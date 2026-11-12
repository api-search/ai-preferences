---
api_specs:
- filename: commerceforagents-com-mcp-api-openapi.yml
  format: yaml
  label: Commerce for Agents MCP API
  slug: commerceforagents-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commerceforagents-com/openapi/commerceforagents-com-mcp-api-openapi.yml
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: conditional
    text: to access it by automated means beyond its intended use in a way that overloads or abuses the underlying data sources
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: conditional
    text: every booking it submits is deemed submitted by you
  ai_use:
    stance: allowed
    text: The Service is designed to be used by AI agents on behalf of a human user
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: true
    llms_txt_url: https://commerceforagents.com/llms.txt
    x-probed: https://commerceforagents.com
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
name: Commerce for Agents
provenance_date: '2026-11-09'
provider_name: Commerce for Agents
provider_slug: commerceforagents-com
slug: commerceforagents-com-ai-preferences
source_date: '2026-11-09'
source_filename: commerceforagents-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://commerceforagents.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Commerce for Agents\naid: commerceforagents-com\nurl: https://commerceforagents.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: The Service is designed to be used by AI agents on behalf of a human user\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: to access it by automated means beyond its intended use in a way that overloads or abuses the underlying\n    data sources\nagent_purchases:\n  stance: conditional\n  text: every booking it submits\
  \ is deemed submitted by you\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: null\n  llms_txt_url: https://commerceforagents.com/llms.txt\n  x-probed: https://commerceforagents.com\n"
source_yaml_url: https://artifacts.apis.io/commerceforagents-com/ai-preferences/commerceforagents-com-ai-preferences.yml
stated_fields:
- ai_use
- agent_actions
- agent_purchases
summary_line: 3 quoted statements, read from Commerce for Agents's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agentic Commerce
- MCP
- Price Comparison
- Energy
- Electricity
- Gas
- Broadband
- Mobile Plans
- eSIM
- VPN
- Germany
---
