---
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Uses bots, scrapers, or automation to artificially inflate extractions, gaming the system, or extract data at scale
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: AI analysis and extraction processing — submitted content URLs, transcripts, and file text are sent to these providers
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://corewise.video/llms.txt
    x-probed: https://corewise.video
  train_ai:
    stance: prohibited
    text: CoreWise does not claim ownership of, and will not use for training purposes, the content of your extractions.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: CoreWise
provenance_date: '2026-11-09'
provider_name: CoreWise
provider_slug: corewise-video
slug: corewise-video-ai-preferences
source_date: '2026-11-09'
source_filename: corewise-video-ai-preferences.yml
source_heading: AI Preferences
source_page: https://corewise.video/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CoreWise\naid: corewise-video\nurl: https://corewise.video/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: CoreWise does not claim ownership of, and will not use for training purposes, the content of your extractions.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: AI analysis and extraction processing — submitted content URLs, transcripts, and file text are sent to these\n    providers\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: Uses bots, scrapers, or automation to artificially inflate\
  \ extractions, gaming the system, or extract data\n    at scale\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://corewise.video/llms.txt\n  x-probed: https://corewise.video\n"
source_yaml_url: https://artifacts.apis.io/corewise-video/ai-preferences/corewise-video-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from CoreWise's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video Summarization
- Knowledge Management
- Research
- Model Context Protocol
- Content Extraction
---
