---
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: conditional
    text: When you authorise a program to connect to your brain, that program works with exactly your permissions
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: the artificial-intelligence programs you connect can read and write with your permissions
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://cobrain.space/llms.txt
    x-probed: https://cobrain.space
  train_ai:
    stance: prohibited
    text: We do not use them to train models.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Cobrain
provenance_date: '2026-11-09'
provider_name: Cobrain
provider_slug: cobrain-space
slug: cobrain-space-ai-preferences
source_date: '2026-11-09'
source_filename: cobrain-space-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cobrain.space/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Cobrain\naid: cobrain-space\nurl: https://cobrain.space/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not use them to train models.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: the artificial-intelligence programs you connect can read and write with your permissions\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: When you authorise a program to connect to your brain, that program works with exactly your permissions\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header:\
  \ false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://cobrain.space/llms.txt\n  x-probed: https://cobrain.space\n"
source_yaml_url: https://artifacts.apis.io/cobrain-space/ai-preferences/cobrain-space-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from Cobrain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Memory
- Model Context Protocol
- MCP Server
- Knowledge Management
- Markdown
- Note Taking
- Collaboration
- Artificial Intelligence
---
