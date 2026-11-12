---
api_specs:
- filename: clipkit-dev-openapi-generated.yml
  format: yaml
  label: Clipkit Render API
  slug: clipkit-dev-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipkit-dev/openapi/_ae-authored/clipkit-dev-openapi-generated.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: unstated
    text: null
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
    llms_txt_url: https://www.clipkit.dev/llms.txt
    x-probed: https://www.clipkit.dev
  train_ai:
    stance: conditional
    text: We do not use the actual content of paid or business plan users to train or develop models or features without opt-in consent.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Clipkit
provenance_date: '2026-11-09'
provider_name: Clipkit
provider_slug: clipkit-dev
slug: clipkit-dev-ai-preferences
source_date: '2026-11-09'
source_filename: clipkit-dev-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.clipkit.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Clipkit\naid: clipkit-dev\nurl: https://www.clipkit.dev/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: We do not use the actual content of paid or business plan users to train or develop models or features without\n    opt-in consent.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url:\
  \ https://www.clipkit.dev/llms.txt\n  x-probed: https://www.clipkit.dev\n"
source_yaml_url: https://artifacts.apis.io/clipkit-dev/ai-preferences/clipkit-dev-ai-preferences.yml
stated_fields:
- train_ai
summary_line: 1 quoted statement, read from Clipkit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Video Rendering
- AI Agents
- MCP
- JSON
- Open Source
- Developer Tools
---
