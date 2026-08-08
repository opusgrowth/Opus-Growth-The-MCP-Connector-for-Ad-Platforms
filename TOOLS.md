# Tool catalog

All 282 tools exposed by the Opus Growth MCP connector (`https://mcp.opus-growth.com/mcp`).

`write` tools always run as a **dry-run preview first** and are applied only after you approve.

## Google Ads + account & website operations (84)

| Tool | What it does | Type |
|---|---|---|
| `account_audit` | Account Audit | read |
| `add_keywords` | Add Keywords | write |
| `add_negative_keyword` | Add Negative Keyword | write |
| `add_pmax_images` | Add PMax Images | write |
| `apply_recommendation` | Apply Recommendation | write |
| `budget_pacing_alerts` | Budget Pacing Alerts | read |
| `client_report` | Client Report (White-Label) | read |
| `client_report_link` | Shareable Report Link | write |
| `competitor_ads` | Competitor Ads | read |
| `conversion_tracking_health` | Conversion Tracking Health | read |
| `create_ad_group` | Create Ad Group | write |
| `create_app_campaign` | Create App Campaign | write |
| `create_customer_match_audience` | Create Customer Match Audience | write |
| `create_demand_gen_campaign` | Create Demand Gen Campaign | write |
| `create_lookalike_audience` | Create Lookalike Audience | write |
| `create_pmax_campaign` | Create Performance Max Campaign | write |
| `create_responsive_search_ad` | Create Responsive Search Ad | write |
| `create_search_campaign` | Create Search Campaign | write |
| `create_trial_site` | Create Free Trial Website | write |
| `create_website_audience` | Create Website Audience | write |
| `dismiss_recommendations` | Dismiss Recommendation | write |
| `get_ad_details` | Ad Details | read |
| `get_ad_schedule` | Ad Schedule (Read) | read |
| `get_campaign_targeting` | Campaign Targeting (Read) | read |
| `get_change_history` | Change History | read |
| `get_conversion_settings` | Conversion Settings (Read) | read |
| `get_conversion_tags` | Read Conversion Tag | read |
| `list_conversion_goals` | Read Conversion Goals | read |
| `update_conversion_goal` | Update Conversion Goal (primary/secondary) | write |
| `set_call_reporting` | Call Reporting Settings | write |
| `get_pmax_assets` | PMax Assets (Read) | read |
| `get_shared_negative_list` | Shared Negative List | read |
| `impression_share_analysis` | Impression Share Analysis | read |
| `instant_audit` | Instant Audit | read |
| `keyword_opportunities` | Keyword Opportunities | read |
| `keyword_planner` | Keyword Planner | read |
| `keyword_report` | Keyword Report | read |
| `list_ad_extensions` | Campaign Extensions | read |
| `list_assets` | Asset Library | read |
| `list_audiences` | List Audiences | read |
| `list_entities` | List Entities | read |
| `list_experiments` | List Experiments | read |
| `list_extension_assets` | List Extension Assets | read |
| `list_negative_keywords` | Negative Keywords | read |
| `list_recommendations` | Google Ads Recommendations | read |
| `list_servers` | List Hosting Servers | read |
| `list_shared_negative_lists` | Shared Negative Lists | read |
| `manage_audience_targeting` | Attach/Remove/Exclude Audience Targeting | write |
| `manage_bidding_strategies` | Set Bid Strategy | write |
| `manage_portfolio_bidding_strategy` | Portfolio (Shared) Bid Strategy | write |
| `manage_campaign_proximity` | Manage Campaign Proximity (radius targeting) | destroy |
| `manage_device_targeting` | Manage Device Targeting (bid adjustments) | write |
| `manage_campaign_settings` | Campaign Settings (network/location type/tracking) | write |
| `manage_conversion_actions` | Create Conversion Action | write |
| `manage_extension_assets` | Add Extension Assets | write |
| `manage_keywords` | Manage Keywords | destroy |
| `manage_shared_negative_list` | Shared Negative List Mgmt | write |
| `marketing_insights` | Marketing Opportunities | read |
| `marketing_overview` | Marketing Overview (Funnel) | read |
| `pause_campaign` | Pause Campaign | write |
| `performance_report` | Performance Report | read |
| `portfolio_report` | Portfolio Report (Multi-Account) | read |
| `provide_contact_details` | Provide Contact Details | write |
| `remove_extension_assets` | Remove Extension Assets | destroy |
| `remove_negative_keyword` | Remove Negative Keyword | destroy |
| `rsa_asset_performance` | RSA Ad Strength & Asset Performance | read |
| `search_terms_report` | Search Terms Report | read |
| `set_ad_schedule` | Set Ad Schedule | write |
| `set_campaign_budget` | Set Campaign Budget | write |
| `set_campaign_targeting` | Set Campaign Targeting | write |
| `set_conversion_settings` | Conversion Value/Count Settings | write |
| `site_info` | Hosting Server Info | read |
| `site_list_files` | List Website Files | read |
| `site_preview` | Preview Site Screenshot | read |
| `site_read_file` | Read Website File | read |
| `site_versions` | List Website Versions | read |
| `site_edit_file` | Edit Website File | write |
| `site_restore` | Restore Website Version | write |
| `site_run_command` | Run Server Command | destroy |
| `site_write_file` | Write Website File | write |
| `site_fetch` | Fetch File To Site | write |
| `smart_negative_keywords` | Smart Negative Keywords | read |
| `update_ad_status` | Update Ad Status | write |
| `update_campaign_status` | Update Campaign Status | write |
| `update_conversion_action` | Update Conversion Action (primary/secondary) | write |
| `update_pmax_assets` | Update PMax Assets | write |
| `update_rsa` | Update Responsive Search Ad | write |
| `upload_conversion_adjustments` | Adjust Conversions (refund/restate) | write |
| `upload_image_asset` | Upload Image Asset | write |
| `upload_offline_conversions` | Upload Offline Conversions | write |

