---
api_specs:
- filename: eudr-dev-a2a-api-openapi.yml
  format: yaml
  label: eudr.dev A2a API
  slug: eudr-dev-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-a2a-api-openapi.yml
- filename: eudr-dev-agent-api-openapi.yml
  format: yaml
  label: eudr.dev Agent API
  slug: eudr-dev-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-agent-api-openapi.yml
- filename: eudr-dev-discovery-api-openapi.yml
  format: yaml
  label: eudr.dev Discovery API
  slug: eudr-dev-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-discovery-api-openapi.yml
- filename: eudr-dev-engineer-api-openapi.yml
  format: yaml
  label: eudr.dev Engineer API
  slug: eudr-dev-engineer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-engineer-api-openapi.yml
- filename: eudr-dev-ops-api-openapi.yml
  format: yaml
  label: eudr.dev Ops API
  slug: eudr-dev-ops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-ops-api-openapi.yml
- filename: eudr-dev-public-api-openapi.yml
  format: yaml
  label: eudr.dev Public API
  slug: eudr-dev-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-public-api-openapi.yml
- filename: eudr-dev-reference-api-openapi.yml
  format: yaml
  label: eudr.dev Reference API
  slug: eudr-dev-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-reference-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: conditional
    text: automated callers must respect the published rate limits (5 magic links per email per hour, 30 per IP per hour; per-org API quotas as documented in the dashboard) and the Retry-After headers the service emits.
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
    llms_txt_url: https://eudr.dev/llms.txt
    x-probed: https://eudr.dev
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
name: eudr.dev
provenance_date: '2026-11-09'
provider_name: eudr.dev
provider_slug: eudr-dev
slug: eudr-dev-ai-preferences
source_date: '2026-11-09'
source_filename: eudr-dev-ai-preferences.yml
source_heading: AI Preferences
source_page: https://eudr.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: eudr.dev\naid: eudr-dev\nurl: https://eudr.dev/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: automated callers must respect the published rate limits (5 magic links per email per hour, 30 per IP per\n    hour; per-org API quotas as documented in the dashboard) and the Retry-After headers the service emits.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header:\
  \ false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://eudr.dev/llms.txt\n  x-probed: https://eudr.dev\n"
source_yaml_url: https://artifacts.apis.io/eudr-dev/ai-preferences/eudr-dev-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from eudr.dev's own page on 2026-11-09.
synthetic: false
tags:
- EU Deforestation
- Compliance
- Agriculture
- AI
- Environmental
---
