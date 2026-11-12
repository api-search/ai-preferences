---
api_specs:
- filename: cnpj-ai-cat-logo-api-openapi.yml
  format: yaml
  label: cnpj.ai Catálogo API
  slug: cnpj-ai-cat-logo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-cat-logo-api-openapi.yml
- filename: cnpj-ai-consulta-de-cnpj-api-openapi.yml
  format: yaml
  label: cnpj.ai Consulta de CNPJ API
  slug: cnpj-ai-consulta-de-cnpj-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-consulta-de-cnpj-api-openapi.yml
- filename: cnpj-ai-empresas-api-openapi.yml
  format: yaml
  label: cnpj.ai Empresas API
  slug: cnpj-ai-empresas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-empresas-api-openapi.yml
- filename: cnpj-ai-empresas-fontes-api-openapi.yml
  format: yaml
  label: cnpj.ai empresas — fontes API
  slug: cnpj-ai-empresas-fontes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-empresas-fontes-api-openapi.yml
- filename: cnpj-ai-estabelecimentos-api-openapi.yml
  format: yaml
  label: cnpj.ai Estabelecimentos API
  slug: cnpj-ai-estabelecimentos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-estabelecimentos-api-openapi.yml
- filename: cnpj-ai-estabelecimentos-fontes-api-openapi.yml
  format: yaml
  label: cnpj.ai estabelecimentos — fontes API
  slug: cnpj-ai-estabelecimentos-fontes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-estabelecimentos-fontes-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Também não é permitido contornar limites de requisições, sobrecarregar o serviço com coleta automatizada fora da API
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
    llms_txt_url: null
    x-probed: https://cnpj.ai
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
name: cnpj.ai
provenance_date: '2026-11-09'
provider_name: cnpj.ai
provider_slug: cnpj-ai
slug: cnpj-ai-ai-preferences
source_date: '2026-11-09'
source_filename: cnpj-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cnpj.ai/termos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: cnpj.ai\naid: cnpj-ai\nurl: https://cnpj.ai/termos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: Também não é permitido contornar limites de requisições, sobrecarregar o serviço com coleta automatizada\n    fora da API\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: null\n  x-probed: https://cnpj.ai\n"
source_yaml_url: https://artifacts.apis.io/cnpj-ai/ai-preferences/cnpj-ai-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from cnpj.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Data
- Brazil
- CNPJ
- Open Data
- Public Records
- Business Registry
- Compliance
- MCP
---
