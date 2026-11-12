---
api_specs:
- filename: commareports-com-account-api-openapi.yml
  format: yaml
  label: Comma Account API
  slug: commareports-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-account-api-openapi.yml
- filename: commareports-com-assets-api-openapi.yml
  format: yaml
  label: Comma Assets API
  slug: commareports-com-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-assets-api-openapi.yml
- filename: commareports-com-comments-api-openapi.yml
  format: yaml
  label: Comma Comments API
  slug: commareports-com-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-comments-api-openapi.yml
- filename: commareports-com-connectors-api-openapi.yml
  format: yaml
  label: Comma Connectors API
  slug: commareports-com-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-connectors-api-openapi.yml
- filename: commareports-com-meta-api-openapi.yml
  format: yaml
  label: Comma Meta API
  slug: commareports-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-meta-api-openapi.yml
- filename: commareports-com-notifications-api-openapi.yml
  format: yaml
  label: Comma Notifications API
  slug: commareports-com-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-notifications-api-openapi.yml
- filename: commareports-com-reports-api-openapi.yml
  format: yaml
  label: Comma Reports API
  slug: commareports-com-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-reports-api-openapi.yml
- filename: commareports-com-reviewers-api-openapi.yml
  format: yaml
  label: Comma Reviewers API
  slug: commareports-com-reviewers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-reviewers-api-openapi.yml
- filename: commareports-com-reviews-api-openapi.yml
  format: yaml
  label: Comma Reviews API
  slug: commareports-com-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-reviews-api-openapi.yml
- filename: commareports-com-revisions-api-openapi.yml
  format: yaml
  label: Comma Revisions API
  slug: commareports-com-revisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-revisions-api-openapi.yml
- filename: commareports-com-routines-api-openapi.yml
  format: yaml
  label: Comma Routines API
  slug: commareports-com-routines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-routines-api-openapi.yml
- filename: commareports-com-sharing-api-openapi.yml
  format: yaml
  label: Comma Sharing API
  slug: commareports-com-sharing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-sharing-api-openapi.yml
- filename: commareports-com-skills-api-openapi.yml
  format: yaml
  label: Comma Skills API
  slug: commareports-com-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-skills-api-openapi.yml
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: unstated
    text: null
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: Reports may be produced by an automated agent powered by Anthropic Claude models running on AWS Bedrock.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://commareports.com/llms.txt
    x-probed: https://commareports.com
  train_ai:
    stance: prohibited
    text: We do not train any model on your data.
  train_genai:
    stance: prohibited
    text: We do not train any model on your data.
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Comma
provenance_date: '2026-11-09'
provider_name: Comma
provider_slug: commareports-com
slug: commareports-com-ai-preferences
source_date: '2026-11-09'
source_filename: commareports-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://commareports.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Comma\naid: commareports-com\nurl: https://commareports.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not train any model on your data.\ntrain_genai:\n  stance: prohibited\n  text: We do not train any model on your data.\nai_use:\n  stance: allowed\n  text: Reports may be produced by an automated agent powered by Anthropic Claude models running on AWS Bedrock.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n\
  \  ai_txt_url: null\n  llms_txt_url: https://commareports.com/llms.txt\n  x-probed: https://commareports.com\n"
source_yaml_url: https://artifacts.apis.io/commareports-com/ai-preferences/commareports-com-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
- ai_use
summary_line: 3 quoted statements, read from Comma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Reports
- Collaboration
- Comments
- HTML
- MCP
- AI Agents
- Data Visualization
---
