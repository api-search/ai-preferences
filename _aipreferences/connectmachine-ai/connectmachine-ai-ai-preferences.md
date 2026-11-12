---
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: prohibited
    text: use any robot, spider, crawler, scraper or other automated means or interface not provided by us to access the Services or to extract or export data collected using the Services
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
    llms_txt_url: https://www.connectmachine.ai/llms.txt
    x-probed: https://www.connectmachine.ai
  train_ai:
    stance: conditional
    text: ConnectMachine may use Inputs and Outputs to train or otherwise improve the AI Services, but only if such Inputs and Outputs have been (a) de-identified so that they do not identify Customer, its Authorized Users or any other person and (b) aggregated with data across other customers.
  train_genai:
    stance: conditional
    text: '"AI Services" means large language models (LLMs) or other machine learning or artificial intelligence features of the Services.'
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: ConnectMachine
provenance_date: '2026-11-09'
provider_name: ConnectMachine
provider_slug: connectmachine-ai
slug: connectmachine-ai-ai-preferences
source_date: '2026-11-09'
source_filename: connectmachine-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.connectmachine.ai/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: ConnectMachine\naid: connectmachine-ai\nurl: https://www.connectmachine.ai/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: conditional\n  text: ConnectMachine may use Inputs and Outputs to train or otherwise improve the AI Services, but only if such\n    Inputs and Outputs have been (a) de-identified so that they do not identify Customer, its Authorized Users or\n    any other person and (b) aggregated with data across other customers.\ntrain_genai:\n  stance: conditional\n  text: '\"AI Services\" means large language models (LLMs) or other machine learning or artificial intelligence\
  \ features\n    of the Services.'\nai_use:\n  stance: unstated\n  text: null\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: prohibited\n  text: use any robot, spider, crawler, scraper or other automated means or interface not provided by us to access\n    the Services or to extract or export data collected using the Services\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://www.connectmachine.ai/llms.txt\n  x-probed: https://www.connectmachine.ai\n"
source_yaml_url: https://artifacts.apis.io/connectmachine-ai/ai-preferences/connectmachine-ai-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
- agent_actions
summary_line: 3 quoted statements, read from ConnectMachine's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Business Cards
- Contact Management
- Business Card Scanner
- Networking
- Artificial Intelligence
- MCP
- CRM
---
