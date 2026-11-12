---
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: conditional
    text: You are responsible for any AI agent, connector, or other tool you authorize to act on your account, and for what it does there.
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
    content_signals: true
    llms_txt_url: https://cloche.dev/llms.txt
    x-probed: https://cloche.dev
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
name: Cloche
provenance_date: '2026-11-09'
provider_name: Cloche
provider_slug: cloche-dev
slug: cloche-dev-ai-preferences
source_date: '2026-11-09'
source_filename: cloche-dev-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cloche.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Cloche\naid: cloche-dev\nurl: https://cloche.dev/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: You are responsible for any AI agent, connector, or other tool you authorize to act on your account, and\n    for what it does there.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: null\n  llms_txt_url: https://cloche.dev/llms.txt\n\
  \  x-probed: https://cloche.dev\n"
source_yaml_url: https://artifacts.apis.io/cloche-dev/ai-preferences/cloche-dev-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from Cloche's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- AI Apps
- Governance
- Low Code
- Internal Tools
- Agents
---
