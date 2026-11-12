---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: allowed
    text: You can run CompSlate from an AI assistant, such as Claude (from Anthropic) or ChatGPT (from OpenAI), by connecting it to the Service.
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
    llms_txt_url: https://compslate.com/llms.txt
    x-probed: https://compslate.com
  train_ai:
    stance: prohibited
    text: We don't sell Customer Data, use it for advertising, or use it to train AI models.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: CompSlate
provenance_date: '2026-11-09'
provider_name: CompSlate
provider_slug: compslate-com
slug: compslate-com-ai-preferences
source_date: '2026-11-09'
source_filename: compslate-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://compslate.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CompSlate\naid: compslate-com\nurl: https://compslate.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We don't sell Customer Data, use it for advertising, or use it to train AI models.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: allowed\n  text: You can run CompSlate from an AI assistant, such as Claude (from Anthropic) or ChatGPT (from OpenAI), by\n    connecting it to the Service.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header:\
  \ false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://compslate.com/llms.txt\n  x-probed: https://compslate.com\n"
source_yaml_url: https://artifacts.apis.io/compslate-com/ai-preferences/compslate-com-ai-preferences.yml
stated_fields:
- train_ai
- agent_actions
summary_line: 2 quoted statements, read from CompSlate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sales Compensation
- Sales Commissions
- Revenue Operations
- MCP
- AI Assistants
- SaaS
---
