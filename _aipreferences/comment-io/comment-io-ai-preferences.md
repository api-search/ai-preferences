---
api_specs:
- filename: comment-io-run-api-openapi.yml
  format: yaml
  label: Comment.io Run API
  slug: comment-io-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comment-io/openapi/comment-io-run-api-openapi.yml
claim_count: 5
description: ''
doc:
  agent_actions:
    stance: allowed
    text: An agent you approve acts with the access you gave it, and what it does is your responsibility as if you had done it.
  agent_onboarding:
    stance: conditional
    text: The Service lets you approve AI agents to act in a workspace, by SSH key, OAuth grant (for example, an MCP client such as ChatGPT or Claude) or API token.
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: conditional
    text: Some features send workspace content to an AI model provider, OpenAI or Anthropic, as our privacy policy describes.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://comment.io/llms.txt
    x-probed: https://comment.io
  train_ai:
    stance: prohibited
    text: We never use your content to train AI models or for any other secondary purpose, never sell it, and never use it for advertising.
  train_genai:
    stance: prohibited
    text: We never use your content to train AI models or for any other secondary purpose, never sell it, and never use it for advertising.
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Comment.io
provenance_date: '2026-11-09'
provider_name: Comment.io
provider_slug: comment-io
slug: comment-io-ai-preferences
source_date: '2026-11-09'
source_filename: comment-io-ai-preferences.yml
source_heading: AI Preferences
source_page: https://comment.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Comment.io\naid: comment-io\nurl: https://comment.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We never use your content to train AI models or for any other secondary purpose, never sell it, and never\n    use it for advertising.\ntrain_genai:\n  stance: prohibited\n  text: We never use your content to train AI models or for any other secondary purpose, never sell it, and never\n    use it for advertising.\nai_use:\n  stance: conditional\n  text: Some features send workspace content to an AI model provider, OpenAI or Anthropic, as our privacy policy\n    describes.\nagent_onboarding:\n\
  \  stance: conditional\n  text: The Service lets you approve AI agents to act in a workspace, by SSH key, OAuth grant (for example, an MCP\n    client such as ChatGPT or Claude) or API token.\nagent_actions:\n  stance: allowed\n  text: An agent you approve acts with the access you gave it, and what it does is your responsibility as if you\n    had done it.\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://comment.io/llms.txt\n  x-probed: https://comment.io\n"
source_yaml_url: https://artifacts.apis.io/comment-io/ai-preferences/comment-io-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
- ai_use
- agent_onboarding
- agent_actions
summary_line: 5 quoted statements, read from Comment.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Collaboration
- Documents
- Markdown
- MCP
- Knowledge Management
- Workspace
---
