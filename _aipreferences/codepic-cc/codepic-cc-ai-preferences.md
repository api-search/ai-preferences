---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: Use automated scripts to access the Service in a way that exceeds reasonable usage
  agent_onboarding:
    stance: prohibited
    text: You must not create accounts through automated means
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
    llms_txt_url: https://codepic.cc/llms.txt
    x-probed: https://codepic.cc
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
name: CodePic
provenance_date: '2026-11-09'
provider_name: CodePic
provider_slug: codepic-cc
slug: codepic-cc-ai-preferences
source_date: '2026-11-09'
source_filename: codepic-cc-ai-preferences.yml
source_heading: AI Preferences
source_page: https://codepic.cc/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CodePic\naid: codepic-cc\nurl: https://codepic.cc/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: prohibited\n  text: You must not create accounts through automated means\nagent_actions:\n  stance: conditional\n  text: Use automated scripts to access the Service in a way that exceeds reasonable usage\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://codepic.cc/llms.txt\n\
  \  x-probed: https://codepic.cc\n"
source_yaml_url: https://artifacts.apis.io/codepic-cc/ai-preferences/codepic-cc-ai-preferences.yml
stated_fields:
- agent_onboarding
- agent_actions
summary_line: 2 quoted statements, read from CodePic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Whiteboard
- Diagramming
- Flowcharts
- MCP
- AI Agents
- Visual Collaboration
---
