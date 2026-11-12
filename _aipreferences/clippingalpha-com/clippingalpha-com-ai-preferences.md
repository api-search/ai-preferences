---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: You are responsible for what an agent you connect does with that access.
  agent_onboarding:
    stance: conditional
    text: Once you approve it, it can see members campaigns, read and change your bookmarks and alert rules
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: unstated
    text: null
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: true
    llms_txt_url: https://clippingalpha.com/llms.txt
    x-probed: https://clippingalpha.com
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
name: ClippingAlpha
provenance_date: '2026-11-09'
provider_name: ClippingAlpha
provider_slug: clippingalpha-com
slug: clippingalpha-com-ai-preferences
source_date: '2026-11-09'
source_filename: clippingalpha-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://clippingalpha.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: ClippingAlpha\naid: clippingalpha-com\nurl: https://clippingalpha.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: conditional\n  text: Once you approve it, it can see members campaigns, read and change your bookmarks and alert rules\nagent_actions:\n  stance: conditional\n  text: You are responsible for what an agent you connect does with that access.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals:\
  \ true\n  ai_txt_url: null\n  llms_txt_url: https://clippingalpha.com/llms.txt\n  x-probed: https://clippingalpha.com\n"
source_yaml_url: https://artifacts.apis.io/clippingalpha-com/ai-preferences/clippingalpha-com-ai-preferences.yml
stated_fields:
- agent_onboarding
- agent_actions
summary_line: 2 quoted statements, read from ClippingAlpha's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Clipping
- UGC
- Creator Economy
- Influencer Marketing
- Campaigns
- MCP
- Open Data
- Short-Form Video
---
