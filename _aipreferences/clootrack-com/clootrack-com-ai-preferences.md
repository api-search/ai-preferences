---
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: unstated
    text: null
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
    llms_txt_url: https://www.clootrack.com/llms.txt
    x-probed: https://www.clootrack.com
  train_ai:
    stance: conditional
    text: Clootrack may collect, analyze, and use aggregated or anonymized data based on Customer Data and your usage of the Services for the purpose of analytics, improvements, machine learning, benchmarking, and product development
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Clootrack
provenance_date: '2026-11-09'
provider_name: Clootrack
provider_slug: clootrack-com
slug: clootrack-com-ai-preferences
source_date: '2026-11-09'
source_filename: clootrack-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.clootrack.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Clootrack\naid: clootrack-com\nurl: https://www.clootrack.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: Clootrack may collect, analyze, and use aggregated or anonymized data based on Customer Data and your usage\n    of the Services for the purpose of analytics, improvements, machine learning, benchmarking, and product development\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n \
  \ text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://www.clootrack.com/llms.txt\n  x-probed: https://www.clootrack.com\n"
source_yaml_url: https://artifacts.apis.io/clootrack-com/ai-preferences/clootrack-com-ai-preferences.yml
stated_fields:
- train_ai
summary_line: 1 quoted statement, read from Clootrack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Experience
- Voice of the Customer
- Customer Feedback Analytics
- Artificial Intelligence
- Sentiment Analysis
- Model Context Protocol
---
