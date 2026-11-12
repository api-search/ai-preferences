---
api_specs:
- filename: contracko-com-authentication-api-openapi.yml
  format: yaml
  label: Contracko Authentication API
  slug: contracko-com-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contracko-com/openapi/contracko-com-authentication-api-openapi.yml
- filename: contracko-com-contract-types-api-openapi.yml
  format: yaml
  label: Contracko Contract Types API
  slug: contracko-com-contract-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contracko-com/openapi/contracko-com-contract-types-api-openapi.yml
- filename: contracko-com-parsing-api-api-openapi.yml
  format: yaml
  label: Contracko Parsing API
  slug: contracko-com-parsing-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contracko-com/openapi/contracko-com-parsing-api-api-openapi.yml
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
    content_signals: true
    llms_txt_url: https://contracko.com/llms.txt
    x-probed: https://contracko.com
  train_ai:
    stance: prohibited
    text: Provider will not use Customer Content, Customer's Confidential Information or Usage Data to train or fine-tune any AI model, including in aggregated or de-identified form.
  train_genai:
    stance: prohibited
    text: Provider will not use Customer Content, Customer's Confidential Information or Usage Data to train or fine-tune any AI model, including in aggregated or de-identified form.
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Contracko
provenance_date: '2026-11-09'
provider_name: Contracko
provider_slug: contracko-com
slug: contracko-com-ai-preferences
source_date: '2026-11-09'
source_filename: contracko-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://contracko.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Contracko\naid: contracko-com\nurl: https://contracko.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: Provider will not use Customer Content, Customer's Confidential Information or Usage Data to train or fine-tune\n    any AI model, including in aggregated or de-identified form.\ntrain_genai:\n  stance: prohibited\n  text: Provider will not use Customer Content, Customer's Confidential Information or Usage Data to train or fine-tune\n    any AI model, including in aggregated or de-identified form.\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n\
  \  stance: unstated\n  text: null\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: null\n  llms_txt_url: https://contracko.com/llms.txt\n  x-probed: https://contracko.com\n"
source_yaml_url: https://artifacts.apis.io/contracko-com/ai-preferences/contracko-com-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
summary_line: 2 quoted statements, read from Contracko's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Contract Management
- Legal Technology
- Artificial Intelligence
- Document Parsing
- Data Extraction
- E-Signature
- MCP
---
