---
api_specs:
- filename: collabpls-com-agent-api-openapi.yml
  format: yaml
  label: CollabPls Agent API
  slug: collabpls-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collabpls-com/openapi/collabpls-com-agent-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: unstated
    text: null
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: AI-generated recommendations are always reviewed by human administrators before enforcement.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://collabpls.com/llms.txt
    x-probed: https://collabpls.com
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
name: CollabPls
provenance_date: '2026-11-09'
provider_name: CollabPls
provider_slug: collabpls-com
slug: collabpls-com-ai-preferences
source_date: '2026-11-09'
source_filename: collabpls-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://collabpls.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CollabPls\naid: collabpls-com\nurl: https://collabpls.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: AI-generated recommendations are always reviewed by human administrators before enforcement.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://collabpls.com/llms.txt\n  x-probed:\
  \ https://collabpls.com\n"
source_yaml_url: https://artifacts.apis.io/collabpls-com/ai-preferences/collabpls-com-ai-preferences.yml
stated_fields:
- ai_use
summary_line: 1 quoted statement, read from CollabPls's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Creator Economy
- Marketplace
- Collaboration
- Scheduling
- Social Networking
- MCP
- Agents
---
