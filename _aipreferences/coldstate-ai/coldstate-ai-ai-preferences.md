---
api_specs:
- filename: coldstate-ai-auth-api-openapi.yml
  format: yaml
  label: ColdState Auth API
  slug: coldstate-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-auth-api-openapi.yml
- filename: coldstate-ai-billing-api-openapi.yml
  format: yaml
  label: ColdState Billing API
  slug: coldstate-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-billing-api-openapi.yml
- filename: coldstate-ai-indexes-api-openapi.yml
  format: yaml
  label: ColdState Indexes API
  slug: coldstate-ai-indexes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-indexes-api-openapi.yml
- filename: coldstate-ai-knowledge-api-openapi.yml
  format: yaml
  label: ColdState Knowledge API
  slug: coldstate-ai-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-knowledge-api-openapi.yml
- filename: coldstate-ai-mcp-api-openapi.yml
  format: yaml
  label: ColdState MCP API
  slug: coldstate-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-mcp-api-openapi.yml
- filename: coldstate-ai-meta-api-openapi.yml
  format: yaml
  label: ColdState Meta API
  slug: coldstate-ai-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-meta-api-openapi.yml
- filename: coldstate-ai-search-api-openapi.yml
  format: yaml
  label: ColdState Search API
  slug: coldstate-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-search-api-openapi.yml
- filename: coldstate-ai-usage-api-openapi.yml
  format: yaml
  label: ColdState Usage API
  slug: coldstate-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: unstated
    text: null
  agent_onboarding:
    stance: prohibited
    text: Use automated systems to create accounts or generate fraudulent usage
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
    llms_txt_url: null
    x-probed: https://coldstate.ai
  train_ai:
    stance: prohibited
    text: We do not use your content to train models or improve algorithms.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: ColdState
provenance_date: '2026-11-09'
provider_name: ColdState
provider_slug: coldstate-ai
slug: coldstate-ai-ai-preferences
source_date: '2026-11-09'
source_filename: coldstate-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://services.coldstate.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: ColdState\naid: coldstate-ai\nurl: https://services.coldstate.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not use your content to train models or improve algorithms.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: prohibited\n  text: Use automated systems to create accounts or generate fraudulent usage\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url:\
  \ null\n  x-probed: https://coldstate.ai\n"
source_yaml_url: https://artifacts.apis.io/coldstate-ai/ai-preferences/coldstate-ai-ai-preferences.yml
stated_fields:
- train_ai
- agent_onboarding
summary_line: 2 quoted statements, read from ColdState's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Knowledge Base
- Search
- Deterministic Retrieval
- MCP
- AI Agents
- Citations
---
