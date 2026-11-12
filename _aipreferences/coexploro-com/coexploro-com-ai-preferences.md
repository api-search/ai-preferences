---
claim_count: 2
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
    llms_txt_url: https://coexploro.com/llms.txt
    x-probed: https://coexploro.com
  train_ai:
    stance: conditional
    text: Any future product-improvement training requires explicit, granular user opt-in via account settings.
  train_genai:
    stance: prohibited
    text: User inputs, submitted URLs, captured screenshots, AI prompts, and AI-generated reports are NOT used to train Anthropic, Google, OpenAI, or any other third-party foundational AI model.
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: coExploro
provenance_date: '2026-11-09'
provider_name: coExploro
provider_slug: coexploro-com
slug: coexploro-com-ai-preferences
source_date: '2026-11-09'
source_filename: coexploro-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://coexploro.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: coExploro\naid: coexploro-com\nurl: https://coexploro.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: Any future product-improvement training requires explicit, granular user opt-in via account settings.\ntrain_genai:\n  stance: prohibited\n  text: User inputs, submitted URLs, captured screenshots, AI prompts, and AI-generated reports are NOT used to\n    train Anthropic, Google, OpenAI, or any other third-party foundational AI model.\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: unstated\n  text: null\n\
  agent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://coexploro.com/llms.txt\n  x-probed: https://coexploro.com\n"
source_yaml_url: https://artifacts.apis.io/coexploro-com/ai-preferences/coexploro-com-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
summary_line: 2 quoted statements, read from coExploro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Competitor Analysis
- UX Audit
- Product Teardown
- Artificial Intelligence
- MCP
- SaaS
---
