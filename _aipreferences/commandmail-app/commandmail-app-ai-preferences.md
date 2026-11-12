---
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: conditional
    text: Messages are sent only after your approval or by an agent you authorised to send
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
    llms_txt_url: https://commandmail.app/llms.txt
    x-probed: https://commandmail.app
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
name: Command Mail
provenance_date: '2026-11-09'
provider_name: Command Mail
provider_slug: commandmail-app
slug: commandmail-app-ai-preferences
source_date: '2026-11-09'
source_filename: commandmail-app-ai-preferences.yml
source_heading: AI Preferences
source_page: https://commandmail.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Command Mail\naid: commandmail-app\nurl: https://commandmail.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: Messages are sent only after your approval or by an agent you authorised to send\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://commandmail.app/llms.txt\n  x-probed: https://commandmail.app\n"
source_yaml_url: https://artifacts.apis.io/commandmail-app/ai-preferences/commandmail-app-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from Command Mail's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- AI Agents
- MCP
- Inbox
- Productivity
- Automation
---
