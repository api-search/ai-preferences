---
api_specs:
- filename: clstr-news-openapi-generated.yml
  format: yaml
  label: CLSTR API
  slug: clstr-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clstr-news/openapi/_ae-authored/clstr-news-openapi-generated.yml
claim_count: 4
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: (a) scrape, crawl, or bulk-extract content from the service;
  agent_onboarding:
    stance: prohibited
    text: (e) use automated systems to create accounts or generate traffic.
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: Giving the output to an AI agent or assistant as context while it answers a request is fine.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: true
    llms_txt_url: https://clstr.news/llms.txt
    x-probed: https://clstr.news
  train_ai:
    stance: prohibited
    text: use it to train or fine-tune machine learning models
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: CLSTR
provenance_date: '2026-11-09'
provider_name: CLSTR
provider_slug: clstr-news
slug: clstr-news-ai-preferences
source_date: '2026-11-09'
source_filename: clstr-news-ai-preferences.yml
source_heading: AI Preferences
source_page: https://clstr.news/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CLSTR\naid: clstr-news\nurl: https://clstr.news/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: use it to train or fine-tune machine learning models\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: Giving the output to an AI agent or assistant as context while it answers a request is fine.\nagent_onboarding:\n  stance: prohibited\n  text: (e) use automated systems to create accounts or generate traffic.\nagent_actions:\n  stance: prohibited\n  text: (a) scrape, crawl, or bulk-extract content from the service;\nagent_purchases:\n  stance: unstated\n\
  \  text: null\nsignals:\n  aipref_header: false\n  content_signals: true\n  ai_txt_url: null\n  llms_txt_url: https://clstr.news/llms.txt\n  x-probed: https://clstr.news\n"
source_yaml_url: https://artifacts.apis.io/clstr-news/ai-preferences/clstr-news-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_onboarding
- agent_actions
summary_line: 4 quoted statements, read from CLSTR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- News
- News API
- MCP
- AI Agents
- News Clustering
- Media Monitoring
- Summarization
---
