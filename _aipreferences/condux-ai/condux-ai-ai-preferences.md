---
api_specs:
- filename: condux-ai-admin-api-openapi.yml
  format: yaml
  label: Condux Admin API
  slug: condux-ai-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-admin-api-openapi.yml
- filename: condux-ai-alerts-api-openapi.yml
  format: yaml
  label: Condux Alerts API
  slug: condux-ai-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-alerts-api-openapi.yml
- filename: condux-ai-auth-api-openapi.yml
  format: yaml
  label: Condux Auth API
  slug: condux-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-auth-api-openapi.yml
- filename: condux-ai-billing-api-openapi.yml
  format: yaml
  label: Condux Billing API
  slug: condux-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-billing-api-openapi.yml
- filename: condux-ai-conductor-api-openapi.yml
  format: yaml
  label: Condux Conductor API
  slug: condux-ai-conductor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-conductor-api-openapi.yml
- filename: condux-ai-debugfiles-api-openapi.yml
  format: yaml
  label: Condux Debug Files API
  slug: condux-ai-debugfiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-debugfiles-api-openapi.yml
- filename: condux-ai-github-api-openapi.yml
  format: yaml
  label: Condux GitHub API
  slug: condux-ai-github-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-github-api-openapi.yml
- filename: condux-ai-invites-api-openapi.yml
  format: yaml
  label: Condux Invites API
  slug: condux-ai-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-invites-api-openapi.yml
- filename: condux-ai-issues-api-openapi.yml
  format: yaml
  label: Condux Issues API
  slug: condux-ai-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-issues-api-openapi.yml
- filename: condux-ai-linear-api-openapi.yml
  format: yaml
  label: Condux Linear API
  slug: condux-ai-linear-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-linear-api-openapi.yml
- filename: condux-ai-mcptokens-api-openapi.yml
  format: yaml
  label: Condux MCP Tokens API
  slug: condux-ai-mcptokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-mcptokens-api-openapi.yml
- filename: condux-ai-members-api-openapi.yml
  format: yaml
  label: Condux Members API
  slug: condux-ai-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-members-api-openapi.yml
- filename: condux-ai-notifications-api-openapi.yml
  format: yaml
  label: Condux Notifications API
  slug: condux-ai-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-notifications-api-openapi.yml
- filename: condux-ai-onboarding-api-openapi.yml
  format: yaml
  label: Condux Onboarding API
  slug: condux-ai-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-onboarding-api-openapi.yml
- filename: condux-ai-provisioning-api-openapi.yml
  format: yaml
  label: Condux Provisioning API
  slug: condux-ai-provisioning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-provisioning-api-openapi.yml
- filename: condux-ai-releasetokens-api-openapi.yml
  format: yaml
  label: Condux Release Tokens API
  slug: condux-ai-releasetokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-releasetokens-api-openapi.yml
- filename: condux-ai-repos-api-openapi.yml
  format: yaml
  label: Condux Repos API
  slug: condux-ai-repos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-repos-api-openapi.yml
- filename: condux-ai-runnertokens-api-openapi.yml
  format: yaml
  label: Condux Runner Tokens API
  slug: condux-ai-runnertokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-runnertokens-api-openapi.yml
- filename: condux-ai-sourcemaps-api-openapi.yml
  format: yaml
  label: Condux Source Maps API
  slug: condux-ai-sourcemaps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-sourcemaps-api-openapi.yml
- filename: condux-ai-weeklysummary-api-openapi.yml
  format: yaml
  label: Condux Weekly Summary API
  slug: condux-ai-weeklysummary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/condux-ai/openapi/condux-ai-weeklysummary-api-openapi.yml
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: conditional
    text: It only ever opens a draft pull request. It does not merge, it does not push to your default branch, and there is no setting that changes this.
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
    llms_txt_url: https://condux.ai/llms.txt
    x-probed: https://condux.ai
  train_ai:
    stance: prohibited
    text: We do not use your data to train models, and we do not share it with anyone except the subprocessors listed on our trust page.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Condux
provenance_date: '2026-11-09'
provider_name: Condux
provider_slug: condux-ai
slug: condux-ai-ai-preferences
source_date: '2026-11-09'
source_filename: condux-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://condux.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Condux\naid: condux-ai\nurl: https://condux.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not use your data to train models, and we do not share it with anyone except the subprocessors listed\n    on our trust page.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: It only ever opens a draft pull request. It does not merge, it does not push to your default branch, and\n    there is no setting that changes this.\nagent_purchases:\n\
  \  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://condux.ai/llms.txt\n  x-probed: https://condux.ai\n"
source_yaml_url: https://artifacts.apis.io/condux-ai/ai-preferences/condux-ai-ai-preferences.yml
stated_fields:
- train_ai
- agent_actions
summary_line: 2 quoted statements, read from Condux's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Error Monitoring
- Observability
- AI
- Developer Tools
- OpenTelemetry
- MCP
- Self-Hosted
---
