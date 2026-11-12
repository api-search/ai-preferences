---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Extract data or content in an automated way (scraping).
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
    llms_txt_url: https://cocuyo.ai/llms.txt
    x-probed: https://cocuyo.ai
  train_ai:
    stance: prohibited
    text: Use the results to develop, train, or improve artificial intelligence models that compete with the providers that make the Estudio possible, nor as part of training data sets.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Cocuyo
provenance_date: '2026-11-09'
provider_name: Cocuyo
provider_slug: cocuyo-ai
slug: cocuyo-ai-ai-preferences
source_date: '2026-11-09'
source_filename: cocuyo-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cocuyo.ai/en/terminos.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Cocuyo\naid: cocuyo-ai\nurl: https://cocuyo.ai/en/terminos.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: Use the results to develop, train, or improve artificial intelligence models that compete with the providers\n    that make the Estudio possible, nor as part of training data sets.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: Extract data or content in an automated way (scraping).\nagent_purchases:\n  stance: unstated\n  text: null\n\
  signals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://cocuyo.ai/llms.txt\n  x-probed: https://cocuyo.ai\n"
source_yaml_url: https://artifacts.apis.io/cocuyo-ai/ai-preferences/cocuyo-ai-ai-preferences.yml
stated_fields:
- train_ai
- agent_actions
summary_line: 2 quoted statements, read from Cocuyo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Image Generation
- Video Generation
- Text To Speech
- MCP
- Creative Tools
---
