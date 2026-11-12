---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: You are responsible for what an agent you connect does with the access you give it.
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
    llms_txt_url: null
    x-probed: https://clepit.com
  train_ai:
    stance: prohibited
    text: We do not scan your content for advertising and do not use it to train models.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Clepit
provenance_date: '2026-11-09'
provider_name: Clepit
provider_slug: clepit-com
slug: clepit-com-ai-preferences
source_date: '2026-11-09'
source_filename: clepit-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://clepit.com/en/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Clepit\naid: clepit-com\nurl: https://clepit.com/en/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not scan your content for advertising and do not use it to train models.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: You are responsible for what an agent you connect does with the access you give it.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url:\
  \ null\n  llms_txt_url: null\n  x-probed: https://clepit.com\n"
source_yaml_url: https://artifacts.apis.io/clepit-com/ai-preferences/clepit-com-ai-preferences.yml
stated_fields:
- train_ai
- agent_actions
summary_line: 2 quoted statements, read from Clepit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Block Editor
- Rich Text Editor
- Knowledge Base
- Open Source
- TypeScript
- JSON
- Collaboration
- Wiki
---
