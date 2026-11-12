---
api_specs:
- filename: codebahn-net-activitypub-api-openapi.yml
  format: yaml
  label: Codebahn Activitypub API
  slug: codebahn-net-activitypub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-activitypub-api-openapi.yml
- filename: codebahn-net-admin-api-openapi.yml
  format: yaml
  label: Codebahn Admin API
  slug: codebahn-net-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-admin-api-openapi.yml
- filename: codebahn-net-issue-api-openapi.yml
  format: yaml
  label: Codebahn Issue API
  slug: codebahn-net-issue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-issue-api-openapi.yml
- filename: codebahn-net-miscellaneous-api-openapi.yml
  format: yaml
  label: Codebahn Miscellaneous API
  slug: codebahn-net-miscellaneous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-miscellaneous-api-openapi.yml
- filename: codebahn-net-notification-api-openapi.yml
  format: yaml
  label: Codebahn Notification API
  slug: codebahn-net-notification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-notification-api-openapi.yml
- filename: codebahn-net-organization-api-openapi.yml
  format: yaml
  label: Codebahn Organization API
  slug: codebahn-net-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-organization-api-openapi.yml
- filename: codebahn-net-package-api-openapi.yml
  format: yaml
  label: Codebahn Package API
  slug: codebahn-net-package-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-package-api-openapi.yml
- filename: codebahn-net-repository-api-openapi.yml
  format: yaml
  label: Codebahn Repository API
  slug: codebahn-net-repository-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-repository-api-openapi.yml
- filename: codebahn-net-settings-api-openapi.yml
  format: yaml
  label: Codebahn Settings API
  slug: codebahn-net-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-settings-api-openapi.yml
- filename: codebahn-net-user-api-openapi.yml
  format: yaml
  label: Codebahn User API
  slug: codebahn-net-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-user-api-openapi.yml
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: unstated
    text: null
  agent_onboarding:
    stance: conditional
    text: Circumvent resource limits through automated account creation or other means.
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: unstated
    text: null
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: true
    llms_txt_url: https://codebahn.net/llms.txt
    x-probed: https://codebahn.net
  train_ai:
    stance: prohibited
    text: We do not train machine learning models on Customer Data.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Codebahn
provenance_date: '2026-11-09'
provider_name: Codebahn
provider_slug: codebahn-net
slug: codebahn-net-ai-preferences
source_date: '2026-11-09'
source_filename: codebahn-net-ai-preferences.yml
source_heading: AI Preferences
source_page: https://codebahn.net/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Codebahn\naid: codebahn-net\nurl: https://codebahn.net/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not train machine learning models on Customer Data.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: conditional\n  text: Circumvent resource limits through automated account creation or other means.\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: null\n  llms_txt_url: https://codebahn.net/llms.txt\n\
  \  x-probed: https://codebahn.net\n"
source_yaml_url: https://artifacts.apis.io/codebahn-net/ai-preferences/codebahn-net-ai-preferences.yml
stated_fields:
- train_ai
- agent_onboarding
summary_line: 2 quoted statements, read from Codebahn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Git Hosting
- Source Code Management
- Continuous Integration
- Forgejo
- Developer Tools
- EU Hosted
- Data Sovereignty
- MCP
---
