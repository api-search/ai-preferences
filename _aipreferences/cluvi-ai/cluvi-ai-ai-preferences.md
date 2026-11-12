---
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: copy, scrape, reverse engineer, or build a competing product from the Service
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: AI features operate on Restaurant Data as part of the Service and on the Restaurant's instructions
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://cluvi.ai/llms.txt
    x-probed: https://cluvi.ai
  train_ai:
    stance: conditional
    text: we do not use Restaurant Data to train third-party models without your agreement
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Cluvi AI
provenance_date: '2026-11-09'
provider_name: Cluvi AI
provider_slug: cluvi-ai
slug: cluvi-ai-ai-preferences
source_date: '2026-11-09'
source_filename: cluvi-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cluvi.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Cluvi AI\naid: cluvi-ai\nurl: https://cluvi.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: we do not use Restaurant Data to train third-party models without your agreement\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: AI features operate on Restaurant Data as part of the Service and on the Restaurant's instructions\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: copy, scrape, reverse engineer, or build a competing product from the Service\nagent_purchases:\n  stance: unstated\n  text:\
  \ null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://cluvi.ai/llms.txt\n  x-probed: https://cluvi.ai\n"
source_yaml_url: https://artifacts.apis.io/cluvi-ai/ai-preferences/cluvi-ai-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from Cluvi AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Restaurants
- Hospitality
- Reservations
- WhatsApp
- Messaging
- AI Receptionist
- Model Context Protocol
---
