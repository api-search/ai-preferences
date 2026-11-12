---
api_specs:
- filename: coudrebros-eu-auth-api-openapi.yml
  format: yaml
  label: Coudre Bros. Auth API
  slug: coudrebros-eu-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-auth-api-openapi.yml
- filename: coudrebros-eu-health-api-openapi.yml
  format: yaml
  label: Coudre Bros. Health API
  slug: coudrebros-eu-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-health-api-openapi.yml
- filename: coudrebros-eu-mint-api-openapi.yml
  format: yaml
  label: Coudre Bros. Mint API
  slug: coudrebros-eu-mint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-mint-api-openapi.yml
- filename: coudrebros-eu-notary-api-openapi.yml
  format: yaml
  label: Coudre Bros. Notary API
  slug: coudrebros-eu-notary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-notary-api-openapi.yml
- filename: coudrebros-eu-payment-api-openapi.yml
  format: yaml
  label: Coudre Bros. Payment API
  slug: coudrebros-eu-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-payment-api-openapi.yml
- filename: coudrebros-eu-prerequisites-api-openapi.yml
  format: yaml
  label: Coudre Bros. Prerequisites API
  slug: coudrebros-eu-prerequisites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-prerequisites-api-openapi.yml
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: allowed
    text: This page is a human-friendly form on top of the same public NFT Minting API used by automated/AI clients.
  agent_onboarding:
    stance: allowed
    text: Everything else -- keypair, registration, IPFS upload, minting -- the agent handles itself.
  agent_purchases:
    stance: allowed
    text: An AI agent — Claude or any other MCP client — can register, pay, and mint a Cardano NFT directly through tool calls in a conversation
  ai_use:
    stance: unstated
    text: null
  signals:
    ai_txt_url: null
    aipref_header: null
    content_signals: null
    llms_txt_url: null
    x-probed: https://www.coudrebros.eu
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
name: Coudre Bros.
provenance_date: '2026-11-09'
provider_name: Coudre Bros.
provider_slug: coudrebros-eu
slug: coudrebros-eu-ai-preferences
source_date: '2026-11-09'
source_filename: coudrebros-eu-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.coudrebros.eu/nft_api/#legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Coudre Bros.\naid: coudrebros-eu\nurl: https://www.coudrebros.eu/nft_api/#legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: allowed\n  text: Everything else -- keypair, registration, IPFS upload, minting -- the agent handles itself.\nagent_actions:\n  stance: allowed\n  text: This page is a human-friendly form on top of the same public NFT Minting API used by automated/AI clients.\nagent_purchases:\n  stance: allowed\n  text: An AI agent — Claude or any other\
  \ MCP client — can register, pay, and mint a Cardano NFT directly through\n    tool calls in a conversation\nsignals:\n  aipref_header: null\n  content_signals: null\n  ai_txt_url: null\n  llms_txt_url: null\n  x-probed: https://www.coudrebros.eu\n"
source_yaml_url: https://artifacts.apis.io/coudrebros-eu/ai-preferences/coudrebros-eu-ai-preferences.yml
stated_fields:
- agent_onboarding
- agent_actions
- agent_purchases
summary_line: 3 quoted statements, read from Coudre Bros.'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cardano
- Blockchain
- Stake Pool
- NFT
- Minting
- Notary
- AI Agents
- MCP
- Web3
---
