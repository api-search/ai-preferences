---
claim_count: 6
description: ''
doc:
  agent_actions:
    stance: conditional
    text: Any action taken through a Connected Assistant on your account — including creating, running, or modifying Workflows, uploading or generating content, incurring usage or charges, or invoking any AI model — is deemed to be your own action for all purposes under this Agreement
  agent_onboarding:
    stance: conditional
    text: that you have connected to your account via the Model Context Protocol (MCP) or a similar integration
  agent_purchases:
    stance: conditional
    text: for any usage or subscription charges it incurs on your behalf
  ai_use:
    stance: allowed
    text: The Company may screen prompts, uploaded files, and generated outputs, using automated systems and service providers acting on its behalf
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://cnaps.ai/llms.txt
    x-probed: https://cnaps.ai
  train_ai:
    stance: prohibited
    text: The Company does not use customer content to train AI models.
  train_genai:
    stance: prohibited
    text: use MiniMax H3, or any of its outputs or results, to train, fine-tune, distill, or otherwise improve any other AI model (other than MiniMax H3 or its model derivatives)
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: CNAPS.AI
provenance_date: '2026-11-09'
provider_name: CNAPS.AI
provider_slug: cnaps-ai
slug: cnaps-ai-ai-preferences
source_date: '2026-11-09'
source_filename: cnaps-ai-ai-preferences.yml
source_heading: AI Preferences
source_page: https://cnaps.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CNAPS.AI\naid: cnaps-ai\nurl: https://cnaps.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ntrain_ai:\n  stance: prohibited\n  text: The Company does not use customer content to train AI models.\ntrain_genai:\n  stance: prohibited\n  text: use MiniMax H3, or any of its outputs or results, to train, fine-tune, distill, or otherwise improve any\n    other AI model (other than MiniMax H3 or its model derivatives)\nai_use:\n  stance: allowed\n  text: The Company may screen prompts, uploaded files, and generated outputs, using automated systems and service\n    providers acting on its behalf\nagent_onboarding:\n\
  \  stance: conditional\n  text: that you have connected to your account via the Model Context Protocol (MCP) or a similar integration\nagent_actions:\n  stance: conditional\n  text: Any action taken through a Connected Assistant on your account — including creating, running, or modifying\n    Workflows, uploading or generating content, incurring usage or charges, or invoking any AI model — is deemed\n    to be your own action for all purposes under this Agreement\nagent_purchases:\n  stance: conditional\n  text: for any usage or subscription charges it incurs on your behalf\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://cnaps.ai/llms.txt\n  x-probed: https://cnaps.ai\n"
source_yaml_url: https://artifacts.apis.io/cnaps-ai/ai-preferences/cnaps-ai-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
- ai_use
- agent_onboarding
- agent_actions
- agent_purchases
summary_line: 6 quoted statements, read from CNAPS.AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Workflow Automation
- No-Code
- Image Generation
- Video Generation
- MCP
---
