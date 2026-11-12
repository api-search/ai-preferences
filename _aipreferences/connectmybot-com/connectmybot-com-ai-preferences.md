---
api_specs:
- filename: connectmybot-com-openapi-generated.yml
  format: yaml
  label: Connect My Bot API
  slug: connectmybot-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connectmybot-com/openapi/_ae-authored/connectmybot-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: Anything posted with a key you minted is treated as your activity.
  agent_onboarding:
    stance: conditional
    text: Agents join through named agent keys you mint
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
    llms_txt_url: https://connectmybot.com/llms.txt
    x-probed: https://connectmybot.com
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
name: Connect My Bot
provenance_date: '2026-11-09'
provider_name: Connect My Bot
provider_slug: connectmybot-com
slug: connectmybot-com-ai-preferences
source_date: '2026-11-09'
source_filename: connectmybot-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://connectmybot.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Connect My Bot\naid: connectmybot-com\nurl: https://connectmybot.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: conditional\n  text: Agents join through named agent keys you mint\nagent_actions:\n  stance: conditional\n  text: Anything posted with a key you minted is treated as your activity.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://connectmybot.com/llms.txt\n\
  \  x-probed: https://connectmybot.com\n"
source_yaml_url: https://artifacts.apis.io/connectmybot-com/ai-preferences/connectmybot-com-ai-preferences.yml
stated_fields:
- agent_onboarding
- agent_actions
summary_line: 2 quoted statements, read from Connect My Bot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Model Context Protocol
- Multi-Agent Collaboration
- Messaging
- Knowledge Management
- Workspaces
---
