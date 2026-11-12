---
api_specs:
- filename: computefirst-net-account-api-openapi.yml
  format: yaml
  label: ComputeFirst Account API
  slug: computefirst-net-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-account-api-openapi.yml
- filename: computefirst-net-discovery-api-openapi.yml
  format: yaml
  label: ComputeFirst Discovery API
  slug: computefirst-net-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-discovery-api-openapi.yml
- filename: computefirst-net-execution-api-openapi.yml
  format: yaml
  label: ComputeFirst Execution API
  slug: computefirst-net-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-execution-api-openapi.yml
- filename: computefirst-net-feedback-api-openapi.yml
  format: yaml
  label: ComputeFirst Feedback API
  slug: computefirst-net-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-feedback-api-openapi.yml
- filename: computefirst-net-mcp-api-openapi.yml
  format: yaml
  label: ComputeFirst MCP API
  slug: computefirst-net-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-mcp-api-openapi.yml
- filename: computefirst-net-newsletter-api-openapi.yml
  format: yaml
  label: ComputeFirst Newsletter API
  slug: computefirst-net-newsletter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-newsletter-api-openapi.yml
- filename: computefirst-net-savings-api-openapi.yml
  format: yaml
  label: ComputeFirst Savings API
  slug: computefirst-net-savings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-savings-api-openapi.yml
- filename: computefirst-net-service-api-openapi.yml
  format: yaml
  label: ComputeFirst Service API
  slug: computefirst-net-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-service-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: conditional
    text: Anything that software does with ComputeFirst on your behalf counts as your own use. These terms bind you, and you are responsible for its actions
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
    llms_txt_url: https://computefirst.net/llms.txt
    x-probed: https://computefirst.net
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
name: ComputeFirst
provenance_date: '2026-11-09'
provider_name: ComputeFirst
provider_slug: computefirst-net
slug: computefirst-net-ai-preferences
source_date: '2026-11-09'
source_filename: computefirst-net-ai-preferences.yml
source_heading: AI Preferences
source_page: https://computefirst.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: ComputeFirst\naid: computefirst-net\nurl: https://computefirst.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: Anything that software does with ComputeFirst on your behalf counts as your own use. These terms bind you,\n    and you are responsible for its actions\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url:\
  \ null\n  llms_txt_url: https://computefirst.net/llms.txt\n  x-probed: https://computefirst.net\n"
source_yaml_url: https://artifacts.apis.io/computefirst-net/ai-preferences/computefirst-net-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from ComputeFirst's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- MCP
- Developer Tools
- Data Transformation
- CSV
- JSON
- Deterministic Tools
---
