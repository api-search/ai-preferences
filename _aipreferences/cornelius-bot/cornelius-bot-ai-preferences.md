---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: resell, sublicense or offer the service to third parties, or scrape it
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: prohibited
    text: Your agent drafts; it does not send, publish or purchase on its own.
  ai_use:
    stance: unstated
    text: null
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: null
    x-probed: https://cornelius.bot
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
name: Cornelius
provenance_date: '2026-11-09'
provider_name: Cornelius
provider_slug: cornelius-bot
slug: cornelius-bot-ai-preferences
source_date: '2026-11-09'
source_filename: cornelius-bot-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cornelius.bot/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Cornelius\naid: cornelius-bot\nurl: https://cornelius.bot/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: resell, sublicense or offer the service to third parties, or scrape it\nagent_purchases:\n  stance: prohibited\n  text: Your agent drafts; it does not send, publish or purchase on its own.\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url:\
  \ null\n  x-probed: https://cornelius.bot\n"
source_yaml_url: https://artifacts.apis.io/cornelius-bot/ai-preferences/cornelius-bot-ai-preferences.yml
stated_fields:
- agent_actions
- agent_purchases
summary_line: 2 quoted statements, read from Cornelius's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Personal Assistant
- Model Context Protocol
- Knowledge Graph
- Productivity
---
