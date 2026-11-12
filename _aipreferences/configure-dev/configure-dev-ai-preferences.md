---
api_specs:
- filename: configure-dev-auth-api-openapi.yml
  format: yaml
  label: Configure Auth API
  slug: configure-dev-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-auth-api-openapi.yml
- filename: configure-dev-connectors-api-openapi.yml
  format: yaml
  label: Configure Connectors API
  slug: configure-dev-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-connectors-api-openapi.yml
- filename: configure-dev-files-api-openapi.yml
  format: yaml
  label: Configure Files API
  slug: configure-dev-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-files-api-openapi.yml
- filename: configure-dev-import-api-openapi.yml
  format: yaml
  label: Configure Import API
  slug: configure-dev-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-import-api-openapi.yml
- filename: configure-dev-profile-api-openapi.yml
  format: yaml
  label: Configure Profile API
  slug: configure-dev-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-profile-api-openapi.yml
- filename: configure-dev-web-api-openapi.yml
  format: yaml
  label: Configure Web API
  slug: configure-dev-web-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-web-api-openapi.yml
- filename: configure-dev-webhooks-api-openapi.yml
  format: yaml
  label: Configure Webhooks API
  slug: configure-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: conditional
    text: Use automated means to access the service except through authorized APIs
  agent_onboarding:
    stance: conditional
    text: You may not impersonate another person or create an account on behalf of someone else without their authorization.
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: Conversations between you and agents using Configure may be processed by AI models to extract facts, preferences, and context.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://configure.dev/llms.txt
    x-probed: https://configure.dev
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
name: Configure
provenance_date: '2026-11-09'
provider_name: Configure
provider_slug: configure-dev
slug: configure-dev-ai-preferences
source_date: '2026-11-09'
source_filename: configure-dev-ai-preferences.yml
source_heading: AI Preferences
source_page: https://configure.dev/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Configure\naid: configure-dev\nurl: https://configure.dev/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: Conversations between you and agents using Configure may be processed by AI models to extract facts, preferences,\n    and context.\nagent_onboarding:\n  stance: conditional\n  text: You may not impersonate another person or create an account on behalf of someone else without their authorization.\nagent_actions:\n  stance: conditional\n  text: Use automated means to access the service\
  \ except through authorized APIs\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://configure.dev/llms.txt\n  x-probed: https://configure.dev\n"
source_yaml_url: https://artifacts.apis.io/configure-dev/ai-preferences/configure-dev-ai-preferences.yml
stated_fields:
- ai_use
- agent_onboarding
- agent_actions
summary_line: 3 quoted statements, read from Configure's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Memory
- Personalization
- User Context
- MCP
---
