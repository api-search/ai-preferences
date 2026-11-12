---
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: access the Service by automated means (scraping, bots, crawlers) except through interfaces we provide for that purpose
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: AI features may be delivered using third-party AI providers acting as our service providers, as described in the Privacy Policy.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://clevra.ai/llms.txt
    x-probed: https://clevra.ai
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
name: Clevra
provenance_date: '2026-11-09'
provider_name: Clevra
provider_slug: clevra-ai
slug: clevra-ai-ai-preferences
source_date: '2026-11-09'
source_filename: clevra-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://clevra.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Clevra\naid: clevra-ai\nurl: https://clevra.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: conditional\n  text: AI features may be delivered using third-party AI providers acting as our service providers, as described\n    in the Privacy Policy.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: access the Service by automated means (scraping, bots, crawlers) except through interfaces we provide for\n    that purpose\nagent_purchases:\n  stance: unstated\n\
  \  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://clevra.ai/llms.txt\n  x-probed: https://clevra.ai\n"
source_yaml_url: https://artifacts.apis.io/clevra-ai/ai-preferences/clevra-ai-ai-preferences.yml
stated_fields:
- ai_use
- agent_actions
summary_line: 2 quoted statements, read from Clevra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Field Service Management
- Contractors
- Scheduling
- Invoicing
- Payments
- CRM
- MCP
- AI Assistants
---