## Microsoft Advertising (36)

| Tool | What it does | Type |
|---|---|---|
| `add_microsoft_ad_schedule` | Microsoft Ad Schedule | write |
| `add_microsoft_demographic_target` | Microsoft Demographic Target | write |
| `add_microsoft_device_target` | Microsoft Device Target | write |
| `add_microsoft_keywords` | Add Microsoft Keywords | write |
| `add_microsoft_location_target` | Microsoft Location Target | write |
| `add_microsoft_negative_keywords` | Microsoft Negative Keywords | write |
| `connect_microsoft_ads` | Connect Microsoft Advertising | write |
| `create_microsoft_ad_group` | Create Microsoft Ad Group | write |
| `create_microsoft_campaign` | Create Microsoft Campaign | write |
| `create_microsoft_conversion_goal` | Create Microsoft Conversion Goal | write |
| `create_microsoft_remarketing_list` | Microsoft Remarketing Audience | write |
| `create_microsoft_responsive_search_ad` | Create Microsoft RSA | write |
| `create_microsoft_uet_tag` | Create Microsoft UET Tag | write |
| `delete_microsoft_audience` | Delete Microsoft Audience | destroy |
| `delete_microsoft_campaign` | Delete Microsoft Campaign | destroy |
| `list_microsoft_accounts` | Microsoft Ad Accounts | read |
| `list_microsoft_ad_groups` | Microsoft Ad Groups | read |
| `list_microsoft_ads` | Microsoft Ads | read |
| `list_microsoft_audiences` | Microsoft Audiences | read |
| `list_microsoft_campaigns` | Microsoft Campaigns | read |
| `list_microsoft_conversion_goals` | Microsoft Conversion Goals | read |
| `list_microsoft_keywords` | Microsoft Keywords | read |
| `list_microsoft_negative_keywords` | Microsoft Negative Keywords | read |
| `list_microsoft_uet_tags` | Microsoft UET Tags | read |
| `microsoft_entity_performance_report` | Microsoft Breakdown Report | read |
| `microsoft_location_search` | Microsoft Location Search | read |
| `microsoft_performance_report` | Microsoft Performance Report | read |
| `remove_microsoft_negative_keywords` | Remove Microsoft Negative Keywords | destroy |
| `set_microsoft_bid_strategy` | Microsoft Bid Strategy | write |
| `update_microsoft_ad_group_status` | Microsoft Ad Group Status | write |
| `update_microsoft_ad_group` | Update Microsoft Ad Group | write |
| `update_microsoft_ad_status` | Microsoft Ad Status | write |
| `update_microsoft_campaign_budget` | Microsoft Campaign Budget | write |
| `update_microsoft_campaign_status` | Microsoft Campaign Status | write |
| `update_microsoft_keyword` | Update Microsoft Keyword | write |
| `upload_microsoft_offline_conversions` | Upload Microsoft Offline Conversions | write |

