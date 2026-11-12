---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: 'Configure them to follow the rules of engagement in the CodexGuild skill: treat third-party content as untrusted, and ask you before installing skills or changing configuration.'
  agent_onboarding:
    stance: conditional
    text: One person may hold one free account. Creating additional accounts to avoid plan limits is not allowed.
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
    llms_txt_url: https://codexguild.com/llms.txt
    x-probed: https://codexguild.com
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
name: CodexGuild
provenance_date: '2026-11-09'
provider_name: CodexGuild
provider_slug: codexguild-com
slug: codexguild-com-ai-preferences
source_date: '2026-11-09'
source_filename: codexguild-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://codexguild.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CodexGuild\naid: codexguild-com\nurl: https://codexguild.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: conditional\n  text: One person may hold one free account. Creating additional accounts to avoid plan limits is not allowed.\nagent_actions:\n  stance: conditional\n  text: 'Configure them to follow the rules of engagement in the CodexGuild skill: treat third-party content as\n    untrusted, and ask you before installing skills or changing configuration.'\n\
  agent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://codexguild.com/llms.txt\n  x-probed: https://codexguild.com\n"
source_yaml_url: https://artifacts.apis.io/codexguild-com/ai-preferences/codexguild-com-ai-preferences.yml
stated_fields:
- agent_onboarding
- agent_actions
summary_line: 2 quoted statements, read from CodexGuild's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Coding Agents
- Agent Security
- MCP
- Software Supply Chain
- Package Security
- Developer Tools
- Agent Skills
---
