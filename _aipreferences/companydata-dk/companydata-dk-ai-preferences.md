---
api_specs:
- filename: companydata-dk-account-api-openapi.yml
  format: yaml
  label: companydata.dk Account API
  slug: companydata-dk-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-account-api-openapi.yml
- filename: companydata-dk-auditors-api-openapi.yml
  format: yaml
  label: companydata.dk Auditors API
  slug: companydata-dk-auditors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-auditors-api-openapi.yml
- filename: companydata-dk-companies-api-openapi.yml
  format: yaml
  label: companydata.dk Companies API
  slug: companydata-dk-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-companies-api-openapi.yml
- filename: companydata-dk-cvrapi-dk-compatibility-api-openapi.yml
  format: yaml
  label: companydata.dk cvrapi.dk compatibility API
  slug: companydata-dk-cvrapi-dk-compatibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-cvrapi-dk-compatibility-api-openapi.yml
- filename: companydata-dk-e-invoicing-api-openapi.yml
  format: yaml
  label: companydata.dk E Invoicing API
  slug: companydata-dk-e-invoicing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-e-invoicing-api-openapi.yml
- filename: companydata-dk-legal-notices-api-openapi.yml
  format: yaml
  label: companydata.dk Legal notices API
  slug: companydata-dk-legal-notices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-legal-notices-api-openapi.yml
- filename: companydata-dk-participants-api-openapi.yml
  format: yaml
  label: companydata.dk Participants API
  slug: companydata-dk-participants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-participants-api-openapi.yml
- filename: companydata-dk-production-units-api-openapi.yml
  format: yaml
  label: companydata.dk Production Units API
  slug: companydata-dk-production-units-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-production-units-api-openapi.yml
- filename: companydata-dk-properties-api-openapi.yml
  format: yaml
  label: companydata.dk Properties API
  slug: companydata-dk-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-properties-api-openapi.yml
- filename: companydata-dk-reference-data-api-openapi.yml
  format: yaml
  label: companydata.dk Reference Data API
  slug: companydata-dk-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-reference-data-api-openapi.yml
- filename: companydata-dk-screening-api-openapi.yml
  format: yaml
  label: companydata.dk Screening API
  slug: companydata-dk-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-screening-api-openapi.yml
- filename: companydata-dk-webhooks-api-openapi.yml
  format: yaml
  label: companydata.dk Webhooks API
  slug: companydata-dk-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-webhooks-api-openapi.yml
- filename: companydata-dk-working-lists-api-openapi.yml
  format: yaml
  label: companydata.dk Working Lists API
  slug: companydata-dk-working-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-working-lists-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: conditional
    text: At overbelaste vores systemer med automatiserede forespørgsler ud over din API-kvote
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
    llms_txt_url: https://companydata.dk/llms.txt
    x-probed: https://companydata.dk
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
name: companydata.dk
provenance_date: '2026-11-09'
provider_name: companydata.dk
provider_slug: companydata-dk
slug: companydata-dk-ai-preferences
source_date: '2026-11-09'
source_filename: companydata-dk-ai-preferences.yml
source_heading: AI Preferences
source_page: https://companydata.dk/da/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: companydata.dk\naid: companydata-dk\nurl: https://companydata.dk/da/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: At overbelaste vores systemer med automatiserede forespørgsler ud over din API-kvote\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: null\n  llms_txt_url: https://companydata.dk/llms.txt\n  x-probed:\
  \ https://companydata.dk\n"
source_yaml_url: https://artifacts.apis.io/companydata-dk/ai-preferences/companydata-dk-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from companydata.dk's own page on 2026-11-09.
synthetic: false
tags:
- Company Data
- Business Registry
- CVR
- Denmark
- Credit Scoring
- Financial Statements
- Lead Generation
- MCP
- REST API
---
