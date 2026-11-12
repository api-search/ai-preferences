---
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: conditional
    text: They are offered on a fair-use basis — please do not send abusive request volumes or use them in any way that degrades the service for others.
  agent_onboarding:
    stance: allowed
    text: You do not need an account, an API key, or a subscription.
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: to look up and reference recipes within your own applications and conversations
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: true
    llms_txt_url: https://cocktail.glass/llms.txt
    x-probed: https://cocktail.glass
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
name: Cocktail Glass
provenance_date: '2026-11-09'
provider_name: Cocktail Glass
provider_slug: cocktail-glass
slug: cocktail-glass-ai-preferences
source_date: '2026-11-09'
source_filename: cocktail-glass-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cocktail.glass/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Cocktail Glass\naid: cocktail-glass\nurl: https://cocktail.glass/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: to look up and reference recipes within your own applications and conversations\nagent_onboarding:\n  stance: allowed\n  text: You do not need an account, an API key, or a subscription.\nagent_actions:\n  stance: conditional\n  text: They are offered on a fair-use basis — please do not send abusive request volumes or use them in any way\n    that degrades the service\
  \ for others.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: null\n  llms_txt_url: https://cocktail.glass/llms.txt\n  x-probed: https://cocktail.glass\n"
source_yaml_url: https://artifacts.apis.io/cocktail-glass/ai-preferences/cocktail-glass-ai-preferences.yml
stated_fields:
- ai_use
- agent_onboarding
- agent_actions
summary_line: 3 quoted statements, read from Cocktail Glass's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cocktails
- Recipes
- Food and Drink
- MCP
- AI Agents
- Open Data
---
