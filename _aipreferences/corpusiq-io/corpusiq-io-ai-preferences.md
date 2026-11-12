---
api_specs:
- filename: corpusiq-io-authentication-api-openapi.yml
  format: yaml
  label: CorpusIQ Authentication API
  slug: corpusiq-io-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-authentication-api-openapi.yml
- filename: corpusiq-io-discovery-api-openapi.yml
  format: yaml
  label: CorpusIQ Discovery API
  slug: corpusiq-io-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-discovery-api-openapi.yml
- filename: corpusiq-io-mcp-api-openapi.yml
  format: yaml
  label: CorpusIQ MCP API
  slug: corpusiq-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-mcp-api-openapi.yml
- filename: corpusiq-io-usage-api-openapi.yml
  format: yaml
  label: CorpusIQ Usage API
  slug: corpusiq-io-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-usage-api-openapi.yml
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Attempt to reverse-engineer, scrape, or replicate the Service.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: By connecting third-party services, you grant CorpusIQ the right to access and index that data solely to provide the Service.
  signals:
    ai_txt_url: https://www.corpusiq.io/ai.txt
    aipref_header: false
    content_signals: false
    llms_txt_url: https://www.corpusiq.io/llms.txt
    x-probed: https://www.corpusiq.io
  train_ai:
    stance: prohibited
    text: We do not train AI models on your data.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: CorpusIQ
provenance_date: '2026-11-09'
provider_name: CorpusIQ
provider_slug: corpusiq-io
slug: corpusiq-io-ai-preferences
source_date: '2026-11-09'
source_filename: corpusiq-io-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.corpusiq.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CorpusIQ\naid: corpusiq-io\nurl: https://www.corpusiq.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not train AI models on your data.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: By connecting third-party services, you grant CorpusIQ the right to access and index that data solely to\n    provide the Service.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: Attempt to reverse-engineer, scrape, or replicate the Service.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n\
  \  aipref_header: false\n  content_signals: false\n  ai_txt_url: https://www.corpusiq.io/ai.txt\n  llms_txt_url: https://www.corpusiq.io/llms.txt\n  x-probed: https://www.corpusiq.io\n"
source_yaml_url: https://artifacts.apis.io/corpusiq-io/ai-preferences/corpusiq-io-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from CorpusIQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- Business Intelligence
- Small Business
- Integrations
- ChatGPT
- Analytics
---
