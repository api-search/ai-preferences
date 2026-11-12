---
api_specs:
- filename: converra-ai-api-openapi-generated.yml
  format: yaml
  label: Converra API Reference API
  slug: api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converra-ai/openapi/_ae-authored/converra-ai-api-openapi-generated.yml
- filename: converra-ai-core-openapi-generated.yml
  format: yaml
  label: Converra core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converra-ai/openapi/_ae-authored/converra-ai-core-openapi-generated.yml
- filename: converra-ai-guide-openapi-generated.yml
  format: yaml
  label: Converra Guide API
  slug: guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converra-ai/openapi/_ae-authored/converra-ai-guide-openapi-generated.yml
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
    stance: allowed
    text: 'To provide the Service, we may transmit Customer Data to: Third-party LLM Providers for inference, evaluation, and simulation'
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://converra.ai/llms.txt
    x-probed: https://converra.ai
  train_ai:
    stance: conditional
    text: Converra will not use Customer Data to train, fine-tune, or improve any machine learning model, foundation model, or AI system except as you direct under this Section.
  train_genai:
    stance: prohibited
    text: Customer Data is used solely to provide the Service to the specific Customer that submitted it, and is never used to train, fine-tune, or improve any model that serves another customer, any Converra platform model, or any foundation model.
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Converra
provenance_date: '2026-11-09'
provider_name: Converra
provider_slug: converra-ai
slug: converra-ai-ai-preferences
source_date: '2026-11-09'
source_filename: converra-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://converra.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Converra\naid: converra-ai\nurl: https://converra.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: Converra will not use Customer Data to train, fine-tune, or improve any machine learning model, foundation\n    model, or AI system except as you direct under this Section.\ntrain_genai:\n  stance: prohibited\n  text: Customer Data is used solely to provide the Service to the specific Customer that submitted it, and is never\n    used to train, fine-tune, or improve any model that serves another customer, any Converra platform model, or\n    any foundation model.\nai_use:\n  stance:\
  \ allowed\n  text: 'To provide the Service, we may transmit Customer Data to: Third-party LLM Providers for inference, evaluation,\n    and simulation'\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://converra.ai/llms.txt\n  x-probed: https://converra.ai\n"
source_yaml_url: https://artifacts.apis.io/converra-ai/ai-preferences/converra-ai-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
- ai_use
summary_line: 3 quoted statements, read from Converra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Agent Optimization
- LLM Observability
- Simulation Testing
- Prompt Engineering
- MCP
---
