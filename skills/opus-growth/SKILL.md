---
name: opus-growth
description: Manages and reports on Google Ads, Meta Ads, Microsoft Advertising, TikTok Ads, LinkedIn Ads and ChatGPT Ads, plus GA4, Search Console, Tag Manager, YouTube and Google Business Profile, through the Opus Growth connector. Use when the user asks how their ads are performing, wants a campaign created, paused, rebudgeted or audited, wants wasted spend found, or asks for a client report, a Data Studio (Looker Studio) report or a PDF.
---

# Opus Growth: ad operations from chat

Opus Growth is a remote connector that gives you live, read and write access to the user's ad accounts and Google marketing data. Every change is previewed first and only applied after the user approves it.

## 1. Make sure the connector is available

Check whether tools such as `get_report`, `list_entities` and `describe` are available to you. If they are not, the user has not connected Opus Growth yet. Give them the step for their app and stop until it is done:

- **Claude (web, desktop, mobile):** Settings > Connectors > Add custom connector, then paste `https://mcp.opus-growth.com/mcp`.
- **ChatGPT (Plus, Pro, Business):** open the Plugins menu, choose Add custom MCP server and paste `https://mcp.opus-growth.com/mcp`.
- **Claude Code:** run `claude mcp add --transport http opus-growth https://mcp.opus-growth.com/mcp`.
- **Cursor:** install the Opus Growth plugin, or add `https://mcp.opus-growth.com/mcp` as a remote MCP server in Cursor Settings, then sign in when Cursor asks.

The user signs in with Google the first time. A free trial with 75 credits that never expire starts automatically, with no credit card. Ad accounts are connected from the chat (for example "connect my Google Ads account") or from the panel at https://platform.opus-growth.com.

## 2. Read before you act

1. Find accounts and objects with `list_entities(platform, entity, account, parent_id)`. Platforms: `google_ads`, `meta`, `microsoft`, `tiktok`, `linkedin`, `chatgpt_ads`.
2. Pull numbers with `get_report(platform, account, days, level, breakdown)`. It also covers `ga4`, `search_console`, `youtube` and `business_profile`.
3. If you are unsure which levels, breakdowns or entity names a platform accepts, call `describe(platform)` instead of guessing.
4. The visible tool list is a core subset. For WordPress, Google Business Profile, hosting, Tag Manager, audiences, conversions or platform specific creative tools, call `search_tools(query)` before telling the user something is not possible.

Always state the account, the date range and the currency with the numbers you report.

## 3. Changing things safely

- Write tools take `confirm`. Call them first with `confirm=false`: you get a preview of exactly what will change. Show it to the user in plain words, and only call again with `confirm=true` after they clearly approve.
- Never apply a change the user did not ask for. Suggest it, explain why, wait.
- Budget changes have built in safety limits: a single increase above 50 percent is blocked, the total increase within 24 hours may not exceed 100 percent, and a single cut may not exceed 80 percent. If the user needs more, explain the limit and split the change over time.
- New Google Ads campaigns start paused. Say so, and enable a campaign only when the user asks for it to start serving.
- If a tool returns an error, read its message, fix the input and retry once. If it still fails, tell the user what failed and offer `report_issue`.

## 4. Common requests

| The user says | Do this |
|---|---|
| "How are my ads doing?" | `get_report` per connected platform for the last 30 days, compare with the previous period, lead with spend, conversions and cost per conversion. |
| "Where am I wasting money?" | `search_terms_report` and `account_audit`, then propose negatives with `add_negative_keyword` (preview first). |
| "Pause campaign X" | Find it with `list_entities`, then `update_campaign_status` with `confirm=false`, show, then `confirm=true`. |
| "Give me a report for my client" | `marketing_report_pdf` returns a download link to a branded PDF. Only use `looker_studio_report` when the user asks for Data Studio or Looker Studio by name. |
| "Build me a website" | Uses the user's AI Server: `list_sites`, `add_site`, `site_write_file`. Use `search_tools("website")` for the rest. |

More detail per workflow is in `references/workflows.md`.

## 5. Style

Speak in the user's language and in plain words, not API terms. Show money with its currency. Keep previews short: what changes, from what, to what, and the expected effect. Credits: reads are light, live changes cost a little more; the user can check their balance with `get_billing_status`.
