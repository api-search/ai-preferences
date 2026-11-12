---
api_specs:
- filename: conveo-ai-interviews-api-openapi.yml
  format: yaml
  label: Conveo Interviews API
  slug: conveo-ai-interviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conveo-ai/openapi/conveo-ai-interviews-api-openapi.yml
- filename: conveo-ai-studies-api-openapi.yml
  format: yaml
  label: Conveo Studies API
  slug: conveo-ai-studies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conveo-ai/openapi/conveo-ai-studies-api-openapi.yml
claim_count: 4
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Use automated systems, bots, spiders, or scraping tools to access the Service except through publicly documented APIs provided by Conveo.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: Conveo uses AI to generate study outlines and live interview questions.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: true
    llms_txt_url: https://conveo.ai/llms.txt
    x-probed: https://conveo.ai
  train_ai:
    stance: prohibited
    text: Conveo does not use Customer Content or Results to train foundation models or improve models for other customers.
  train_genai:
    stance: prohibited
    text: Conveo does not use Customer Content or Results to train foundation models or improve models for other customers.
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Conveo
provenance_date: '2026-11-09'
provider_name: Conveo
provider_slug: conveo-ai
slug: conveo-ai-ai-preferences
source_date: '2026-11-09'
source_filename: conveo-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://conveo.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Conveo\naid: conveo-ai\nurl: https://conveo.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: Conveo does not use Customer Content or Results to train foundation models or improve models for other customers.\ntrain_genai:\n  stance: prohibited\n  text: Conveo does not use Customer Content or Results to train foundation models or improve models for other customers.\nai_use:\n  stance: conditional\n  text: Conveo uses AI to generate study outlines and live interview questions.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n \
  \ text: Use automated systems, bots, spiders, or scraping tools to access the Service except through publicly documented\n    APIs provided by Conveo.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: null\n  llms_txt_url: https://conveo.ai/llms.txt\n  x-probed: https://conveo.ai\n"
source_yaml_url: https://artifacts.apis.io/conveo-ai/ai-preferences/conveo-ai-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
- ai_use
- agent_actions
summary_line: 4 quoted statements, read from Conveo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI
- Qualitative Research
- Market Research
- Customer Interviews
- Consumer Insights
- MCP
---
