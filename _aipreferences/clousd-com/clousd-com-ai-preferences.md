---
api_specs:
- filename: clousd-com-account-api-openapi.yml
  format: yaml
  label: Clousd Account API
  slug: clousd-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-account-api-openapi.yml
- filename: clousd-com-adb-api-openapi.yml
  format: yaml
  label: Clousd ADB API
  slug: clousd-com-adb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-adb-api-openapi.yml
- filename: clousd-com-ai-agents-api-openapi.yml
  format: yaml
  label: Clousd AI agents API
  slug: clousd-com-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-ai-agents-api-openapi.yml
- filename: clousd-com-apps-api-openapi.yml
  format: yaml
  label: Clousd Apps API
  slug: clousd-com-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-apps-api-openapi.yml
- filename: clousd-com-devices-api-openapi.yml
  format: yaml
  label: Clousd Devices API
  slug: clousd-com-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-devices-api-openapi.yml
- filename: clousd-com-files-and-media-api-openapi.yml
  format: yaml
  label: Clousd Files and media API
  slug: clousd-com-files-and-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-files-and-media-api-openapi.yml
- filename: clousd-com-network-api-openapi.yml
  format: yaml
  label: Clousd Network API
  slug: clousd-com-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-network-api-openapi.yml
- filename: clousd-com-screen-and-input-api-openapi.yml
  format: yaml
  label: Clousd Screen and input API
  slug: clousd-com-screen-and-input-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-screen-and-input-api-openapi.yml
- filename: clousd-com-tasks-api-openapi.yml
  format: yaml
  label: Clousd Tasks API
  slug: clousd-com-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-tasks-api-openapi.yml
- filename: clousd-com-webhooks-api-openapi.yml
  format: yaml
  label: Clousd Webhooks API
  slug: clousd-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  agent_actions:
    stance: conditional
    text: you authorize every action the agent takes through your keys or session as if you had taken it yourself
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: conditional
    text: You, not Clousd, must make sure that a person confirms actions with legal, financial or significant real-world effect before an agent performs them
  ai_use:
    stance: conditional
    text: If you connect your own key for Claude, OpenAI or another model provider, screenshots, UI trees, files and prompts from your devices are sent to that provider under your agreement with it
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://clousd.com/llms.txt
    x-probed: https://clousd.com
  train_ai:
    stance: prohibited
    text: We do not use your content for advertising, do not sell it and do not use it to train AI models.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Clousd
provenance_date: '2026-11-09'
provider_name: Clousd
provider_slug: clousd-com
slug: clousd-com-ai-preferences
source_date: '2026-11-09'
source_filename: clousd-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://clousd.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Clousd\naid: clousd-com\nurl: https://clousd.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not use your content for advertising, do not sell it and do not use it to train AI models.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: If you connect your own key for Claude, OpenAI or another model provider, screenshots, UI trees, files and\n    prompts from your devices are sent to that provider under your agreement with it\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: you authorize\
  \ every action the agent takes through your keys or session as if you had taken it yourself\nagent_purchases:\n  stance: conditional\n  text: You, not Clousd, must make sure that a person confirms actions with legal, financial or significant real-world\n    effect before an agent performs them\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://clousd.com/llms.txt\n  x-probed: https://clousd.com\n"
source_yaml_url: https://artifacts.apis.io/clousd-com/ai-preferences/clousd-com-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
- agent_purchases
summary_line: 4 quoted statements, read from Clousd's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Android
- Cloud Phones
- AI Agents
- MCP
- Mobile Testing
- QA
- Emulators
---
