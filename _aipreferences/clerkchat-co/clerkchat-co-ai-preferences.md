---
claim_count: 1
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
    stance: allowed
    text: Clerk Chat may help generate responses from the content and settings you provide.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://clerkchat.co/llms.txt
    x-probed: https://clerkchat.co
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
name: ClerkChat
provenance_date: '2026-11-09'
provider_name: ClerkChat
provider_slug: clerkchat-co
slug: clerkchat-co-ai-preferences
source_date: '2026-11-09'
source_filename: clerkchat-co-ai-preferences.yml
source_heading: AI Preferences
source_page: https://clerkchat.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: ClerkChat\naid: clerkchat-co\nurl: https://clerkchat.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: Clerk Chat may help generate responses from the content and settings you provide.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://clerkchat.co/llms.txt\n  x-probed: https://clerkchat.co\n"
source_yaml_url: https://artifacts.apis.io/clerkchat-co/ai-preferences/clerkchat-co-ai-preferences.yml
stated_fields:
- ai_use
summary_line: 1 quoted statement, read from ClerkChat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Customer Support
- Chatbots
- Messaging
- WhatsApp
- Model Context Protocol
- Conversational AI
---