## TikTok Ads (30)

| Tool | What it does | Type |
|---|---|---|
| `connect_tiktok_ads` | Connect TikTok Ads | write |
| `create_tiktok_ad` | Create TikTok Ad | write |
| `create_tiktok_adgroup` | Create TikTok Ad Group | write |
| `create_tiktok_campaign` | Create TikTok Campaign | write |
| `create_tiktok_identity` | Create TikTok Ad Identity | write |
| `create_tiktok_lookalike_audience` | Create TikTok Lookalike Audience | write |
| `list_tiktok_ad_accounts` | TikTok Ad Accounts | read |
| `list_tiktok_adgroups` | TikTok Ad Groups | read |
| `list_tiktok_ads` | TikTok Ads | read |
| `list_tiktok_audiences` | TikTok Audiences | read |
| `list_tiktok_bc_advertisers` | TikTok BC Ad Accounts | read |
| `list_tiktok_business_centers` | TikTok Business Centers | read |
| `list_tiktok_campaigns` | TikTok Campaigns | read |
| `list_tiktok_identities` | TikTok Identities | read |
| `create_tiktok_pixel` | Create TikTok Pixel | write |
| `list_tiktok_pixels` | TikTok Pixels | read |
| `send_tiktok_conversion_event` | Send TikTok Conversion Event (Events API) | write |
| `tiktok_campaign_report` | TikTok Performance Report | read |
| `tiktok_region_search` | TikTok Location Search | read |
| `tiktok_targeting_search` | TikTok Targeting Search | read |
| `update_tiktok_ad_status` | Update TikTok Ad Status | write |
| `update_tiktok_ad` | Update TikTok Ad Creative | write |
| `update_tiktok_adgroup` | Update TikTok Ad Group Targeting | write |
| `update_tiktok_adgroup_budget` | Update TikTok Ad Group Budget | write |
| `update_tiktok_adgroup_status` | Update TikTok Ad Group Status | write |
| `update_tiktok_campaign` | Update TikTok Campaign | write |
| `update_tiktok_campaign_budget` | Update TikTok Campaign Budget | write |
| `update_tiktok_campaign_status` | Update TikTok Campaign Status | write |
| `upload_tiktok_image` | Upload TikTok Image | write |
| `upload_tiktok_video` | Upload TikTok Video | write |

## LinkedIn Ads (21)

| Tool | What it does | Type |
|---|---|---|
| `attach_linkedin_conversion` | Attach LinkedIn Conversion | write |
| `detach_linkedin_conversion` | Detach LinkedIn Conversion | destroy |
| `connect_linkedin_ads` | Connect LinkedIn Ads | write |
| `create_linkedin_campaign` | Create LinkedIn Campaign | write |
| `create_linkedin_campaign_group` | Create LinkedIn Campaign Group | write |
| `create_linkedin_post_ad` | Create LinkedIn Post Ad | write |
| `create_linkedin_text_ad` | Create LinkedIn Text Ad | write |
| `delete_linkedin_campaign` | Delete LinkedIn Campaign | destroy |
| `delete_linkedin_campaign_group` | Delete LinkedIn Campaign Group | destroy |
| `delete_linkedin_creative` | Delete LinkedIn Creative | destroy |
| `linkedin_audience_forecast` | LinkedIn Audience Forecast | read |
| `linkedin_ad_copy` | LinkedIn Ad Copy | read |
| `linkedin_bid_recommendations` | LinkedIn Bid Recommendations | read |
| `linkedin_campaign_analytics` | LinkedIn Performance Report | read |
| `linkedin_targeting_search` | LinkedIn Targeting Search | read |
| `list_linkedin_ad_accounts` | LinkedIn Ad Accounts | read |
| `list_linkedin_campaign_groups` | LinkedIn Campaign Groups | read |
| `list_linkedin_campaigns` | LinkedIn Campaigns | read |
| `list_linkedin_creatives` | LinkedIn Creatives | read |
| `list_linkedin_conversions` | LinkedIn Conversions | read |
| `list_linkedin_audiences` | LinkedIn Matched Audiences | read |
| `update_linkedin_campaign` | Update LinkedIn Campaign | write |
| `update_linkedin_campaign_group` | Update LinkedIn Campaign Group | write |
| `update_linkedin_campaign_targeting` | Update LinkedIn Targeting | write |
| `update_linkedin_creative_status` | Update LinkedIn Creative Status | write |

