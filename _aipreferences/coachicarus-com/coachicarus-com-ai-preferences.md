---
api_specs:
- filename: coachicarus-com-agent-api-openapi.yml
  format: yaml
  label: Coach Icarus Agent API
  slug: coachicarus-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coachicarus-com/openapi/coachicarus-com-agent-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: use automated means to abuse the Service
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
    llms_txt_url: https://www.coachicarus.com/llms.txt
    x-probed: https://www.coachicarus.com
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
name: Coach Icarus
provenance_date: '2026-11-09'
provider_name: Coach Icarus
provider_slug: coachicarus-com
slug: coachicarus-com-ai-preferences
source_date: '2026-11-09'
source_filename: coachicarus-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.coachicarus.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Coach Icarus\naid: coachicarus-com\nurl: https://www.coachicarus.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: use automated means to abuse the Service\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://www.coachicarus.com/llms.txt\n  x-probed: https://www.coachicarus.com\n"
source_yaml_url: https://artifacts.apis.io/coachicarus-com/ai-preferences/coachicarus-com-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from Coach Icarus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Running
- Fitness
- Coaching
- Garmin
- Health
- Wearables
- MCP
- AI Agents
---
