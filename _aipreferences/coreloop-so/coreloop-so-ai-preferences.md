---
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: allowed
    text: Agent protocols are active by default for a published profile.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: Agents, model providers, search systems and other third parties may read, store, cache, index, summarise and reuse your published content.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://coreloop.so/llms.txt
    x-probed: https://coreloop.so
  train_ai:
    stance: conditional
    text: use CoreLoop, or any data obtained from it, to train, fine-tune, evaluate or develop a machine-learning model or service that competes with CoreLoop, without our prior written permission
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: CoreLoop
provenance_date: '2026-11-09'
provider_name: CoreLoop
provider_slug: coreloop-so
slug: coreloop-so-ai-preferences
source_date: '2026-11-09'
source_filename: coreloop-so-ai-preferences.yml
source_heading: AI Preferences
source_page: https://coreloop.so/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CoreLoop\naid: coreloop-so\nurl: https://coreloop.so/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: use CoreLoop, or any data obtained from it, to train, fine-tune, evaluate or develop a machine-learning\n    model or service that competes with CoreLoop, without our prior written permission\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: Agents, model providers, search systems and other third parties may read, store, cache, index, summarise\n    and reuse your published content.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n\
  \  stance: allowed\n  text: Agent protocols are active by default for a published profile.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://coreloop.so/llms.txt\n  x-probed: https://coreloop.so\n"
source_yaml_url: https://artifacts.apis.io/coreloop-so/ai-preferences/coreloop-so-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from CoreLoop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- MCP
- A2A
- llms.txt
- Business Directory
- Agent Discoverability
---
