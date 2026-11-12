---
api_specs:
- filename: cleve-ai-folders-api-openapi.yml
  format: yaml
  label: Cleve Folders API
  slug: cleve-ai-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleve-ai/openapi/cleve-ai-folders-api-openapi.yml
- filename: cleve-ai-notes-api-openapi.yml
  format: yaml
  label: Cleve Notes API
  slug: cleve-ai-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleve-ai/openapi/cleve-ai-notes-api-openapi.yml
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Reverse engineer, scrape, or use automated means to access the Services beyond what is explicitly permitted.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: When you use these features, relevant context from your request is sent to AI providers to generate a response.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://www.cleve.ai/llms.txt
    x-probed: https://cleve.ai
  train_ai:
    stance: prohibited
    text: We do not train on your content. Neither Cleve nor our AI providers use your User Content or Output to train AI models.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Cleve
provenance_date: '2026-11-09'
provider_name: Cleve
provider_slug: cleve-ai
slug: cleve-ai-ai-preferences
source_date: '2026-11-09'
source_filename: cleve-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.cleve.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Cleve\naid: cleve-ai\nurl: https://www.cleve.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not train on your content. Neither Cleve nor our AI providers use your User Content or Output to train\n    AI models.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: When you use these features, relevant context from your request is sent to AI providers to generate a response.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: Reverse engineer, scrape, or use automated means to access the Services\
  \ beyond what is explicitly permitted.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://www.cleve.ai/llms.txt\n  x-probed: https://cleve.ai\n"
source_yaml_url: https://artifacts.apis.io/cleve-ai/ai-preferences/cleve-ai-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from Cleve's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Writing
- Knowledge Management
- Note Taking
- Collaboration
- Model Context Protocol
- Productivity
---
