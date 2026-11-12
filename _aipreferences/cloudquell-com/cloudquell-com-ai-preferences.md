---
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
    stance: allowed
    text: The Service includes features that use generative AI (for example, the "Explain with AI" buttons and the website chat widget).
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://cloudquell.com/llms.txt
    x-probed: https://cloudquell.com
  train_ai:
    stance: unstated
    text: null
  train_genai:
    stance: prohibited
    text: CloudQuell does not use Customer Data to train generative AI models
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: CloudQuell
provenance_date: '2026-11-09'
provider_name: CloudQuell
provider_slug: cloudquell-com
slug: cloudquell-com-ai-preferences
source_date: '2026-11-09'
source_filename: cloudquell-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.cloudquell.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: CloudQuell\naid: cloudquell-com\nurl: https://www.cloudquell.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: unstated\n  text: null\ntrain_genai:\n  stance: prohibited\n  text: CloudQuell does not use Customer Data to train generative AI models\nai_use:\n  stance: allowed\n  text: The Service includes features that use generative AI (for example, the \"Explain with AI\" buttons and the\n    website chat widget).\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: unstated\n  text: null\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n\
  \  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://cloudquell.com/llms.txt\n  x-probed: https://cloudquell.com\n"
source_yaml_url: https://artifacts.apis.io/cloudquell-com/ai-preferences/cloudquell-com-ai-preferences.yml
stated_fields:
- train_genai
- ai_use
summary_line: 2 quoted statements, read from CloudQuell's own page on 2026-11-09.
synthetic: false
tags:
- Company
- FinOps
- Cloud Cost Management
- AI Cost Management
- Cost Allocation
- Anomaly Detection
- Multi-Cloud
- MCP
---
