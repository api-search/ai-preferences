---
api_specs:
- filename: comos-federation-com-openapi.yml
  format: yaml
  label: ComOS Federation Gateway
  slug: comos-federation-gateway
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comos-federation-com/openapi/comos-federation-com-openapi.yml
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: conditional
    text: you authorize that AI client to perform any action within the scopes you grant it
  agent_onboarding:
    stance: allowed
    text: A manager may be operated by a person or by an AI agent, and admittance does not distinguish between them.
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: The Merchant chooses which AI clients to connect to its ComOS tenant.
  signals:
    ai_txt_url: https://comos-federation.com/ai.txt
    aipref_header: false
    content_signals: false
    llms_txt_url: https://comos-federation.com/llms.txt
    x-probed: https://comos-federation.com
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
name: ComOS
provenance_date: '2026-11-09'
provider_name: ComOS
provider_slug: comos-federation-com
slug: comos-federation-com-ai-preferences
source_date: '2026-11-09'
source_filename: comos-federation-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://comos-federation.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: ComOS\naid: comos-federation-com\nurl: https://comos-federation.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: The Merchant chooses which AI clients to connect to its ComOS tenant.\nagent_onboarding:\n  stance: allowed\n  text: A manager may be operated by a person or by an AI agent, and admittance does not distinguish between them.\nagent_actions:\n  stance: conditional\n  text: you authorize that AI client to perform any action within the scopes you grant it\nagent_purchases:\n  stance:\
  \ unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: https://comos-federation.com/ai.txt\n  llms_txt_url: https://comos-federation.com/llms.txt\n  x-probed: https://comos-federation.com\n"
source_yaml_url: https://artifacts.apis.io/comos-federation-com/ai-preferences/comos-federation-com-ai-preferences.yml
stated_fields:
- ai_use
- agent_onboarding
- agent_actions
summary_line: 3 quoted statements, read from ComOS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commerce
- AI Agents
- MCP
- Federation
- Payments
- Self-Hosted
- Operating System
---
