---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: 'A connected application (for example an AI assistant using MCP) acts on your behalf within the access you grant: it converts files and can see your account email, conversion history and limits.'
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
    llms_txt_url: https://www.conved.com/llms.txt
    x-probed: https://www.conved.com
  train_ai:
    stance: prohibited
    text: We do not read their content, use it for any other purpose or use it to train artificial intelligence.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: conved.com
provenance_date: '2026-11-09'
provider_name: conved.com
provider_slug: conved-com
slug: conved-com-ai-preferences
source_date: '2026-11-09'
source_filename: conved-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.conved.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: conved.com\naid: conved-com\nurl: https://www.conved.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not read their content, use it for any other purpose or use it to train artificial intelligence.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: 'A connected application (for example an AI assistant using MCP) acts on your behalf within the access you\n    grant: it converts files and can see your account email, conversion history\
  \ and limits.'\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://www.conved.com/llms.txt\n  x-probed: https://www.conved.com\n"
source_yaml_url: https://artifacts.apis.io/conved-com/ai-preferences/conved-com-ai-preferences.yml
stated_fields:
- train_ai
- agent_actions
summary_line: 2 quoted statements, read from conved.com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- File Conversion
- Documents
- Images
- Media
- MCP
- CLI
- Developer Tools
---
