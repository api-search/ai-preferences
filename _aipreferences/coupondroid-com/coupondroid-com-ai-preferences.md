---
api_specs:
- filename: coupondroid-com-a2a-api-openapi.yml
  format: yaml
  label: Coupondroid A2a API
  slug: coupondroid-com-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-a2a-api-openapi.yml
- filename: coupondroid-com-auth-md-api-openapi.yml
  format: yaml
  label: Coupondroid Auth.md API
  slug: coupondroid-com-auth-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-auth-md-api-openapi.yml
- filename: coupondroid-com-llms-txt-api-openapi.yml
  format: yaml
  label: Coupondroid Llms.txt API
  slug: coupondroid-com-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-llms-txt-api-openapi.yml
- filename: coupondroid-com-mcp-api-openapi.yml
  format: yaml
  label: Coupondroid MCP API
  slug: coupondroid-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-mcp-api-openapi.yml
- filename: coupondroid-com-well-known-api-openapi.yml
  format: yaml
  label: Coupondroid .well Known API
  slug: coupondroid-com-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-well-known-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Scrape, crawl at volume, or use bots or scripts to harvest our coupon database.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: unstated
    text: null
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: null
    x-probed: https://coupondroid.com
  train_ai:
    stance: unstated
    text: null
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Coupondroid
provenance_date: '2026-11-09'
provider_name: Coupondroid
provider_slug: coupondroid-com
slug: coupondroid-com-ai-preferences
source_date: '2026-11-09'
source_filename: coupondroid-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://coupondroid.com/corp/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Coupondroid\naid: coupondroid-com\nurl: https://coupondroid.com/corp/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: Scrape, crawl at volume, or use bots or scripts to harvest our coupon database.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: null\n  x-probed: https://coupondroid.com\n"
source_yaml_url: https://artifacts.apis.io/coupondroid-com/ai-preferences/coupondroid-com-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from Coupondroid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coupons
- Deals
- E-Commerce
- Shopping
- Affiliate Marketing
- MCP
- AI Agents
---
