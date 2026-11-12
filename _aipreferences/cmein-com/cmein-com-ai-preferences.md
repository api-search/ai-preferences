---
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: You and any Restricted Party may not scrape, crawl, spider, scroll, index, bulk-download, cache, mirror, or otherwise collect, copy, or extract images, photos, generated outputs, thumbnails, prompts, or metadata from the Service, whether manually or by any automated means, bot, script, headless browser, or AI agent.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: When you request image generation, your uploaded images and prompts may be sent to third-party AI services for processing.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://cmein.com/llms.txt
    x-probed: https://cmein.com
  train_ai:
    stance: conditional
    text: You and any Restricted Party may not use — and may not enable, fund, procure, or assist any other party to use — any image or content obtained from the Service to train, fine-tune, build, evaluate, or improve any model, classifier, detector
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: CMeIn
provenance_date: '2026-11-09'
provider_name: CMeIn
provider_slug: cmein-com
slug: cmein-com-ai-preferences
source_date: '2026-11-09'
source_filename: cmein-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cmein.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CMeIn\naid: cmein-com\nurl: https://cmein.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: You and any Restricted Party may not use — and may not enable, fund, procure, or assist any other party\n    to use — any image or content obtained from the Service to train, fine-tune, build, evaluate, or improve any\n    model, classifier, detector\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: When you request image generation, your uploaded images and prompts may be sent to third-party AI services\n    for processing.\nagent_onboarding:\n  stance:\
  \ unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: You and any Restricted Party may not scrape, crawl, spider, scroll, index, bulk-download, cache, mirror,\n    or otherwise collect, copy, or extract images, photos, generated outputs, thumbnails, prompts, or metadata from\n    the Service, whether manually or by any automated means, bot, script, headless browser, or AI agent.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://cmein.com/llms.txt\n  x-probed: https://cmein.com\n"
source_yaml_url: https://artifacts.apis.io/cmein-com/ai-preferences/cmein-com-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from CMeIn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Image Generation
- Photos
- Dating
- Headshots
- Consumer Apps
- MCP
---
