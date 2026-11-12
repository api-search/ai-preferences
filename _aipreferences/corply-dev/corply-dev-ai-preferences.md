---
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Do not interfere with, scrape, copy, resell, benchmark for competitive purposes, reverse engineer, overload, probe, scan, bypass, or disrupt the Services except as permitted by law or our written permission.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: AI providers may process the information needed to extract facts, check documents, or deliver other requested features under business terms that prohibit model training on customer content.
  signals:
    ai_txt_url: https://corply.dev/ai.txt
    aipref_header: false
    content_signals: false
    llms_txt_url: https://corply.dev/llms.txt
    x-probed: https://corply.dev
  train_ai:
    stance: prohibited
    text: We do not sell your confidential company records or use them to train AI or machine-learning models.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Corply
provenance_date: '2026-11-09'
provider_name: Corply
provider_slug: corply-dev
slug: corply-dev-ai-preferences
source_date: '2026-11-09'
source_filename: corply-dev-ai-preferences.yml
source_heading: AI Preferences
source_page: https://corply.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Corply\naid: corply-dev\nurl: https://corply.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not sell your confidential company records or use them to train AI or machine-learning models.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: AI providers may process the information needed to extract facts, check documents, or deliver other requested\n    features under business terms that prohibit model training on customer content.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: Do not\
  \ interfere with, scrape, copy, resell, benchmark for competitive purposes, reverse engineer, overload,\n    probe, scan, bypass, or disrupt the Services except as permitted by law or our written permission.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: https://corply.dev/ai.txt\n  llms_txt_url: https://corply.dev/llms.txt\n  x-probed: https://corply.dev\n"
source_yaml_url: https://artifacts.apis.io/corply-dev/ai-preferences/corply-dev-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from Corply's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Formation
- Incorporation
- Delaware C-Corp
- Legal Tech
- AI Agents
- MCP
- Startups
---
