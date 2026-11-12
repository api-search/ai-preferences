---
api_specs:
- filename: coordigent-com-agents-api-openapi.yml
  format: yaml
  label: Coordigent Agents API
  slug: coordigent-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-agents-api-openapi.yml
- filename: coordigent-com-events-api-openapi.yml
  format: yaml
  label: Coordigent Events API
  slug: coordigent-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-events-api-openapi.yml
- filename: coordigent-com-items-api-openapi.yml
  format: yaml
  label: Coordigent Items API
  slug: coordigent-com-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-items-api-openapi.yml
- filename: coordigent-com-me-api-openapi.yml
  format: yaml
  label: Coordigent Me API
  slug: coordigent-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-me-api-openapi.yml
- filename: coordigent-com-projects-api-openapi.yml
  format: yaml
  label: Coordigent Projects API
  slug: coordigent-com-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-projects-api-openapi.yml
- filename: coordigent-com-stream-api-openapi.yml
  format: yaml
  label: Coordigent Stream API
  slug: coordigent-com-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-stream-api-openapi.yml
- filename: coordigent-com-threads-api-openapi.yml
  format: yaml
  label: Coordigent Threads API
  slug: coordigent-com-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-threads-api-openapi.yml
- filename: coordigent-com-webhooks-api-openapi.yml
  format: yaml
  label: Coordigent Webhooks API
  slug: coordigent-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-webhooks-api-openapi.yml
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
    stance: conditional
    text: A project's owner or an admin can switch on an agent that drafts suggestions for resolving conflicts, using a third-party language model. It is off by default.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://coordigent.com/llms.txt
    x-probed: https://coordigent.com
  train_ai:
    stance: prohibited
    text: We do not claim ownership of it, and we do not use it to train models.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Coordigent
provenance_date: '2026-11-09'
provider_name: Coordigent
provider_slug: coordigent-com
slug: coordigent-com-ai-preferences
source_date: '2026-11-09'
source_filename: coordigent-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://coordigent.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Coordigent\naid: coordigent-com\nurl: https://coordigent.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not claim ownership of it, and we do not use it to train models.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: A project's owner or an admin can switch on an agent that drafts suggestions for resolving conflicts, using\n    a third-party language model. It is off by default.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n  text: null\n\
  signals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://coordigent.com/llms.txt\n  x-probed: https://coordigent.com\n"
source_yaml_url: https://artifacts.apis.io/coordigent-com/ai-preferences/coordigent-com-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
summary_line: 2 quoted statements, read from Coordigent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Coding Agents
- MCP
- Developer Tools
- Agent Coordination
- CLI
---
