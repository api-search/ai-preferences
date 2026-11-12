---
claim_count: 4
description: ''
doc:
  agent_actions:
    stance: conditional
    text: through which a third-party AI assistant acts on your Clueso workspace at your direction
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: your audio, video, transcripts and related Content are transmitted to AI sub-processors to deliver the AI-powered features you request
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://www.clueso.io/llms.txt
    x-probed: https://www.clueso.io
  train_ai:
    stance: prohibited
    text: Clueso does not use your Content to train generalised AI models
  train_genai:
    stance: prohibited
    text: Clueso does not use your Content to train generalised AI models
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Clueso
provenance_date: '2026-11-09'
provider_name: Clueso
provider_slug: clueso-io
slug: clueso-io-ai-preferences
source_date: '2026-11-09'
source_filename: clueso-io-ai-preferences.yml
source_heading: AI Preferences
source_page: https://www.clueso.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Clueso\naid: clueso-io\nurl: https://www.clueso.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: Clueso does not use your Content to train generalised AI models\ntrain_genai:\n  stance: prohibited\n  text: Clueso does not use your Content to train generalised AI models\nai_use:\n  stance: allowed\n  text: your audio, video, transcripts and related Content are transmitted to AI sub-processors to deliver the AI-powered\n    features you request\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: through which a third-party AI\
  \ assistant acts on your Clueso workspace at your direction\nagent_purchases:\n  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://www.clueso.io/llms.txt\n  x-probed: https://www.clueso.io\n"
source_yaml_url: https://artifacts.apis.io/clueso-io/ai-preferences/clueso-io-ai-preferences.yml
stated_fields:
- train_ai
- train_genai
- ai_use
- agent_actions
summary_line: 4 quoted statements, read from Clueso's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Video
- Documentation
- Screen Recording
- Video Creation
- Knowledge Base
- Training
- MCP
---
