---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: You are responsible for how you configure, scope, supervise, and pause automated responders, and for any third-party tools you connect to them.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: The Service includes optional AI features — classification, digests, an inbox assistant, and configurable automated responders.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: true
    llms_txt_url: https://commsync.ai/llms.txt
    x-probed: https://commsync.ai
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
name: CommSync
provenance_date: '2026-11-09'
provider_name: CommSync
provider_slug: commsync-ai
slug: commsync-ai-ai-preferences
source_date: '2026-11-09'
source_filename: commsync-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://commsync.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CommSync\naid: commsync-ai\nurl: https://commsync.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: The Service includes optional AI features — classification, digests, an inbox assistant, and configurable\n    automated responders.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: You are responsible for how you configure, scope, supervise, and pause automated responders, and for any\n    third-party tools you connect to them.\nagent_purchases:\n\
  \  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: null\n  llms_txt_url: https://commsync.ai/llms.txt\n  x-probed: https://commsync.ai\n"
source_yaml_url: https://artifacts.apis.io/commsync-ai/ai-preferences/commsync-ai-ai-preferences.yml
stated_fields:
- ai_use
- agent_actions
summary_line: 2 quoted statements, read from CommSync's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Unified Inbox
- SMS
- Email
- Messaging
- Artificial Intelligence
- AI Agents
- MCP
- Webhooks
- Communications
---
