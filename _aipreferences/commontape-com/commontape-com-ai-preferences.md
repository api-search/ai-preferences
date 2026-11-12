---
api_specs:
- filename: commontape-com-book-api-openapi.yml
  format: yaml
  label: CommonTape Book API
  slug: commontape-com-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-book-api-openapi.yml
- filename: commontape-com-cancel-api-openapi.yml
  format: yaml
  label: CommonTape Cancel API
  slug: commontape-com-cancel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-cancel-api-openapi.yml
- filename: commontape-com-discover-api-openapi.yml
  format: yaml
  label: CommonTape Discover API
  slug: commontape-com-discover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-discover-api-openapi.yml
- filename: commontape-com-hold-api-openapi.yml
  format: yaml
  label: CommonTape Hold API
  slug: commontape-com-hold-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-hold-api-openapi.yml
- filename: commontape-com-keys-api-openapi.yml
  format: yaml
  label: CommonTape Keys API
  slug: commontape-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-keys-api-openapi.yml
- filename: commontape-com-modify-api-openapi.yml
  format: yaml
  label: CommonTape Modify API
  slug: commontape-com-modify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-modify-api-openapi.yml
- filename: commontape-com-quote-api-openapi.yml
  format: yaml
  label: CommonTape Quote API
  slug: commontape-com-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-quote-api-openapi.yml
- filename: commontape-com-search-api-openapi.yml
  format: yaml
  label: CommonTape Search API
  slug: commontape-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-search-api-openapi.yml
- filename: commontape-com-status-api-openapi.yml
  format: yaml
  label: CommonTape Status API
  slug: commontape-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-status-api-openapi.yml
- filename: commontape-com-taxonomy-api-openapi.yml
  format: yaml
  label: CommonTape Taxonomy API
  slug: commontape-com-taxonomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-taxonomy-api-openapi.yml
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: The key’s holder is responsible for every call made with it, must act on behalf of a real customer, and must give the business true details for each job.
  agent_onboarding:
    stance: conditional
    text: An agent uses the service with a key issued to it.
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
    llms_txt_url: https://commontape.com/llms.txt
    x-probed: https://commontape.com
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
name: CommonTape
provenance_date: '2026-11-09'
provider_name: CommonTape
provider_slug: commontape-com
slug: commontape-com-ai-preferences
source_date: '2026-11-09'
source_filename: commontape-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://commontape.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CommonTape\naid: commontape-com\nurl: https://commontape.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: conditional\n  text: An agent uses the service with a key issued to it.\nagent_actions:\n  stance: conditional\n  text: The key’s holder is responsible for every call made with it, must act on behalf of a real customer, and\n    must give the business true details for each job.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header:\
  \ false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://commontape.com/llms.txt\n  x-probed: https://commontape.com\n"
source_yaml_url: https://artifacts.apis.io/commontape-com/ai-preferences/commontape-com-ai-preferences.yml
stated_fields:
- agent_onboarding
- agent_actions
summary_line: 2 quoted statements, read from CommonTape's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Booking
- Home Services
- House Cleaning
- MCP
- Marketplace
- Scheduling
---
