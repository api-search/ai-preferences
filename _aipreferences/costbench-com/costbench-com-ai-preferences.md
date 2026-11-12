---
api_specs:
- filename: costbench-com-compare-api-openapi.yml
  format: yaml
  label: CostBench Compare API
  slug: costbench-com-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costbench-com/openapi/costbench-com-compare-api-openapi.yml
- filename: costbench-com-coverage-api-openapi.yml
  format: yaml
  label: CostBench Coverage API
  slug: costbench-com-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costbench-com/openapi/costbench-com-coverage-api-openapi.yml
- filename: costbench-com-discover-api-openapi.yml
  format: yaml
  label: CostBench Discover API
  slug: costbench-com-discover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costbench-com/openapi/costbench-com-discover-api-openapi.yml
- filename: costbench-com-history-api-openapi.yml
  format: yaml
  label: CostBench History API
  slug: costbench-com-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costbench-com/openapi/costbench-com-history-api-openapi.yml
- filename: costbench-com-mcp-api-openapi.yml
  format: yaml
  label: CostBench MCP API
  slug: costbench-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costbench-com/openapi/costbench-com-mcp-api-openapi.yml
- filename: costbench-com-pricing-api-openapi.yml
  format: yaml
  label: CostBench Pricing API
  slug: costbench-com-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costbench-com/openapi/costbench-com-pricing-api-openapi.yml
- filename: costbench-com-tco-api-openapi.yml
  format: yaml
  label: CostBench Tco API
  slug: costbench-com-tco-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costbench-com/openapi/costbench-com-tco-api-openapi.yml
- filename: costbench-com-usage-api-openapi.yml
  format: yaml
  label: CostBench Usage API
  slug: costbench-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costbench-com/openapi/costbench-com-usage-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Use automated tools to scrape, harvest, or extract data from the Site
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
    llms_txt_url: https://costbench.com/llms.txt
    x-probed: https://costbench.com
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
name: CostBench
provenance_date: '2026-11-09'
provider_name: CostBench
provider_slug: costbench-com
slug: costbench-com-ai-preferences
source_date: '2026-11-09'
source_filename: costbench-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://costbench.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CostBench\naid: costbench-com\nurl: https://costbench.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: Use automated tools to scrape, harvest, or extract data from the Site\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: null\n  llms_txt_url: https://costbench.com/llms.txt\n  x-probed: https://costbench.com\n"
source_yaml_url: https://artifacts.apis.io/costbench-com/ai-preferences/costbench-com-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from CostBench's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software Pricing
- SaaS
- Procurement
- Cost Intelligence
- Price Comparison
- Total Cost of Ownership
- MCP
---
