---
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Engage in any automated use of the system, such as using scripts to send comments or messages, or using any data mining, robots, or similar data gathering and extraction tools.
  agent_onboarding:
    stance: prohibited
    text: creating user accounts by automated means or under false pretenses
  agent_purchases:
    stance: prohibited
    text: Use a buying agent or purchasing agent to make purchases on the Services.
  ai_use:
    stance: unstated
    text: null
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://clipstudio.ai/llms.txt
    x-probed: https://clipstudio.ai
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
name: Clip Studio AI
provenance_date: '2026-11-09'
provider_name: Clip Studio AI
provider_slug: clipstudio-ai
slug: clipstudio-ai-ai-preferences
source_date: '2026-11-09'
source_filename: clipstudio-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://clipstudio.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Clip Studio AI\naid: clipstudio-ai\nurl: https://clipstudio.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: prohibited\n  text: creating user accounts by automated means or under false pretenses\nagent_actions:\n  stance: prohibited\n  text: Engage in any automated use of the system, such as using scripts to send comments or messages, or using\n    any data mining, robots, or similar data gathering and extraction tools.\nagent_purchases:\n  stance: prohibited\n\
  \  text: Use a buying agent or purchasing agent to make purchases on the Services.\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://clipstudio.ai/llms.txt\n  x-probed: https://clipstudio.ai\n"
source_yaml_url: https://artifacts.apis.io/clipstudio-ai/ai-preferences/clipstudio-ai-ai-preferences.yml
stated_fields:
- agent_onboarding
- agent_actions
- agent_purchases
summary_line: 3 quoted statements, read from Clip Studio AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Video
- Video Generation
- Generative AI
- Image Generation
- Short-Form Video
- Video Ads
- MCP
---
