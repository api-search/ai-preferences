---
api_specs:
- filename: euroref-dev-alerts-api-openapi.yml
  format: yaml
  label: Euroref Alerts API
  slug: euroref-dev-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-alerts-api-openapi.yml
- filename: euroref-dev-answers-api-openapi.yml
  format: yaml
  label: Euroref Answers API
  slug: euroref-dev-answers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-answers-api-openapi.yml
- filename: euroref-dev-certified-api-openapi.yml
  format: yaml
  label: Euroref Certified API
  slug: euroref-dev-certified-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-certified-api-openapi.yml
- filename: euroref-dev-discovery-api-openapi.yml
  format: yaml
  label: Euroref Discovery API
  slug: euroref-dev-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-discovery-api-openapi.yml
- filename: euroref-dev-free-api-openapi.yml
  format: yaml
  label: Euroref Free API
  slug: euroref-dev-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-free-api-openapi.yml
- filename: euroref-dev-jobs-api-openapi.yml
  format: yaml
  label: Euroref Jobs API
  slug: euroref-dev-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-jobs-api-openapi.yml
- filename: euroref-dev-keys-api-openapi.yml
  format: yaml
  label: Euroref Keys API
  slug: euroref-dev-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-keys-api-openapi.yml
- filename: euroref-dev-reference-data-api-openapi.yml
  format: yaml
  label: Euroref Reference data API
  slug: euroref-dev-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-reference-data-api-openapi.yml
- filename: euroref-dev-x402-sellers-api-openapi.yml
  format: yaml
  label: Euroref x402 sellers API
  slug: euroref-dev-x402-sellers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-x402-sellers-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: allowed
    text: The same paid tools are also available to AI agents through our MCP server at https://euroref.dev/mcp , at the same prices.
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
    llms_txt_url: https://euroref.dev/llms.txt
    x-probed: https://euroref.dev
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
name: Euroref
provenance_date: '2026-11-09'
provider_name: Euroref
provider_slug: euroref-dev
slug: euroref-dev-ai-preferences
source_date: '2026-11-09'
source_filename: euroref-dev-ai-preferences.yml
source_heading: AI Preferences
source_page: https://euroref.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Euroref\naid: euroref-dev\nurl: https://euroref.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: allowed\n  text: The same paid tools are also available to AI agents through our MCP server at https://euroref.dev/mcp ,\n    at the same prices.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://euroref.dev/llms.txt\n\
  \  x-probed: https://euroref.dev\n"
source_yaml_url: https://artifacts.apis.io/euroref-dev/ai-preferences/euroref-dev-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from Euroref's own page on 2026-11-09.
synthetic: false
tags:
- Reference Data
- Government
- Europe
- API
- Open Data
---
