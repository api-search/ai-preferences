---
claim_count: 4
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: Access the Service through automated means (bots, scrapers) without our permission.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: AI features are powered by third-party artificial intelligence services, our AI providers (currently Anthropic and TypeSafe).
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: null
    x-probed: https://conduitmail.app
  train_ai:
    stance: prohibited
    text: Email content sent to our AI providers for processing is not used for model training.
  train_genai:
    stance: prohibited
    text: Email content sent to our AI providers for processing is not used for model training.
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Conduit Mail
provenance_date: '2026-11-09'
provider_name: Conduit Mail
provider_slug: conduitmail-app
slug: conduitmail-app-ai-preferences
source_date: '2026-11-09'
source_filename: conduitmail-app-ai-preferences.yml
source_heading: AI Preferences
source_page: https://conduitmail.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Conduit Mail\naid: conduitmail-app\nurl: https://conduitmail.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: Email content sent to our AI providers for processing is not used for model training.\ntrain_genai:\n  stance: prohibited\n  text: Email content sent to our AI providers for processing is not used for model training.\nai_use:\n  stance: allowed\n  text: AI features are powered by third-party artificial intelligence services, our AI providers (currently Anthropic\n    and TypeSafe).\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n\
  \  text: Access the Service through automated means (bots, scrapers) without our permission.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: null\n  x-probed: https://conduitmail.app\n"
source_yaml_url: https://artifacts.apis.io/conduitmail-app/ai-preferences/conduitmail-app-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
- ai_use
- agent_actions
summary_line: 4 quoted statements, read from Conduit Mail's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Email Client
- Artificial Intelligence
- MCP
- AI Agents
- Productivity
- Automation
---
