---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: Please do not break the law, send abusive or automated traffic that overloads the service, try to bypass limits or security
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: You may use the MCP server and the city data files free of charge, including from AI assistants, agents and apps, as long as you follow these terms and keep the attribution above.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://courtlygo.com/llms.txt
    x-probed: https://courtlygo.com
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
name: CourtlyGo
provenance_date: '2026-11-09'
provider_name: CourtlyGo
provider_slug: courtlygo-com
slug: courtlygo-com-ai-preferences
source_date: '2026-11-09'
source_filename: courtlygo-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://courtlygo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CourtlyGo\naid: courtlygo-com\nurl: https://courtlygo.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: You may use the MCP server and the city data files free of charge, including from AI assistants, agents\n    and apps, as long as you follow these terms and keep the attribution above.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: Please do not break the law, send abusive or automated traffic that overloads the service, try to bypass\n\
  \    limits or security\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://courtlygo.com/llms.txt\n  x-probed: https://courtlygo.com\n"
source_yaml_url: https://artifacts.apis.io/courtlygo-com/ai-preferences/courtlygo-com-ai-preferences.yml
stated_fields:
- ai_use
- agent_actions
summary_line: 2 quoted statements, read from CourtlyGo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sports
- Tennis
- Pickleball
- Padel
- Open Data
- OpenStreetMap
- MCP
- AI Agents
- Geolocation
---
