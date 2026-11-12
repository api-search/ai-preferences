---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: Use automated means to access the Service except through the interfaces we provide.
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
    llms_txt_url: https://convradar.com/llms.txt
    x-probed: https://convradar.com
  train_ai:
    stance: prohibited
    text: ConvRadar does not access, store, transmit, or learn from the content of your conversations with ChatGPT, Claude, or any other AI assistant
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Conversion Radar
provenance_date: '2026-11-09'
provider_name: Conversion Radar
provider_slug: convradar-com
slug: convradar-com-ai-preferences
source_date: '2026-11-09'
source_filename: convradar-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://convradar.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Conversion Radar\naid: convradar-com\nurl: https://convradar.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: ConvRadar does not access, store, transmit, or learn from the content of your conversations with ChatGPT,\n    Claude, or any other AI assistant\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: Use automated means to access the Service except through the interfaces we provide.\nagent_purchases:\n  stance: unstated\n  text: null\n\
  signals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://convradar.com/llms.txt\n  x-probed: https://convradar.com\n"
source_yaml_url: https://artifacts.apis.io/convradar-com/ai-preferences/convradar-com-ai-preferences.yml
stated_fields:
- train_ai
- agent_actions
summary_line: 2 quoted statements, read from Conversion Radar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Google Analytics 4
- MCP
- Conversion Rate Optimization
- E-Commerce
- Benchmarks
- AI Agents
---
