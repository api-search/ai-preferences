---
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Unauthorized access to the Service, automated access that puts excessive load on it, or interfering with its operation
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: An AI connected to CLUBS (“AI”) is chosen and connected by the user, and reads and writes records on the Service on the user’s instructions.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: null
    x-probed: https://clubs.place
  train_ai:
    stance: prohibited
    text: We do not use user records to train AI models, and we do not provide them to third parties for training.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: CLUBS
provenance_date: '2026-11-09'
provider_name: CLUBS
provider_slug: clubs-place
slug: clubs-place-ai-preferences
source_date: '2026-11-09'
source_filename: clubs-place-ai-preferences.yml
source_heading: AI Preferences
source_page: https://clubs.place/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CLUBS\naid: clubs-place\nurl: https://clubs.place/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not use user records to train AI models, and we do not provide them to third parties for training.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: An AI connected to CLUBS (“AI”) is chosen and connected by the user, and reads and writes records on the\n    Service on the user’s instructions.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: Unauthorized access to the Service, automated access\
  \ that puts excessive load on it, or interfering with\n    its operation\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: null\n  x-probed: https://clubs.place\n"
source_yaml_url: https://artifacts.apis.io/clubs-place/ai-preferences/clubs-place-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from CLUBS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI
- Model Context Protocol
- Productivity
- Notes
- Reporting
- Japan
---
