---
api_specs:
- filename: cosvoice-com-activity-api-openapi.yml
  format: yaml
  label: CosVoice Activity API
  slug: cosvoice-com-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-activity-api-openapi.yml
- filename: cosvoice-com-calls-api-openapi.yml
  format: yaml
  label: CosVoice Calls API
  slug: cosvoice-com-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-calls-api-openapi.yml
- filename: cosvoice-com-contacts-api-openapi.yml
  format: yaml
  label: CosVoice Contacts API
  slug: cosvoice-com-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-contacts-api-openapi.yml
- filename: cosvoice-com-emails-api-openapi.yml
  format: yaml
  label: CosVoice Emails API
  slug: cosvoice-com-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-emails-api-openapi.yml
- filename: cosvoice-com-history-api-openapi.yml
  format: yaml
  label: CosVoice History API
  slug: cosvoice-com-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-history-api-openapi.yml
- filename: cosvoice-com-line-api-openapi.yml
  format: yaml
  label: CosVoice Line API
  slug: cosvoice-com-line-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-line-api-openapi.yml
- filename: cosvoice-com-messages-api-openapi.yml
  format: yaml
  label: CosVoice Messages API
  slug: cosvoice-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-messages-api-openapi.yml
- filename: cosvoice-com-reservations-api-openapi.yml
  format: yaml
  label: CosVoice Reservations API
  slug: cosvoice-com-reservations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-reservations-api-openapi.yml
- filename: cosvoice-com-settings-api-openapi.yml
  format: yaml
  label: CosVoice Settings API
  slug: cosvoice-com-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-settings-api-openapi.yml
- filename: cosvoice-com-webhook-api-openapi.yml
  format: yaml
  label: CosVoice Webhook API
  slug: cosvoice-com-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-webhook-api-openapi.yml
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: allowed
    text: CosVoice gives your AI assistant a phone number and an email address, answers and places calls on your instruction
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: prohibited
    text: The line never makes payments
  ai_use:
    stance: unstated
    text: null
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://cosvoice.com/llms.txt
    x-probed: https://cosvoice.com
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
name: CosVoice
provenance_date: '2026-11-09'
provider_name: CosVoice
provider_slug: cosvoice-com
slug: cosvoice-com-ai-preferences
source_date: '2026-11-09'
source_filename: cosvoice-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cosvoice.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CosVoice\naid: cosvoice-com\nurl: https://cosvoice.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: allowed\n  text: CosVoice gives your AI assistant a phone number and an email address, answers and places calls on your instruction\nagent_purchases:\n  stance: prohibited\n  text: The line never makes payments\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://cosvoice.com/llms.txt\n\
  \  x-probed: https://cosvoice.com\n"
source_yaml_url: https://artifacts.apis.io/cosvoice-com/ai-preferences/cosvoice-com-ai-preferences.yml
stated_fields:
- agent_actions
- agent_purchases
summary_line: 2 quoted statements, read from CosVoice's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Voice
- Telephony
- Phone Numbers
- AI Receptionist
- Call Transcription
- MCP
- Small Business
---
