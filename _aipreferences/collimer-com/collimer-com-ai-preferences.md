---
claim_count: 3
description: ''
doc:
  agent_actions:
    stance: conditional
    text: Use the service to scrape, mass-extract, or otherwise overload either Collimer or third-party sites.
  agent_onboarding:
    stance: unstated
    text: null
  agent_purchases:
    stance: unstated
    text: null
  ai_use:
    stance: allowed
    text: Read, index, and cite this site with attribution, automated agents and AI assistants included.
  signals:
    ai_txt_url: null
    aipref_header: false
    content_signals: false
    llms_txt_url: https://collimer.com/llms.txt
    x-probed: https://collimer.com
  train_ai:
    stance: prohibited
    text: We do not use your submitted content to train AI models, neither ours nor third parties’.
  train_genai:
    stance: unstated
    text: null
layer: ai_preferences
layer_version: 0.1.0
layout: ai-preferences
method: harvested
model: claude-haiku-5-5
name: Collimer
provenance_date: '2026-11-09'
provider_name: Collimer
provider_slug: collimer-com
slug: collimer-com-ai-preferences
source_date: '2026-11-09'
source_filename: collimer-com-ai-preferences.yml
source_heading: AI Preferences
source_page: https://collimer.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nai_preferences: 0.1.0\nprovider: Collimer\naid: collimer-com\nurl: https://collimer.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrain_ai:\n  stance: prohibited\n  text: We do not use your submitted content to train AI models, neither ours nor third parties’.\ntrain_genai:\n  stance: unstated\n  text: null\nai_use:\n  stance: allowed\n  text: Read, index, and cite this site with attribution, automated agents and AI assistants included.\nagent_onboarding:\n  stance: unstated\n  text: null\nagent_actions:\n  stance: conditional\n  text: Use the service to scrape, mass-extract, or otherwise overload either Collimer or third-party sites.\nagent_purchases:\n\
  \  stance: unstated\n  text: null\nsignals:\n  aipref_header: false\n  content_signals: false\n  ai_txt_url: null\n  llms_txt_url: https://collimer.com/llms.txt\n  x-probed: https://collimer.com\n"
source_yaml_url: https://artifacts.apis.io/collimer-com/ai-preferences/collimer-com-ai-preferences.yml
stated_fields:
- train_ai
- ai_use
- agent_actions
summary_line: 3 quoted statements, read from Collimer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Visibility
- Generative Engine Optimization
- SEO
- Marketing
- Analytics
- AI Search
---
