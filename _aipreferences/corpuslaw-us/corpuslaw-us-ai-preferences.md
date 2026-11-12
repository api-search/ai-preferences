---
api_specs:
- filename: corpuslaw-us-account-api-openapi.yml
  format: yaml
  label: Corpus Account API
  slug: corpuslaw-us-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-account-api-openapi.yml
- filename: corpuslaw-us-browse-api-openapi.yml
  format: yaml
  label: Corpus Browse API
  slug: corpuslaw-us-browse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-browse-api-openapi.yml
- filename: corpuslaw-us-coverage-api-openapi.yml
  format: yaml
  label: Corpus Coverage API
  slug: corpuslaw-us-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-coverage-api-openapi.yml
- filename: corpuslaw-us-formation-api-openapi.yml
  format: yaml
  label: Corpus Formation API
  slug: corpuslaw-us-formation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-formation-api-openapi.yml
- filename: corpuslaw-us-general-api-openapi.yml
  format: yaml
  label: Corpus General API
  slug: corpuslaw-us-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-general-api-openapi.yml
- filename: corpuslaw-us-gis-api-openapi.yml
  format: yaml
  label: Corpus GIS API
  slug: corpuslaw-us-gis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-gis-api-openapi.yml
- filename: corpuslaw-us-search-api-openapi.yml
  format: yaml
  label: Corpus Search API
  slug: corpuslaw-us-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: allowed
    text: 'For AI agents: read the machine-readable documentation index at /llms.txt or the single-file full reference at /llms-full.txt .'
  agent_onboarding:
    stance: allowed
    text: or, if an AI agent placed your order, within 24 hours of your email confirmation
  agent_purchases:
    stance: allowed
    text: Public proof listing (optional). If you tick the box on the confirmation page, Corpus lists your company on corpuslaw.us as an order an AI agent placed.
  ai_use:
    stance: unstated
    text: null
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://corpuslaw.us/llms.txt
    x-probed: https://corpuslaw.us
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
name: Corpus
provenance_date: '2026-11-09'
provider_name: Corpus
provider_slug: corpuslaw-us
slug: corpuslaw-us-ai-preferences
source_date: '2026-11-09'
source_filename: corpuslaw-us-ai-preferences.yml
source_heading: AI Preferences
source_page: https://corpuslaw.us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Corpus\naid: corpuslaw-us\nurl: https://corpuslaw.us/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: allowed\n  text: or, if an AI agent placed your order, within 24 hours of your email confirmation\nagent_actions:\n  stance: allowed\n  text: 'For AI agents: read the machine-readable documentation index at /llms.txt or the single-file full reference\n    at /llms-full.txt .'\nagent_purchases:\n  stance: allowed\n  text: Public proof listing (optional). If you\
  \ tick the box on the confirmation page, Corpus lists your company\n    on corpuslaw.us as an order an AI agent placed.\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://corpuslaw.us/llms.txt\n  x-probed: https://corpuslaw.us\n"
source_yaml_url: https://artifacts.apis.io/corpuslaw-us/ai-preferences/corpuslaw-us-ai-preferences.yml
stated_fields:
- agent_onboarding
- agent_actions
- agent_purchases
summary_line: 3 quoted statements, read from Corpus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Law
- Business Formation
- LLC
- Compliance
- MCP
- AI Agents
---
