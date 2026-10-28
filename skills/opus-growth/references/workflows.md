# Opus Growth workflows

## Weekly performance check
1. `list_entities(platform, "campaigns", account)` for each connected ad platform.
2. `get_report(platform, account, days=7, level="campaign")` and the same for the 7 days before.
3. Report per platform: spend, conversions, cost per conversion, conversion value and ROAS where tracked.
4. Flag campaigns whose cost per conversion rose by more than 30 percent, campaigns spending with zero conversions, and budget limited campaigns.
5. Suggest at most three actions, each with the expected effect. Apply nothing without approval.

## Wasted spend cleanup (Google Ads, Microsoft Advertising)
1. `search_terms_report` for the last 30 days.
2. Group terms that spent money without converting and are clearly off topic.
3. Propose them as negative keywords (phrase match by default) with `add_negative_keyword`, `confirm=false`.
4. After approval, apply with `confirm=true` and report how much spend the excluded terms used in the period.

## Budget change
1. Read the current daily budget with `list_entities` or `get_report`.
2. Call `set_campaign_budget` with `confirm=false` and show the old and new amount.
3. Respect the safety limits: one increase up to +50 percent, up to +100 percent within 24 hours, one cut up to -80 percent.
4. Apply with `confirm=true` only after the user approves.

## Client reporting
- Default: `marketing_report_pdf` (one download link covering the connected ad platforms, plus GA4, Search Console and Business Profile when connected). Pass `language` so the report matches the user's language.
- Data Studio (Looker Studio): `looker_studio_report` returns a link that copies a ready template into the user's own Google account. Data Studio asks the user to sign in to Opus Growth once.

## Conversion tracking health
1. `conversion_tracking_health` (search with `search_tools("conversion")` if it is not visible).
2. Explain what is missing in plain words: which action, on which platform, since when.
3. Offer the fix as a preview first.

## Websites on the user's AI Server
- `list_sites` shows the sites on the server and the disk in use. One server holds up to 15 sites, each on its own domain.
- `add_site` adds a site on a new domain; the user only changes the nameservers at their registrar.
- Edit pages with `site_write_file`; fetch images server side with `site_fetch` instead of pasting image data into the chat.
