---
api_specs:
- filename: cloudovna-eu-catalog-api-openapi.yml
  format: yaml
  label: Cloudovňa Catalog API
  slug: cloudovna-eu-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-catalog-api-openapi.yml
- filename: cloudovna-eu-health-api-openapi.yml
  format: yaml
  label: Cloudovňa Health API
  slug: cloudovna-eu-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-health-api-openapi.yml
- filename: cloudovna-eu-hooks-api-openapi.yml
  format: yaml
  label: Cloudovňa Hooks API
  slug: cloudovna-eu-hooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-hooks-api-openapi.yml
- filename: cloudovna-eu-images-api-openapi.yml
  format: yaml
  label: Cloudovňa Images API
  slug: cloudovna-eu-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-images-api-openapi.yml
- filename: cloudovna-eu-integrations-api-openapi.yml
  format: yaml
  label: Cloudovňa Integrations API
  slug: cloudovna-eu-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-integrations-api-openapi.yml
- filename: cloudovna-eu-invitations-api-openapi.yml
  format: yaml
  label: Cloudovňa Invitations API
  slug: cloudovna-eu-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-invitations-api-openapi.yml
- filename: cloudovna-eu-invoices-api-openapi.yml
  format: yaml
  label: Cloudovňa Invoices API
  slug: cloudovna-eu-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-invoices-api-openapi.yml
- filename: cloudovna-eu-mcp-api-openapi.yml
  format: yaml
  label: Cloudovňa MCP API
  slug: cloudovna-eu-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-mcp-api-openapi.yml
- filename: cloudovna-eu-oauth-api-openapi.yml
  format: yaml
  label: Cloudovňa OAuth API
  slug: cloudovna-eu-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-oauth-api-openapi.yml
- filename: cloudovna-eu-organizations-api-openapi.yml
  format: yaml
  label: Cloudovňa Organizations API
  slug: cloudovna-eu-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-organizations-api-openapi.yml
- filename: cloudovna-eu-payments-api-openapi.yml
  format: yaml
  label: Cloudovňa Payments API
  slug: cloudovna-eu-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-payments-api-openapi.yml
- filename: cloudovna-eu-pool-api-openapi.yml
  format: yaml
  label: Cloudovňa Pool API
  slug: cloudovna-eu-pool-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-pool-api-openapi.yml
- filename: cloudovna-eu-public-api-openapi.yml
  format: yaml
  label: Cloudovňa Public API
  slug: cloudovna-eu-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-public-api-openapi.yml
- filename: cloudovna-eu-services-api-openapi.yml
  format: yaml
  label: Cloudovňa Services API
  slug: cloudovna-eu-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-services-api-openapi.yml
- filename: cloudovna-eu-stacks-api-openapi.yml
  format: yaml
  label: Cloudovňa Stacks API
  slug: cloudovna-eu-stacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-stacks-api-openapi.yml
- filename: cloudovna-eu-well-known-api-openapi.yml
  format: yaml
  label: Cloudovňa .well Known API
  slug: cloudovna-eu-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-well-known-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: conditional
    text: You are responsible for everything done in your account, including actions taken through the API or by an AI agent connected to the MCP server with your token.
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
    llms_txt_url: https://cloudovna.eu/llms.txt
    x-probed: https://cloudovna.eu
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
name: Cloudovňa
provenance_date: '2026-11-09'
provider_name: Cloudovňa
provider_slug: cloudovna-eu
slug: cloudovna-eu-ai-preferences
source_date: '2026-11-09'
source_filename: cloudovna-eu-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cloudovna.eu/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Cloudovňa\naid: cloudovna-eu\nurl: https://cloudovna.eu/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: You are responsible for everything done in your account, including actions taken through the API or by an\n    AI agent connected to the MCP server with your token.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url:\
  \ null\n  llms_txt_url: https://cloudovna.eu/llms.txt\n  x-probed: https://cloudovna.eu\n"
source_yaml_url: https://artifacts.apis.io/cloudovna-eu/ai-preferences/cloudovna-eu-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from Cloudovňa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Hosting
- Containers
- Docker
- Databases
- PostgreSQL
- SQL Server
- European Union
- MCP
---
