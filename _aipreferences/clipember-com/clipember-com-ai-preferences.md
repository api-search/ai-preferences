---
claim_count: 4
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: break, overload, probe or circumvent ClipEmber ’s limits or security (including scraping, credential stuffing, or bypassing credit accounting)
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: ClipEmber uses automated systems to choose moments, transcribe speech, and suggest titles, hashtags, summaries and translations.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://clipember.com/llms.txt
    x-probed: https://clipember.com
  train_ai:
    stance: prohibited
    text: does not let us publish, license, sell or train models on your content.
  train_genai:
    stance: prohibited
    text: does not let us publish, license, sell or train models on your content.
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: ClipEmber
provenance_date: '2026-11-09'
provider_name: ClipEmber
provider_slug: clipember-com
slug: clipember-com-ai-preferences
source_date: '2026-11-09'
source_filename: clipember-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://clipember.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: ClipEmber\naid: clipember-com\nurl: https://clipember.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: does not let us publish, license, sell or train models on your content.\ntrain_genai:\n  stance: prohibited\n  text: does not let us publish, license, sell or train models on your content.\nai_use:\n  stance: allowed\n  text: ClipEmber uses automated systems to choose moments, transcribe speech, and suggest titles, hashtags, summaries\n    and translations.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: break, overload, probe\
  \ or circumvent ClipEmber ’s limits or security (including scraping, credential stuffing,\n    or bypassing credit accounting)\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://clipember.com/llms.txt\n  x-probed: https://clipember.com\n"
source_yaml_url: https://artifacts.apis.io/clipember-com/ai-preferences/clipember-com-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
- ai_use
- agent_actions
summary_line: 4 quoted statements, read from ClipEmber's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Artificial Intelligence
- Video Editing
- Short-Form Video
- Captions
- Social Media
- MCP
---
