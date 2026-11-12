---
api_specs:
- filename: compareanswering-com-enquiry-api-openapi.yml
  format: yaml
  label: Compare Answering Enquiry API
  slug: compareanswering-com-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compareanswering-com/openapi/compareanswering-com-enquiry-api-openapi.yml
- filename: compareanswering-com-guide-api-openapi.yml
  format: yaml
  label: Compare Answering Guide API
  slug: compareanswering-com-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compareanswering-com/openapi/compareanswering-com-guide-api-openapi.yml
- filename: compareanswering-com-mcp-api-openapi.yml
  format: yaml
  label: Compare Answering MCP API
  slug: compareanswering-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compareanswering-com/openapi/compareanswering-com-mcp-api-openapi.yml
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
    llms_txt_url: https://compareanswering.com/llms.txt
    x-probed: https://compareanswering.com
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
name: Compare Answering
provenance_date: '2026-11-09'
provider_name: Compare Answering
provider_slug: compareanswering-com
slug: compareanswering-com-ai-preferences
source_date: '2026-11-09'
source_filename: compareanswering-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://compareanswering.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Compare Answering\naid: compareanswering-com\nurl: https://compareanswering.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: Scraping that removes attribution, or republishing tables wholesale without a link, is not permitted.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: null\n  llms_txt_url: https://compareanswering.com/llms.txt\n\
  \  x-probed: https://compareanswering.com\n"
source_yaml_url: https://artifacts.apis.io/compareanswering-com/ai-preferences/compareanswering-com-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from Compare Answering's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Answering Services
- Virtual Receptionists
- Price Comparison
- Pricing Data
- Datasets
- MCP
---
