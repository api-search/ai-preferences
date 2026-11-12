---
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: conditional
    text: El usuario es responsable de las acciones que su asistente de inteligencia artificial ejecute a través del conector MCP de la Plataforma con los permisos que le haya concedido
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
    llms_txt_url: https://clonio.es/llms.txt
    x-probed: https://clonio.es
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
name: Clonio
provenance_date: '2026-11-09'
provider_name: Clonio
provider_slug: clonio-es
slug: clonio-es-ai-preferences
source_date: '2026-11-09'
source_filename: clonio-es-ai-preferences.yml
source_heading: AI Preferences
source_page: https://clonio.es/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Clonio\naid: clonio-es\nurl: https://clonio.es/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: El usuario es responsable de las acciones que su asistente de inteligencia artificial ejecute a través del\n    conector MCP de la Plataforma con los permisos que le haya concedido\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n \
  \ ai_txt_url: null\n  llms_txt_url: https://clonio.es/llms.txt\n  x-probed: https://clonio.es\n"
source_yaml_url: https://artifacts.apis.io/clonio-es/ai-preferences/clonio-es-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from Clonio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LinkedIn
- Content Generation
- Social Media
- Marketing
- Scheduling
- MCP
---
