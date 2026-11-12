---
api_specs:
- filename: commutescout-com-tools-api-openapi.yml
  format: yaml
  label: CommuteScout Tools API
  slug: commutescout-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commutescout-com/openapi/commutescout-com-tools-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: no scraping at volumes that degrade it for others, no attempts to bypass rate limits or access controls
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
    llms_txt_url: https://commutescout.com/llms.txt
    x-probed: https://commutescout.com
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
name: CommuteScout
provenance_date: '2026-11-09'
provider_name: CommuteScout
provider_slug: commutescout-com
slug: commutescout-com-ai-preferences
source_date: '2026-11-09'
source_filename: commutescout-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://commutescout.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CommuteScout\naid: commutescout-com\nurl: https://commutescout.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: no scraping at volumes that degrade it for others, no attempts to bypass rate limits or access controls\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: null\n  llms_txt_url: https://commutescout.com/llms.txt\n\
  \  x-probed: https://commutescout.com\n"
source_yaml_url: https://artifacts.apis.io/commutescout-com/ai-preferences/commutescout-com-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from CommuteScout's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Traffic
- Road Conditions
- Transportation
- Navigation
- Route Planning
- Maps
- MCP
- Open Source
---
