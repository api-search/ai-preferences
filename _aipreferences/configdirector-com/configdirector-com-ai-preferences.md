---
api_specs:
- filename: configdirector-com-api-tokens-api-openapi.yml
  format: yaml
  label: ConfigDirector API tokens API
  slug: configdirector-com-api-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-api-tokens-api-openapi.yml
- filename: configdirector-com-configs-api-openapi.yml
  format: yaml
  label: ConfigDirector Configs API
  slug: configdirector-com-configs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-configs-api-openapi.yml
- filename: configdirector-com-discovery-api-openapi.yml
  format: yaml
  label: ConfigDirector Discovery API
  slug: configdirector-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-discovery-api-openapi.yml
- filename: configdirector-com-documentation-api-openapi.yml
  format: yaml
  label: ConfigDirector Documentation API
  slug: configdirector-com-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-documentation-api-openapi.yml
- filename: configdirector-com-environments-api-openapi.yml
  format: yaml
  label: ConfigDirector Environments API
  slug: configdirector-com-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-environments-api-openapi.yml
- filename: configdirector-com-projects-api-openapi.yml
  format: yaml
  label: ConfigDirector Projects API
  slug: configdirector-com-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-projects-api-openapi.yml
- filename: configdirector-com-scanned-repositories-api-openapi.yml
  format: yaml
  label: ConfigDirector Scanned repositories API
  slug: configdirector-com-scanned-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-scanned-repositories-api-openapi.yml
- filename: configdirector-com-segments-api-openapi.yml
  format: yaml
  label: ConfigDirector Segments API
  slug: configdirector-com-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-segments-api-openapi.yml
- filename: configdirector-com-tags-api-openapi.yml
  format: yaml
  label: ConfigDirector Tags API
  slug: configdirector-com-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-tags-api-openapi.yml
- filename: configdirector-com-webhooks-api-openapi.yml
  format: yaml
  label: ConfigDirector Webhooks API
  slug: configdirector-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: use, launch, develop, or distribute any automated system, including without limitation, any spider, robot, cheat utility, scraper, or offline reader that accesses the Services
  agent_onboarding:
    stance: prohibited
    text: creating user accounts by automated means or under false pretenses
  agent_purchases:
    stance: prohibited
    text: Use a buying agent or purchasing agent to make purchases on the Services.
  ai_use:
    stance: unstated
    text: null
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://www.configdirector.com/llms.txt
    x-probed: https://www.configdirector.com
  train_ai:
    stance: prohibited
    text: We do not use snippets to train machine learning or artificial intelligence models, and we do not use them as examples in our products, documentation, or marketing.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: ConfigDirector
provenance_date: '2026-11-09'
provider_name: ConfigDirector
provider_slug: configdirector-com
slug: configdirector-com-ai-preferences
source_date: '2026-11-09'
source_filename: configdirector-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.configdirector.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: ConfigDirector\naid: configdirector-com\nurl: https://www.configdirector.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not use snippets to train machine learning or artificial intelligence models, and we do not use them\n    as examples in our products, documentation, or marketing.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: prohibited\n  text: creating user accounts by automated means or under false pretenses\nagent_actions:\n  stance: prohibited\n  text: use, launch, develop, or distribute\
  \ any automated system, including without limitation, any spider, robot,\n    cheat utility, scraper, or offline reader that accesses the Services\nagent_purchases:\n  stance: prohibited\n  text: Use a buying agent or purchasing agent to make purchases on the Services.\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://www.configdirector.com/llms.txt\n  x-probed: https://www.configdirector.com\n"
source_yaml_url: https://artifacts.apis.io/configdirector-com/ai-preferences/configdirector-com-ai-preferences.yml
stated_fields:
- train_ai
- agent_onboarding
- agent_actions
- agent_purchases
summary_line: 4 quoted statements, read from ConfigDirector's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Feature Flags
- Remote Configuration
- Configuration Management
- Developer Tools
- OpenFeature
- SDKs
- MCP
---
