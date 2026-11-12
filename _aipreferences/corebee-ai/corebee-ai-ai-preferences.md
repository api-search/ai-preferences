---
api_specs:
- filename: corebee-ai-auth-api-openapi.yml
  format: yaml
  label: Corebee Auth API
  slug: corebee-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-auth-api-openapi.yml
- filename: corebee-ai-contacts-api-openapi.yml
  format: yaml
  label: Corebee Contacts API
  slug: corebee-ai-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-contacts-api-openapi.yml
- filename: corebee-ai-conversations-api-openapi.yml
  format: yaml
  label: Corebee Conversations API
  slug: corebee-ai-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-conversations-api-openapi.yml
- filename: corebee-ai-labels-api-openapi.yml
  format: yaml
  label: Corebee Labels API
  slug: corebee-ai-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-labels-api-openapi.yml
- filename: corebee-ai-voice-api-openapi.yml
  format: yaml
  label: Corebee Voice API
  slug: corebee-ai-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-voice-api-openapi.yml
- filename: corebee-ai-webhooks-api-openapi.yml
  format: yaml
  label: Corebee Webhooks API
  slug: corebee-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  agent_actions:
    stance: conditional
    text: Section 6 (Acceptable Use) applies to all access through the API or MCP server, including by apps you connect.
  agent_onboarding:
    stance: conditional
    text: You may connect third-party apps and AI agents, for example Meta Muse, Claude, ChatGPT or Cursor, to the Service through our API or our Model Context Protocol (MCP) server, using API keys or OAuth access that you approve.
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: Your data is used solely to generate responses within the Service.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://corebee.ai/llms.txt
    x-probed: https://corebee.ai
  train_ai:
    stance: prohibited
    text: Corebee does not use your Customer Data to train, fine-tune, or improve AI models
  train_genai:
    stance: prohibited
    text: Corebee does not use your Customer Data to train, fine-tune, or improve AI models, and our AI model providers (OpenAI, Anthropic, Google Gemini) may not use it to train their models.
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Corebee
provenance_date: '2026-11-09'
provider_name: Corebee
provider_slug: corebee-ai
slug: corebee-ai-ai-preferences
source_date: '2026-11-09'
source_filename: corebee-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://corebee.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Corebee\naid: corebee-ai\nurl: https://corebee.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: Corebee does not use your Customer Data to train, fine-tune, or improve AI models\ntrain_genai:\n  stance: prohibited\n  text: Corebee does not use your Customer Data to train, fine-tune, or improve AI models, and our AI model providers\n    (OpenAI, Anthropic, Google Gemini) may not use it to train their models.\nai_use:\n  stance: allowed\n  text: Your data is used solely to generate responses within the Service.\nagent_onboarding:\n  stance: conditional\n  text: You may connect third-party\
  \ apps and AI agents, for example Meta Muse, Claude, ChatGPT or Cursor, to the\n    Service through our API or our Model Context Protocol (MCP) server, using API keys or OAuth access that you\n    approve.\nagent_actions:\n  stance: conditional\n  text: Section 6 (Acceptable Use) applies to all access through the API or MCP server, including by apps you connect.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://corebee.ai/llms.txt\n  x-probed: https://corebee.ai\n"
source_yaml_url: https://artifacts.apis.io/corebee-ai/ai-preferences/corebee-ai-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
- ai_use
- agent_onboarding
- agent_actions
summary_line: 5 quoted statements, read from Corebee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Support
- Artificial Intelligence
- Chatbots
- Help Desk
- Omnichannel Messaging
- Voice Agents
- MCP
---
