---
api_specs:
- filename: codequiry-com-auth-api-openapi.yml
  format: yaml
  label: Codequiry Auth API
  slug: codequiry-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-auth-api-openapi.yml
- filename: codequiry-com-checks-api-openapi.yml
  format: yaml
  label: Codequiry Checks API
  slug: codequiry-com-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-checks-api-openapi.yml
- filename: codequiry-com-reference-api-openapi.yml
  format: yaml
  label: Codequiry Reference API
  slug: codequiry-com-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-reference-api-openapi.yml
- filename: codequiry-com-results-api-openapi.yml
  format: yaml
  label: Codequiry Results API
  slug: codequiry-com-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-results-api-openapi.yml
- filename: codequiry-com-run-api-openapi.yml
  format: yaml
  label: Codequiry Run API
  slug: codequiry-com-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-run-api-openapi.yml
- filename: codequiry-com-submissions-api-openapi.yml
  format: yaml
  label: Codequiry Submissions API
  slug: codequiry-com-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-submissions-api-openapi.yml
claim_count: 2
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: use any robot, script or automated tool except our published API within its limits
  agent_onboarding:
    stance: prohibited
    text: create accounts by automated means
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
    llms_txt_url: https://codequiry.com/llms.txt
    x-probed: https://codequiry.com
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
name: Codequiry
provenance_date: '2026-11-09'
provider_name: Codequiry
provider_slug: codequiry-com
slug: codequiry-com-ai-preferences
source_date: '2026-11-09'
source_filename: codequiry-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://codequiry.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Codequiry\naid: codequiry-com\nurl: https://codequiry.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: prohibited\n  text: create accounts by automated means\nagent_actions:\n  stance: prohibited\n  text: use any robot, script or automated tool except our published API within its limits\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url:\
  \ https://codequiry.com/llms.txt\n  x-probed: https://codequiry.com\n"
source_yaml_url: https://artifacts.apis.io/codequiry-com/ai-preferences/codequiry-com-ai-preferences.yml
stated_fields:
- agent_onboarding
- agent_actions
summary_line: 2 quoted statements, read from Codequiry's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Code Plagiarism
- AI Code Detection
- Education
- Source Code Analysis
- Academic Integrity
- MCP
---
