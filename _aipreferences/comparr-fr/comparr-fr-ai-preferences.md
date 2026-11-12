---
api_specs:
- filename: comparr-fr-comparatifs-api-openapi.yml
  format: yaml
  label: Comparr Comparatifs API
  slug: comparr-fr-comparatifs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-comparatifs-api-openapi.yml
- filename: comparr-fr-deals-api-openapi.yml
  format: yaml
  label: Comparr Deals API
  slug: comparr-fr-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-deals-api-openapi.yml
- filename: comparr-fr-discovery-api-openapi.yml
  format: yaml
  label: Comparr Discovery API
  slug: comparr-fr-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-discovery-api-openapi.yml
- filename: comparr-fr-products-api-openapi.yml
  format: yaml
  label: Comparr Products API
  slug: comparr-fr-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-products-api-openapi.yml
- filename: comparr-fr-searches-api-openapi.yml
  format: yaml
  label: Comparr Searches API
  slug: comparr-fr-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-searches-api-openapi.yml
- filename: comparr-fr-versus-api-openapi.yml
  format: yaml
  label: Comparr Versus API
  slug: comparr-fr-versus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-versus-api-openapi.yml
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: L'API ( /api/v1 ) et le serveur MCP sont ouverts gratuitement aux programmes et aux assistants IA, dans la limite de quotas quotidiens
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: Un assistant ou un programme qui reprend nos classements ou nos prix cite Comparr et renvoie vers la page source
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://www.comparr.fr/llms.txt
    x-probed: https://www.comparr.fr
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
name: Comparr
provenance_date: '2026-11-09'
provider_name: Comparr
provider_slug: comparr-fr
slug: comparr-fr-ai-preferences
source_date: '2026-11-09'
source_filename: comparr-fr-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.comparr.fr/conditions-utilisation
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Comparr\naid: comparr-fr\nurl: https://www.comparr.fr/conditions-utilisation\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: Un assistant ou un programme qui reprend nos classements ou nos prix cite Comparr et renvoie vers la page\n    source\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: L'API ( /api/v1 ) et le serveur MCP sont ouverts gratuitement aux programmes et aux assistants IA, dans\n    la limite de quotas quotidiens\nagent_purchases:\n\
  \  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://www.comparr.fr/llms.txt\n  x-probed: https://www.comparr.fr\n"
source_yaml_url: https://artifacts.apis.io/comparr-fr/ai-preferences/comparr-fr-ai-preferences.yml
stated_fields:
- ai_use
- agent_actions
summary_line: 2 quoted statements, read from Comparr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Price Comparison
- E-Commerce
- Shopping
- Artificial Intelligence
- Product Reviews
- AI Agents
- MCP
- France
---
