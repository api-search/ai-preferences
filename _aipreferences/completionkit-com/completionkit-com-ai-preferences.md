---
api_specs:
- filename: completionkit-com-openapi-generated.yml
  format: yaml
  label: CompletionKit API
  slug: completionkit-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/completionkit-com/openapi/_ae-authored/completionkit-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: scrape, reverse-engineer, or resell the Service itself to third parties.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: The Service routes LLM requests to third-party providers (OpenAI, Anthropic, OpenRouter, and any others you configure). Those providers' terms apply to their handling of the content you send through them.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://completionkit.com/llms.txt
    x-probed: https://completionkit.com
  train_ai:
    stance: conditional
    text: We will not use Your Content to train models for third parties.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: CompletionKit
provenance_date: '2026-11-09'
provider_name: CompletionKit
provider_slug: completionkit-com
slug: completionkit-com-ai-preferences
source_date: '2026-11-09'
source_filename: completionkit-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://completionkit.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CompletionKit\naid: completionkit-com\nurl: https://completionkit.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: We will not use Your Content to train models for third parties.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: The Service routes LLM requests to third-party providers (OpenAI, Anthropic, OpenRouter, and any others\n    you configure). Those providers' terms apply to their handling of the content you send through them.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text:\
  \ scrape, reverse-engineer, or resell the Service itself to third parties.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://completionkit.com/llms.txt\n  x-probed: https://completionkit.com\n"
source_yaml_url: https://artifacts.apis.io/completionkit-com/ai-preferences/completionkit-com-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from CompletionKit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- Prompt Engineering
- Evaluation
- Testing
- Developer Tools
- MCP
---