## Meta Ads (45 — in final review)

| Tool | What it does | Type |
|---|---|---|
| `connect_meta_ads` | Connect Meta Ads | write |
| `copy_meta_entity` | Copy Meta Entity | write |
| `create_meta_adset` | Create Meta Ad Set | write |
| `create_meta_campaign` | Create Meta Campaign | write |
| `create_meta_carousel_ad` | Create Meta Carousel Ad | write |
| `create_meta_dynamic_ad` | Create Meta Dynamic Ad | write |
| `create_meta_engagement_audience` | Create Meta Engagement Audience | write |
| `create_meta_link_ad` | Create Meta Link Ad | write |
| `create_meta_lookalike_audience` | Create Meta Lookalike Audience | write |
| `create_meta_post_ad` | Create Meta Post Ad | write |
| `create_meta_video_ad` | Create Meta Video Ad | write |
| `create_meta_instagram_post_ad` | Create Meta Instagram Post Ad | write |
| `create_meta_website_audience` | Create Meta Website Audience | write |
| `upload_meta_image` | Upload Meta Image | write |
| `upload_meta_video` | Upload Meta Video | write |
| `delete_meta_audience` | Delete Meta Audience | destroy |
| `delete_meta_ad` | Delete Meta Ad | destroy |
| `delete_meta_adset` | Delete Meta Ad Set | destroy |
| `delete_meta_campaign` | Delete Meta Campaign | destroy |
| `list_meta_ad_accounts` | Meta Ad Accounts | read |
| `list_meta_ads` | Meta Ads | read |
| `list_meta_adsets` | Meta Ad Sets | read |
| `list_meta_audiences` | Meta Audiences | read |
| `list_meta_campaigns` | Meta Campaigns | read |
| `list_meta_catalogs` | Meta Catalogs | read |
| `list_meta_product_sets` | Meta Product Sets | read |
| `list_meta_page_posts` | Meta Page Posts | read |
| `list_meta_instagram_posts` | Meta Instagram Posts | read |
| `list_meta_instagram_accounts` | Meta Instagram Accounts | read |
| `list_meta_pages` | Meta Pages | read |
| `preview_meta_ad` | Preview Meta Ad | read |
| `list_meta_saved_audiences` | Meta Saved Audiences | read |
| `list_meta_custom_conversions` | Meta Custom Conversions | read |
| `create_meta_custom_conversion` | Create Meta Custom Conversion | write |
| `meta_delivery_estimate` | Meta Delivery Estimate | read |
| `create_meta_ab_test` | Create Meta A/B Test | write |
| `list_meta_pixels` | Meta Pixels | read |
| `send_meta_conversion_event` | Send Meta Conversion Event (CAPI) | write |
| `meta_campaign_insights` | Meta Campaign Insights | read |
| `meta_reach_estimate` | Meta Reach Estimate | read |
| `search_meta_interests` | Meta Interest Search | read |
| `update_meta_ad` | Update Meta Ad | write |
| `update_meta_ad_creative` | Update Meta Ad Creative | write |
| `update_meta_adset` | Update Meta Ad Set | write |
| `update_meta_campaign` | Update Meta Campaign | write |

## Google Search Console + SEO (7)

