---
api_specs:
- filename: collegecalcai-com-chances-api-openapi.yml
  format: yaml
  label: CollegeCalcAI Chances API
  slug: collegecalcai-com-chances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collegecalcai-com/openapi/collegecalcai-com-chances-api-openapi.yml
- filename: collegecalcai-com-colleges-api-openapi.yml
  format: yaml
  label: CollegeCalcAI Colleges API
  slug: collegecalcai-com-colleges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collegecalcai-com/openapi/collegecalcai-com-colleges-api-openapi.yml
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: 'Do not misuse the Service: no scraping, automated bulk access, reverse engineering, probing or disrupting our systems'
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: sending your essay to our AI provider to produce your review
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://collegecalcai.com/llms.txt
    x-probed: https://collegecalcai.com
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
name: CollegeCalcAI
provenance_date: '2026-11-09'
provider_name: CollegeCalcAI
provider_slug: collegecalcai-com
slug: collegecalcai-com-ai-preferences
source_date: '2026-11-09'
source_filename: collegecalcai-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://collegecalcai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CollegeCalcAI\naid: collegecalcai-com\nurl: https://collegecalcai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: sending your essay to our AI provider to produce your review\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: 'Do not misuse the Service: no scraping, automated bulk access, reverse engineering, probing or disrupting\n    our systems'\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals:\
  \ false\n  ai_txt_url: null\n  llms_txt_url: https://collegecalcai.com/llms.txt\n  x-probed: https://collegecalcai.com\n"
source_yaml_url: https://artifacts.apis.io/collegecalcai-com/ai-preferences/collegecalcai-com-ai-preferences.yml
stated_fields:
- ai_use
- agent_actions
summary_line: 2 quoted statements, read from CollegeCalcAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- College Admissions
- Higher Education
- Students
- Calculators
- MCP
- Artificial Intelligence
---
