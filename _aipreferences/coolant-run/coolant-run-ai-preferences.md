---
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: allowed
    text: coolant.run is an endpoint for software agents.
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
    llms_txt_url: https://coolant.run/llms.txt
    x-probed: https://coolant.run
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
name: Coolant
provenance_date: '2026-11-09'
provider_name: Coolant
provider_slug: coolant-run
slug: coolant-run-ai-preferences
source_date: '2026-11-09'
source_filename: coolant-run-ai-preferences.yml
source_heading: AI Preferences
source_page: https://coolant.run/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Coolant\naid: coolant-run\nurl: https://coolant.run/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: allowed\n  text: coolant.run is an endpoint for software agents.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://coolant.run/llms.txt\n  x-probed: https://coolant.run\n"
source_yaml_url: https://artifacts.apis.io/coolant-run/ai-preferences/coolant-run-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from Coolant's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- MCP
- x402
- Agent Tools
- Micropayments
- Developer Utilities
---
