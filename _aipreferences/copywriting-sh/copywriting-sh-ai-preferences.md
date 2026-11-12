---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: copy, scrape, crawl, harvest, republish, mirror, or redistribute the Library or the reference tools, in whole or in substantial part
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
    llms_txt_url: https://copywriting.sh/llms.txt
    x-probed: https://copywriting.sh
  train_ai:
    stance: prohibited
    text: use the Service, the Library, or any output to build, train, benchmark, or improve a competing product, model, or dataset
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Copywriting MCP
provenance_date: '2026-11-09'
provider_name: Copywriting MCP
provider_slug: copywriting-sh
slug: copywriting-sh-ai-preferences
source_date: '2026-11-09'
source_filename: copywriting-sh-ai-preferences.yml
source_heading: AI Preferences
source_page: https://copywriting.sh/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Copywriting MCP\naid: copywriting-sh\nurl: https://copywriting.sh/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: use the Service, the Library, or any output to build, train, benchmark, or improve a competing product,\n    model, or dataset\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: copy, scrape, crawl, harvest, republish, mirror, or redistribute the Library or the reference tools, in\n    whole or in substantial part\nagent_purchases:\n\
  \  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://copywriting.sh/llms.txt\n  x-probed: https://copywriting.sh\n"
source_yaml_url: https://artifacts.apis.io/copywriting-sh/ai-preferences/copywriting-sh-ai-preferences.yml
stated_fields:
- train_ai
- agent_actions
summary_line: 2 quoted statements, read from Copywriting MCP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Copywriting
- MCP
- Model Context Protocol
- AI Agents
- Knowledge Base
- Marketing
- Content Writing
---
