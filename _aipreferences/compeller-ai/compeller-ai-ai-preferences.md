---
api_specs:
- filename: compeller-ai-auth-api-openapi.yml
  format: yaml
  label: Compeller Auth API
  slug: compeller-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-auth-api-openapi.yml
- filename: compeller-ai-compels-api-openapi.yml
  format: yaml
  label: Compeller Compels API
  slug: compeller-ai-compels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-compels-api-openapi.yml
- filename: compeller-ai-discovery-api-openapi.yml
  format: yaml
  label: Compeller Discovery API
  slug: compeller-ai-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-discovery-api-openapi.yml
- filename: compeller-ai-lighting-api-openapi.yml
  format: yaml
  label: Compeller Lighting API
  slug: compeller-ai-lighting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-lighting-api-openapi.yml
- filename: compeller-ai-media-api-openapi.yml
  format: yaml
  label: Compeller Media API
  slug: compeller-ai-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-media-api-openapi.yml
- filename: compeller-ai-music-api-openapi.yml
  format: yaml
  label: Compeller Music API
  slug: compeller-ai-music-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-music-api-openapi.yml
- filename: compeller-ai-renderings-api-openapi.yml
  format: yaml
  label: Compeller Renderings API
  slug: compeller-ai-renderings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-renderings-api-openapi.yml
- filename: compeller-ai-webhooks-api-openapi.yml
  format: yaml
  label: Compeller Webhooks API
  slug: compeller-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: you shall not use any manual or automated software, devices or other processes (including but not limited to spiders, robots, scrapers, crawlers, avatars, data mining tools or the like) to
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: The Company Properties utilize artificial intelligence to process user inputs to the Company Properties
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://compeller.ai/llms.txt
    x-probed: https://compeller.ai
  train_ai:
    stance: allowed
    text: Inputs and Outputs may be used by the Company to train, enhance, evolve and improve its AI models, algorithms and related technology, products and services
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Compeller
provenance_date: '2026-11-09'
provider_name: Compeller
provider_slug: compeller-ai
slug: compeller-ai-ai-preferences
source_date: '2026-11-09'
source_filename: compeller-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://compeller.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Compeller\naid: compeller-ai\nurl: https://compeller.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: allowed\n  text: Inputs and Outputs may be used by the Company to train, enhance, evolve and improve its AI models, algorithms\n    and related technology, products and services\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: The Company Properties utilize artificial intelligence to process user inputs to the Company Properties\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: you shall not use any manual or automated\
  \ software, devices or other processes (including but not limited\n    to spiders, robots, scrapers, crawlers, avatars, data mining tools or the like) to\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://compeller.ai/llms.txt\n  x-probed: https://compeller.ai\n"
source_yaml_url: https://artifacts.apis.io/compeller-ai/ai-preferences/compeller-ai-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from Compeller's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI
- Music
- Video Generation
- Live Performance
- Audio Reactive Visuals
- MCP
---
