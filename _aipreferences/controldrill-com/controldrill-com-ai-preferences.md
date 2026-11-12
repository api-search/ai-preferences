---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: unstated
    text: null
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
    llms_txt_url: https://controldrill.com/llms.txt
    x-probed: https://controldrill.com
  train_ai:
    stance: prohibited
    text: We do not use customer content to train models.
  train_genai:
    stance: prohibited
    text: We do not use customer content to train models.
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: ControlDrill
provenance_date: '2026-11-09'
provider_name: ControlDrill
provider_slug: controldrill-com
slug: controldrill-com-ai-preferences
source_date: '2026-11-09'
source_filename: controldrill-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://controldrill.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: ControlDrill\naid: controldrill-com\nurl: https://controldrill.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not use customer content to train models.\ntrain_genai:\n  stance: prohibited\n  text: We do not use customer content to train models.\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://controldrill.com/llms.txt\n\
  \  x-probed: https://controldrill.com\n"
source_yaml_url: https://artifacts.apis.io/controldrill-com/ai-preferences/controldrill-com-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
summary_line: 2 quoted statements, read from ControlDrill's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Incident Response
- Tabletop Exercises
- Compliance
- Security
- SOC 2
- Audit Evidence
- MCP
---