| Tool | What it does | Type |
|---|---|---|
| `connect_search_console` | Connect Search Console | write |
| `gsc_list_sites` | Search Console Sites | read |
| `gsc_performance` | Organic Search Performance | read |
| `gsc_sitemaps` | Sitemaps | read |
| `gsc_submit_sitemap` | Submit Sitemap | write |
| `gsc_url_inspect` | URL Index Inspection | read |
| `seo_audit` | SEO & Speed Audit | read |
| `seo_keyword_research` | SEO Keyword Research | read |
| `seo_competitor_gap` | SEO Competitor Gap | read |
| `seo_backlinks` | SEO Backlink Profile | read |
| `seo_technical_audit` | SEO Technical Audit | read |
| `seo_geo_citations` | SEO AI-Citation (GEO) | read |
| `seo_serp_analysis` | SEO SERP Analysis | read |
| `seo_ranked_keywords` | SEO Ranked Keywords | read |
| `seo_keyword_trends` | SEO Keyword Trends | read |
| `seo_site_technologies` | SEO Site Technologies | read |
| `core_web_vitals` | Core Web Vitals | read |

## Google Analytics 4 (10)

| Tool | What it does | Type |
|---|---|---|
| `connect_ga4` | Connect Google Analytics | write |
| `ga4_create_conversion` | Create GA4 Conversion | write |
| `ga4_create_custom_dimension` | Create GA4 Custom Dimension | write |
| `ga4_link_google_ads` | Link GA4 to Google Ads | write |
| `ga4_list_ads_links` | GA4 Google Ads Links | read |
| `ga4_list_conversions` | GA4 Conversions | read |
| `ga4_list_properties` | GA4 Properties | read |
| `ga4_overview` | GA4 Overview | read |
| `ga4_realtime` | GA4 Realtime Users | read |
| `ga4_report` | GA4 Breakdown Report | read |

## Google Tag Manager (22)

| Tool | What it does | Type |
|---|---|---|
| `connect_tag_manager` | Connect Tag Manager | write |
| `create_gtm_container` | Create GTM Container | write |
| `create_gtm_tag` | Create GTM Tag | destroy |
| `create_gtm_trigger` | Create GTM Trigger | write |
| `create_gtm_variable` | Create GTM Variable | write |
| `create_gtm_workspace` | Create GTM Workspace | write |
| `delete_gtm_container` | Delete GTM Container | destroy |
| `delete_gtm_entity` | Delete GTM Entity | destroy |
| `list_gtm_accounts` | GTM Accounts | read |
| `list_gtm_containers` | GTM Containers | read |
| `list_gtm_permissions` | GTM User Permissions | read |
| `list_gtm_tags` | GTM Tags | read |
| `list_gtm_triggers` | GTM Triggers | read |
| `list_gtm_variables` | GTM Variables | read |
| `enable_gtm_builtin_variables` | Enable GTM Built-in Variables | write |
| `gtm_workspace_status` | GTM Pending Changes | read |
| `list_gtm_versions` | GTM Version History | read |
| `list_gtm_workspaces` | GTM Workspaces | read |
| `manage_gtm_permissions` | Manage GTM Permissions | write |
| `publish_gtm_container` | Publish GTM Container | destroy |
| `rollback_gtm_version` | Roll Back GTM Version | destroy |
| `update_gtm_entity` | Edit GTM Entity | destroy |

## Google Business Profile (7)

| Tool | What it does | Type |
|---|---|---|
| `connect_business_profile` | Connect Business Profile | write |
| `gbp_create_post` | Create Business Post | write |
| `gbp_list_locations` | Business Locations | read |
| `gbp_location_details` | Business Details | read |
| `gbp_reply_review` | Reply to Review | write |
| `gbp_reviews` | Business Reviews | read |
| `gbp_update_location` | Update Business Details | write |

## YouTube (5)

| Tool | What it does | Type |
|---|---|---|
| `connect_youtube` | Connect YouTube | write |
| `youtube_channels` | YouTube Channels | read |
| `youtube_overview` | YouTube Overview | read |
| `youtube_top_videos` | YouTube Top Videos | read |
| `youtube_traffic_sources` | YouTube Traffic Sources | read |

## System (10)

| Tool | What it does | Type |
|---|---|---|
| `connect_google_ads` | Connect Google Ads | write |
| `fetch` | Get Account Details | read |
| `get_billing_status` | Billing Status | read |
| `list_accounts` | Google Ads Accounts | read |
| `report_issue` | Report Issue | write |
| `scaffold_site` | Install Professional Site Starter | write |
| `search` | Search Ad Accounts | read |
| `site_design_guide` | Professional Site Design Guide | read |
| `site_seo_guide` | Site SEO & Schema Guide | read |
| `start_subscription` | Start Subscription | write |

