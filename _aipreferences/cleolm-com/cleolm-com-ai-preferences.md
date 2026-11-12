---
api_specs:
- filename: cleolm-com-tools-api-openapi.yml
  format: yaml
  label: CleoLM Tools API
  slug: cleolm-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleolm-com/openapi/cleolm-com-tools-api-openapi.yml
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: Use automated scripts, bots, or crawlers to access the Service without our express written permission
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: The Service utilizes multiple artificial intelligence providers and technologies to deliver these features.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://cleolm.com/llms.txt
    x-probed: https://cleolm.com
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
name: CleoLM
provenance_date: '2026-11-09'
provider_name: CleoLM
provider_slug: cleolm-com
slug: cleolm-com-ai-preferences
source_date: '2026-11-09'
source_filename: cleolm-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cleolm.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CleoLM\naid: cleolm-com\nurl: https://cleolm.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: The Service utilizes multiple artificial intelligence providers and technologies to deliver these features.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: Use automated scripts, bots, or crawlers to access the Service without our express written permission\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals:\
  \ false\n  ai_txt_url: null\n  llms_txt_url: https://cleolm.com/llms.txt\n  x-probed: https://cleolm.com\n"
source_yaml_url: https://artifacts.apis.io/cleolm-com/ai-preferences/cleolm-com-ai-preferences.yml
stated_fields:
- ai_use
- agent_actions
summary_line: 2 quoted statements, read from CleoLM's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI
- Transcription
- Podcasts
- YouTube
- Search
- MCP
- Video
---
