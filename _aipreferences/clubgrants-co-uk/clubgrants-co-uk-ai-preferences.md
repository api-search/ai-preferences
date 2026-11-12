---
api_specs:
- filename: clubgrants-co-uk-enquiry-api-openapi.yml
  format: yaml
  label: Club Grants Enquiry API
  slug: clubgrants-co-uk-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clubgrants-co-uk/openapi/clubgrants-co-uk-enquiry-api-openapi.yml
- filename: clubgrants-co-uk-guide-api-openapi.yml
  format: yaml
  label: Club Grants Guide API
  slug: clubgrants-co-uk-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clubgrants-co-uk/openapi/clubgrants-co-uk-guide-api-openapi.yml
- filename: clubgrants-co-uk-mcp-api-openapi.yml
  format: yaml
  label: Club Grants MCP API
  slug: clubgrants-co-uk-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clubgrants-co-uk/openapi/clubgrants-co-uk-mcp-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: conditional
    text: Scraping that removes attribution, or republishing tables wholesale without a link, is not permitted.
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
    content_signals: true
    llms_txt_url: https://clubgrants.co.uk/llms.txt
    x-probed: https://clubgrants.co.uk
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
name: Club Grants
provenance_date: '2026-11-09'
provider_name: Club Grants
provider_slug: clubgrants-co-uk
slug: clubgrants-co-uk-ai-preferences
source_date: '2026-11-09'
source_filename: clubgrants-co-uk-ai-preferences.yml
source_heading: AI Preferences
source_page: https://clubgrants.co.uk/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Club Grants\naid: clubgrants-co-uk\nurl: https://clubgrants.co.uk/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: Scraping that removes attribution, or republishing tables wholesale without a link, is not permitted.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: null\n  llms_txt_url: https://clubgrants.co.uk/llms.txt\n\
  \  x-probed: https://clubgrants.co.uk\n"
source_yaml_url: https://artifacts.apis.io/clubgrants-co-uk/ai-preferences/clubgrants-co-uk-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from Club Grants's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Grants
- Funding
- Sports
- Nonprofit
- Open Data
- United Kingdom
- MCP
---
