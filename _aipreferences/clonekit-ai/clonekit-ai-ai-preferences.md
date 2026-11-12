---
api_specs:
- filename: clonekit-ai-openapi-generated.yml
  format: yaml
  label: CloneKit REST API
  slug: clonekit-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clonekit-ai/openapi/_ae-authored/clonekit-ai-openapi-generated.yml
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: attack, overload, scrape or reverse-engineer CloneKit, or get around its limits or security
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: allowed
    text: You allow CloneKit and the creators you buy from to charge your saved card for kits you or your AI buy, within your limits.
  ai_use:
    stance: unstated
    text: null
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://clonekit.ai/llms.txt
    x-probed: https://clonekit.ai
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
name: CloneKit
provenance_date: '2026-11-09'
provider_name: CloneKit
provider_slug: clonekit-ai
slug: clonekit-ai-ai-preferences
source_date: '2026-11-09'
source_filename: clonekit-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://clonekit.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CloneKit\naid: clonekit-ai\nurl: https://clonekit.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: attack, overload, scrape or reverse-engineer CloneKit, or get around its limits or security\nagent_purchases:\n  stance: allowed\n  text: You allow CloneKit and the creators you buy from to charge your saved card for kits you or your AI buy,\n    within your limits.\nsignals:\n  aipref_header:\
  \ false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://clonekit.ai/llms.txt\n  x-probed: https://clonekit.ai\n"
source_yaml_url: https://artifacts.apis.io/clonekit-ai/ai-preferences/clonekit-ai-ai-preferences.yml
stated_fields:
- agent_actions
- agent_purchases
summary_line: 2 quoted statements, read from CloneKit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Model Context Protocol
- Marketplace
- Playbooks
- Automation
---
