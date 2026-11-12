---
api_specs:
- filename: codebase-design-account-api-openapi.yml
  format: yaml
  label: Codebase Account API
  slug: codebase-design-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-account-api-openapi.yml
- filename: codebase-design-admin-api-openapi.yml
  format: yaml
  label: Codebase Admin API
  slug: codebase-design-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-admin-api-openapi.yml
- filename: codebase-design-api-keys-api-openapi.yml
  format: yaml
  label: Codebase API Keys API
  slug: codebase-design-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-api-keys-api-openapi.yml
- filename: codebase-design-billing-api-openapi.yml
  format: yaml
  label: Codebase Billing API
  slug: codebase-design-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-billing-api-openapi.yml
- filename: codebase-design-builds-api-openapi.yml
  format: yaml
  label: Codebase Builds API
  slug: codebase-design-builds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-builds-api-openapi.yml
- filename: codebase-design-community-api-openapi.yml
  format: yaml
  label: Codebase Community API
  slug: codebase-design-community-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-community-api-openapi.yml
- filename: codebase-design-credits-api-openapi.yml
  format: yaml
  label: Codebase Credits API
  slug: codebase-design-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-credits-api-openapi.yml
- filename: codebase-design-deploys-api-openapi.yml
  format: yaml
  label: Codebase Deploys API
  slug: codebase-design-deploys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-deploys-api-openapi.yml
- filename: codebase-design-gallery-api-openapi.yml
  format: yaml
  label: Codebase Gallery API
  slug: codebase-design-gallery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-gallery-api-openapi.yml
- filename: codebase-design-health-api-openapi.yml
  format: yaml
  label: Codebase Health API
  slug: codebase-design-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-health-api-openapi.yml
- filename: codebase-design-inference-api-openapi.yml
  format: yaml
  label: Codebase Inference API
  slug: codebase-design-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-inference-api-openapi.yml
- filename: codebase-design-platform-api-openapi.yml
  format: yaml
  label: Codebase Platform API
  slug: codebase-design-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-platform-api-openapi.yml
- filename: codebase-design-projects-api-openapi.yml
  format: yaml
  label: Codebase Projects API
  slug: codebase-design-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-projects-api-openapi.yml
- filename: codebase-design-prompts-api-openapi.yml
  format: yaml
  label: Codebase Prompts API
  slug: codebase-design-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-prompts-api-openapi.yml
- filename: codebase-design-sessions-api-openapi.yml
  format: yaml
  label: Codebase Sessions API
  slug: codebase-design-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-sessions-api-openapi.yml
claim_count: 2
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
    stance: unstated
    text: null
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://codebase.design/llms.txt
    x-probed: https://codebase.design
  train_ai:
    stance: conditional
    text: We do not use your prompts, project files, or generated code to train our own or third-party foundation models without your explicit permission.
  train_genai:
    stance: conditional
    text: We do not use your prompts, project files, or generated code to train our own or third-party foundation models without your explicit permission.
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Codebase
provenance_date: '2026-11-09'
provider_name: Codebase
provider_slug: codebase-design
slug: codebase-design-ai-preferences
source_date: '2026-11-09'
source_filename: codebase-design-ai-preferences.yml
source_heading: AI Preferences
source_page: https://codebase.design/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Codebase\naid: codebase-design\nurl: https://codebase.design/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: We do not use your prompts, project files, or generated code to train our own or third-party foundation\n    models without your explicit permission.\ntrain_genai:\n  stance: conditional\n  text: We do not use your prompts, project files, or generated code to train our own or third-party foundation\n    models without your explicit permission.\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: unstated\n\
  \  text: null\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://codebase.design/llms.txt\n  x-probed: https://codebase.design\n"
source_yaml_url: https://artifacts.apis.io/codebase-design/ai-preferences/codebase-design-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
summary_line: 2 quoted statements, read from Codebase's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI App Builder
- Code Generation
- Developer Tools
- Open-Weight Models
- CLI
- MCP
- Web3
---
