---
api_specs:
- filename: corvio-ai-agent-collaboration-api-openapi.yml
  format: yaml
  label: Corvio Agent collaboration API
  slug: corvio-ai-agent-collaboration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-agent-collaboration-api-openapi.yml
- filename: corvio-ai-public-api-v1-api-openapi.yml
  format: yaml
  label: Corvio Public API v1 API
  slug: corvio-ai-public-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-public-api-v1-api-openapi.yml
- filename: corvio-ai-public-api-v1-files-api-openapi.yml
  format: yaml
  label: Corvio Public API v1 - Files API
  slug: corvio-ai-public-api-v1-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-public-api-v1-files-api-openapi.yml
- filename: corvio-ai-public-api-v1-local-markdown-sync-api-openapi.yml
  format: yaml
  label: Corvio Public API v1 - Local Markdown Sync API
  slug: corvio-ai-public-api-v1-local-markdown-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-public-api-v1-local-markdown-sync-api-openapi.yml
- filename: corvio-ai-public-api-v1-source-publication-api-openapi.yml
  format: yaml
  label: Corvio Public API v1 - Source publication API
  slug: corvio-ai-public-api-v1-source-publication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-public-api-v1-source-publication-api-openapi.yml
claim_count: 2
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
    stance: unstated
    text: null
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://corvio.ai/llms.txt
    x-probed: https://corvio.ai
  train_ai:
    stance: conditional
    text: We do not use Customer Content to train public or shared foundation models, and we require AI inference providers not to train their foundation models on Corvio inputs or outputs.
  train_genai:
    stance: conditional
    text: We do not use Customer Content to train public or shared foundation models, and we require AI inference providers not to train their foundation models on Corvio inputs or outputs.
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Corvio
provenance_date: '2026-11-09'
provider_name: Corvio
provider_slug: corvio-ai
slug: corvio-ai-ai-preferences
source_date: '2026-11-09'
source_filename: corvio-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://corvio.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Corvio\naid: corvio-ai\nurl: https://corvio.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: We do not use Customer Content to train public or shared foundation models, and we require AI inference\n    providers not to train their foundation models on Corvio inputs or outputs.\ntrain_genai:\n  stance: conditional\n  text: We do not use Customer Content to train public or shared foundation models, and we require AI inference\n    providers not to train their foundation models on Corvio inputs or outputs.\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n\
  \  text: null\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://corvio.ai/llms.txt\n  x-probed: https://corvio.ai\n"
source_yaml_url: https://artifacts.apis.io/corvio-ai/ai-preferences/corvio-ai-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
summary_line: 2 quoted statements, read from Corvio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Notes
- Knowledge Management
- Workspace
- AI Agents
- MCP
- Developer API
- CLI
---
