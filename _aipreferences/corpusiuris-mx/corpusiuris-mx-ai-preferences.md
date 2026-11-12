---
api_specs:
- filename: corpusiuris-mx-agent-api-openapi.yml
  format: yaml
  label: Corpus Iuris Agent API
  slug: corpusiuris-mx-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiuris-mx/openapi/corpusiuris-mx-agent-api-openapi.yml
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: consultas automatizadas mediante bots fuera de las interfaces autorizadas
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: Está permitido consultarlas, citarlas y enlazarlas libremente, incluso desde asistentes de IA.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://corpusiuris.mx/llms.txt
    x-probed: https://corpusiuris.mx
  train_ai:
    stance: conditional
    text: Utilizar las búsquedas de la API, del conector MCP o de las páginas públicas para construir, poblar o entrenar bases de datos, índices o modelos que repliquen o compitan con la compilación de Corpus Iuris
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Corpus Iuris
provenance_date: '2026-11-09'
provider_name: Corpus Iuris
provider_slug: corpusiuris-mx
slug: corpusiuris-mx-ai-preferences
source_date: '2026-11-09'
source_filename: corpusiuris-mx-ai-preferences.yml
source_heading: AI Preferences
source_page: https://corpusiuris.mx/terminos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Corpus Iuris\naid: corpusiuris-mx\nurl: https://corpusiuris.mx/terminos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: Utilizar las búsquedas de la API, del conector MCP o de las páginas públicas para construir, poblar o entrenar\n    bases de datos, índices o modelos que repliquen o compitan con la compilación de Corpus Iuris\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: Está permitido consultarlas, citarlas y enlazarlas libremente, incluso desde asistentes de IA.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n\
  \  text: consultas automatizadas mediante bots fuera de las interfaces autorizadas\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://corpusiuris.mx/llms.txt\n  x-probed: https://corpusiuris.mx\n"
source_yaml_url: https://artifacts.apis.io/corpusiuris-mx/ai-preferences/corpusiuris-mx-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from Corpus Iuris's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Research
- Artificial Intelligence
- Mexico
- Jurisprudence
- MCP
- Search
---
