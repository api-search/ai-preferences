---
api_specs:
- filename: cookiefreeanalytics-com-sites-api-openapi.yml
  format: yaml
  label: Cookie Free Analytics Sites API
  slug: cookiefreeanalytics-com-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cookiefreeanalytics-com/openapi/cookiefreeanalytics-com-sites-api-openapi.yml
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: only the permissions shown on that screen.
  agent_onboarding:
    stance: conditional
    text: An AI app only gets access after you click Allow, and only the permissions shown on that screen.
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
    llms_txt_url: https://www.cookiefreeanalytics.com/llms.txt
    x-probed: https://www.cookiefreeanalytics.com
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
name: Cookie Free Analytics
provenance_date: '2026-11-09'
provider_name: Cookie Free Analytics
provider_slug: cookiefreeanalytics-com
slug: cookiefreeanalytics-com-ai-preferences
source_date: '2026-11-09'
source_filename: cookiefreeanalytics-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.cookiefreeanalytics.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Cookie Free Analytics\naid: cookiefreeanalytics-com\nurl: https://www.cookiefreeanalytics.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: conditional\n  text: An AI app only gets access after you click Allow, and only the permissions shown on that screen.\nagent_actions:\n  stance: conditional\n  text: only the permissions shown on that screen.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n\
  \  ai_txt_url: null\n  llms_txt_url: https://www.cookiefreeanalytics.com/llms.txt\n  x-probed: https://www.cookiefreeanalytics.com\n"
source_yaml_url: https://artifacts.apis.io/cookiefreeanalytics-com/ai-preferences/cookiefreeanalytics-com-ai-preferences.yml
stated_fields:
- agent_onboarding
- agent_actions
summary_line: 2 quoted statements, read from Cookie Free Analytics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Web Analytics
- Privacy
- Cookieless
- GDPR
- MCP
- Uptime Monitoring
---
