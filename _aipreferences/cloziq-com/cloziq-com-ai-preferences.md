---
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: conditional
    text: If you connect an AI assistant or other client to your workspace (for example, through our MCP connector), that client can read and change your workspace data with your account's permissions.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: The Service includes AI features, such as inbox sorting and labels, suggested and automatic replies and follow-ups, conversation summaries, extracting lead details from messages, lead research, and setup from your website or files.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://cloziq.com/llms.txt
    x-probed: https://cloziq.com
  train_ai:
    stance: prohibited
    text: Cloziq does not permit its third-party AI model providers, or the hosting providers that run AI models Cloziq controls, to use Your Content to train their own models.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Cloziq
provenance_date: '2026-11-09'
provider_name: Cloziq
provider_slug: cloziq-com
slug: cloziq-com-ai-preferences
source_date: '2026-11-09'
source_filename: cloziq-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cloziq.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Cloziq\naid: cloziq-com\nurl: https://cloziq.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: Cloziq does not permit its third-party AI model providers, or the hosting providers that run AI models Cloziq\n    controls, to use Your Content to train their own models.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: The Service includes AI features, such as inbox sorting and labels, suggested and automatic replies and\n    follow-ups, conversation summaries, extracting lead details from messages, lead research, and setup from your\n\
  \    website or files.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: If you connect an AI assistant or other client to your workspace (for example, through our MCP connector),\n    that client can read and change your workspace data with your account's permissions.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://cloziq.com/llms.txt\n  x-probed: https://cloziq.com\n"
source_yaml_url: https://artifacts.apis.io/cloziq-com/ai-preferences/cloziq-com-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from Cloziq's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Sales Agent
- Instagram
- Facebook Messenger
- Direct Messaging
- Appointment Setting
- Sales Automation
- Model Context Protocol
---
