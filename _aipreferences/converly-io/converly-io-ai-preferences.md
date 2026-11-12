---
api_specs:
- filename: converly-io-action-types-api-openapi.yml
  format: yaml
  label: Converly Action Types API
  slug: converly-io-action-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-action-types-api-openapi.yml
- filename: converly-io-billing-api-openapi.yml
  format: yaml
  label: Converly Billing API
  slug: converly-io-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-billing-api-openapi.yml
- filename: converly-io-destination-types-api-openapi.yml
  format: yaml
  label: Converly Destination Types API
  slug: converly-io-destination-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-destination-types-api-openapi.yml
- filename: converly-io-destinations-api-openapi.yml
  format: yaml
  label: Converly Destinations API
  slug: converly-io-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-destinations-api-openapi.yml
- filename: converly-io-events-api-openapi.yml
  format: yaml
  label: Converly Events API
  slug: converly-io-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-events-api-openapi.yml
- filename: converly-io-flows-api-openapi.yml
  format: yaml
  label: Converly Flows API
  slug: converly-io-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-flows-api-openapi.yml
- filename: converly-io-handoffs-api-openapi.yml
  format: yaml
  label: Converly Handoffs API
  slug: converly-io-handoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-handoffs-api-openapi.yml
- filename: converly-io-invoices-api-openapi.yml
  format: yaml
  label: Converly Invoices API
  slug: converly-io-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-invoices-api-openapi.yml
- filename: converly-io-plans-api-openapi.yml
  format: yaml
  label: Converly Plans API
  slug: converly-io-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-plans-api-openapi.yml
- filename: converly-io-signup-api-openapi.yml
  format: yaml
  label: Converly Signup API
  slug: converly-io-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-signup-api-openapi.yml
- filename: converly-io-site-integrations-api-openapi.yml
  format: yaml
  label: Converly Site Integrations API
  slug: converly-io-site-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-site-integrations-api-openapi.yml
- filename: converly-io-sites-api-openapi.yml
  format: yaml
  label: Converly Sites API
  slug: converly-io-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-sites-api-openapi.yml
- filename: converly-io-subscription-api-openapi.yml
  format: yaml
  label: Converly Subscription API
  slug: converly-io-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-subscription-api-openapi.yml
- filename: converly-io-test-event-api-openapi.yml
  format: yaml
  label: Converly Test Event API
  slug: converly-io-test-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-test-event-api-openapi.yml
- filename: converly-io-trigger-types-api-openapi.yml
  format: yaml
  label: Converly Trigger Types API
  slug: converly-io-trigger-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-trigger-types-api-openapi.yml
- filename: converly-io-usage-api-openapi.yml
  format: yaml
  label: Converly Usage API
  slug: converly-io-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-usage-api-openapi.yml
claim_count: 1
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: use any automated process or service (such as a bot, a spider, or periodic caching of information stored by Converly) to access or use the Services;
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
    llms_txt_url: https://converly.io/llms.txt
    x-probed: https://converly.io
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
name: Converly
provenance_date: '2026-11-09'
provider_name: Converly
provider_slug: converly-io
slug: converly-io-ai-preferences
source_date: '2026-11-09'
source_filename: converly-io-ai-preferences.yml
source_heading: AI Preferences
source_page: https://converly.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Converly\naid: converly-io\nurl: https://converly.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: use any automated process or service (such as a bot, a spider, or periodic caching of information stored\n    by Converly) to access or use the Services;\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url:\
  \ https://converly.io/llms.txt\n  x-probed: https://converly.io\n"
source_yaml_url: https://artifacts.apis.io/converly-io/ai-preferences/converly-io-ai-preferences.yml
stated_fields:
- agent_actions
summary_line: 1 quoted statement, read from Converly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Conversion Tracking
- Marketing
- Advertising
- Analytics
- MCP
- REST API
---
