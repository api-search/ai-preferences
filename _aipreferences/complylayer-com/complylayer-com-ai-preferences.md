---
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Scrape, crawl, or use automated means to extract data from the Service
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: Where the Service uses third-party AI APIs to generate documents or assist risk classification, excerpts of your Customer Data are processed by those providers under terms that prohibit its use for model training
  signals:
    ai_txt_url: https://complylayer.com/ai.txt
    aipref_header: false
    content_signals: true
    llms_txt_url: https://complylayer.com/llms.txt
    x-probed: https://complylayer.com
  train_ai:
    stance: prohibited
    text: We will never use your Customer Data to train AI models or share it with other customers.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: ComplyLayer
provenance_date: '2026-11-09'
provider_name: ComplyLayer
provider_slug: complylayer-com
slug: complylayer-com-ai-preferences
source_date: '2026-11-09'
source_filename: complylayer-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://complylayer.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: ComplyLayer\naid: complylayer-com\nurl: https://complylayer.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We will never use your Customer Data to train AI models or share it with other customers.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: Where the Service uses third-party AI APIs to generate documents or assist risk classification, excerpts\n    of your Customer Data are processed by those providers under terms that prohibit its use for model training\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance:\
  \ prohibited\n  text: Scrape, crawl, or use automated means to extract data from the Service\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: https://complylayer.com/ai.txt\n  llms_txt_url: https://complylayer.com/llms.txt\n  x-probed: https://complylayer.com\n"
source_yaml_url: https://artifacts.apis.io/complylayer-com/ai-preferences/complylayer-com-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from ComplyLayer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Governance
- Compliance
- EU AI Act
- Risk Management
- GDPR
- MCP
- Privacy
---
