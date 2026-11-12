---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: An assistant you connect acts for you within what you approved.
  agent_onboarding:
    stance: conditional
    text: Your assistant signs in to CloudCrane with your approval
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
    llms_txt_url: https://cloudcrane.ai/llms.txt
    x-probed: https://cloudcrane.ai
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
name: CloudCrane
provenance_date: '2026-11-09'
provider_name: CloudCrane
provider_slug: cloudcrane-ai
slug: cloudcrane-ai-ai-preferences
source_date: '2026-11-09'
source_filename: cloudcrane-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cloudcrane.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CloudCrane\naid: cloudcrane-ai\nurl: https://cloudcrane.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: conditional\n  text: Your assistant signs in to CloudCrane with your approval\nagent_actions:\n  stance: conditional\n  text: An assistant you connect acts for you within what you approved.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://cloudcrane.ai/llms.txt\n\
  \  x-probed: https://cloudcrane.ai\n"
source_yaml_url: https://artifacts.apis.io/cloudcrane-ai/ai-preferences/cloudcrane-ai-ai-preferences.yml
stated_fields:
- agent_onboarding
- agent_actions
summary_line: 2 quoted statements, read from CloudCrane's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Assistants
- MCP
- Mobile Apps
- No-Code
- App Builder
- Progressive Web Apps
---
