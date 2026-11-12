---
api_specs:
- filename: corporary-com-change-api-openapi.yml
  format: yaml
  label: corporary Change API
  slug: corporary-com-change-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corporary-com/openapi/corporary-com-change-api-openapi.yml
- filename: corporary-com-company-api-openapi.yml
  format: yaml
  label: corporary Company API
  slug: corporary-com-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corporary-com/openapi/corporary-com-company-api-openapi.yml
- filename: corporary-com-search-api-openapi.yml
  format: yaml
  label: corporary Search API
  slug: corporary-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corporary-com/openapi/corporary-com-search-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: L’extraction systématique du site par des robots, au delà de ce qu’autorise le fichier robots.txt, est interdite
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
    llms_txt_url: https://corporary.com/llms.txt
    x-probed: https://corporary.com
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
name: corporary
provenance_date: '2026-11-09'
provider_name: corporary
provider_slug: corporary-com
slug: corporary-com-ai-preferences
source_date: '2026-11-09'
source_filename: corporary-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://corporary.com/fr/conditions-utilisation
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: corporary\naid: corporary-com\nurl: https://corporary.com/fr/conditions-utilisation\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: L’extraction systématique du site par des robots, au delà de ce qu’autorise le fichier robots.txt, est interdite\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://corporary.com/llms.txt\n\
  \  x-probed: https://corporary.com\n"
source_yaml_url: https://artifacts.apis.io/corporary-com/ai-preferences/corporary-com-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from corporary's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Data
- Business Registry
- France
- Financial Data
- Legal Announcements
- MCP
- Open Data
---
