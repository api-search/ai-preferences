---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: Please be reasonable about how often you ask.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: If an assistant answers a question using this data, name where it came from.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://www.courts.tennis/llms.txt
    x-probed: https://www.courts.tennis
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
name: Courts.tennis
provenance_date: '2026-11-09'
provider_name: Courts.tennis
provider_slug: courts-tennis
slug: courts-tennis-ai-preferences
source_date: '2026-11-09'
source_filename: courts-tennis-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.courts.tennis/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Courts.tennis\naid: courts-tennis\nurl: https://www.courts.tennis/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: If an assistant answers a question using this data, name where it came from.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: Please be reasonable about how often you ask.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://www.courts.tennis/llms.txt\n\
  \  x-probed: https://www.courts.tennis\n"
source_yaml_url: https://artifacts.apis.io/courts-tennis/ai-preferences/courts-tennis-ai-preferences.yml
stated_fields:
- ai_use
- agent_actions
summary_line: 2 quoted statements, read from Courts.tennis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Tennis
- Sports
- Sports Facilities
- Directories
- Open Data
- Model Context Protocol
- Travel
---
