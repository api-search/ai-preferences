---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Reverse engineer, decompile, or scrape the apps.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: Cleo Plan uses AI to estimate the calories and protein of foods you log.
  signals:
    ai_txt_url: null
    aipref_header: null
    content_signals: null
    llms_txt_url: null
    x-probed: https://cleofamily.app
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
name: Cleo
provenance_date: '2026-11-09'
provider_name: Cleo
provider_slug: cleofamily-app
slug: cleofamily-app-ai-preferences
source_date: '2026-11-09'
source_filename: cleofamily-app-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.cleofamily.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Cleo\naid: cleofamily-app\nurl: https://www.cleofamily.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: Cleo Plan uses AI to estimate the calories and protein of foods you log.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: Reverse engineer, decompile, or scrape the apps.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: null\n  content_signals: null\n  ai_txt_url: null\n  llms_txt_url: null\n  x-probed: https://cleofamily.app\n"
source_yaml_url: https://artifacts.apis.io/cleofamily-app/ai-preferences/cleofamily-app-ai-preferences.yml
stated_fields:
- ai_use
- agent_actions
summary_line: 2 quoted statements, read from Cleo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Family
- Parenting
- Baby Tracking
- Meal Planning
- MCP
- AI Assistants
- Productivity
---
