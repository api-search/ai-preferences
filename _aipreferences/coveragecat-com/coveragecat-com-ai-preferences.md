---
api_specs:
- filename: coveragecat-com-agent-api-openapi.yml
  format: yaml
  label: Coverage Cat Agent API
  slug: coveragecat-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coveragecat-com/openapi/coveragecat-com-agent-api-openapi.yml
- filename: coveragecat-com-consumer-api-openapi.yml
  format: yaml
  label: Coverage Cat Consumer API
  slug: coveragecat-com-consumer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coveragecat-com/openapi/coveragecat-com-consumer-api-openapi.yml
- filename: coveragecat-com-intake-api-openapi.yml
  format: yaml
  label: Coverage Cat Intake API
  slug: coveragecat-com-intake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coveragecat-com/openapi/coveragecat-com-intake-api-openapi.yml
- filename: coveragecat-com-tools-api-openapi.yml
  format: yaml
  label: Coverage Cat Tools API
  slug: coveragecat-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coveragecat-com/openapi/coveragecat-com-tools-api-openapi.yml
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: unstated
    text: null
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: including vendors that provide artificial intelligence or large language model services—such as OpenAI, Anthropic, AWS, and others—subject to applicable law and our agreements with those vendors.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://coveragecat.com/llms.txt
    x-probed: https://coveragecat.com
  train_ai:
    stance: conditional
    text: and evaluating, training, fine-tuning, or otherwise improving artificial intelligence, machine learning, large language model, and similar systems.
  train_genai:
    stance: conditional
    text: and evaluating, training, fine-tuning, or otherwise improving artificial intelligence, machine learning, large language model, and similar systems.
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Coverage Cat
provenance_date: '2026-11-09'
provider_name: Coverage Cat
provider_slug: coveragecat-com
slug: coveragecat-com-ai-preferences
source_date: '2026-11-09'
source_filename: coveragecat-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.coveragecat.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Coverage Cat\naid: coveragecat-com\nurl: https://www.coveragecat.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: and evaluating, training, fine-tuning, or otherwise improving artificial intelligence, machine learning,\n    large language model, and similar systems.\ntrain_genai:\n  stance: conditional\n  text: and evaluating, training, fine-tuning, or otherwise improving artificial intelligence, machine learning,\n    large language model, and similar systems.\nai_use:\n  stance: conditional\n  text: including vendors that provide artificial intelligence or large\
  \ language model services—such as OpenAI,\n    Anthropic, AWS, and others—subject to applicable law and our agreements with those vendors.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://coveragecat.com/llms.txt\n  x-probed: https://coveragecat.com\n"
source_yaml_url: https://artifacts.apis.io/coveragecat-com/ai-preferences/coveragecat-com-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
- ai_use
summary_line: 3 quoted statements, read from Coverage Cat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurance Broker
- Homeowners Insurance
- Umbrella Insurance
- Auto Insurance
- AI Agents
- MCP
---
