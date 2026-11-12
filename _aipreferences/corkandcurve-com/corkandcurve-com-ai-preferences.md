---
api_specs:
- filename: corkandcurve-com-bookable-api-openapi.yml
  format: yaml
  label: Cork & Curve Bookable API
  slug: corkandcurve-com-bookable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corkandcurve-com/openapi/corkandcurve-com-bookable-api-openapi.yml
- filename: corkandcurve-com-festivals-api-openapi.yml
  format: yaml
  label: Cork & Curve Festivals API
  slug: corkandcurve-com-festivals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corkandcurve-com/openapi/corkandcurve-com-festivals-api-openapi.yml
- filename: corkandcurve-com-meta-api-openapi.yml
  format: yaml
  label: Cork & Curve Meta API
  slug: corkandcurve-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corkandcurve-com/openapi/corkandcurve-com-meta-api-openapi.yml
- filename: corkandcurve-com-places-api-openapi.yml
  format: yaml
  label: Cork & Curve Places API
  slug: corkandcurve-com-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corkandcurve-com/openapi/corkandcurve-com-places-api-openapi.yml
- filename: corkandcurve-com-site-api-openapi.yml
  format: yaml
  label: Cork & Curve Site API
  slug: corkandcurve-com-site-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corkandcurve-com/openapi/corkandcurve-com-site-api-openapi.yml
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: We block crawlers that misbehave.
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
    llms_txt_url: https://corkandcurve.com/llms.txt
    x-probed: https://corkandcurve.com
  train_ai:
    stance: conditional
    text: AI training on this site requires a separate licence.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Cork & Curve
provenance_date: '2026-11-09'
provider_name: Cork & Curve
provider_slug: corkandcurve-com
slug: corkandcurve-com-ai-preferences
source_date: '2026-11-09'
source_filename: corkandcurve-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://corkandcurve.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Cork & Curve\naid: corkandcurve-com\nurl: https://corkandcurve.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: AI training on this site requires a separate licence.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: We block crawlers that misbehave.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://corkandcurve.com/llms.txt\n  x-probed:\
  \ https://corkandcurve.com\n"
source_yaml_url: https://artifacts.apis.io/corkandcurve-com/ai-preferences/corkandcurve-com-ai-preferences.yml
stated_fields:
- train_ai
- agent_actions
summary_line: 2 quoted statements, read from Cork & Curve's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wine
- Travel
- Travel Guides
- Publishing
- Food and Drink
- MCP
---
