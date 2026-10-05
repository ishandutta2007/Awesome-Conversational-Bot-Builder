# Awesome-Conversational-Bot-Builder

# Awesome-Conversational-Bot-Builder

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Visual Flow Builders, NLU Engines & Multi-Channel Bot Development*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Conversational Bot Builders**. These tools help developers and business users design, build, and deploy intelligent chatbots and voice assistants across websites, messaging apps, and contact centers.

**Examples** include Microsoft Power Virtual Agents, Google Dialogflow, Amazon Lex, Rasa, Botpress, Voiceflow, Cognigy, Yellow.ai, Kore.ai, and Ada (the category leaders).

**Open-source emphasis**: The open-source conversational bot builder ecosystem is **mature and production-proven**. **Rasa** leads enterprise-grade frameworks with NLU and dialogue management, **Botpress** provides a visual drag-and-drop builder with managed NLU, and **Tock** offers a complete open-source conversational AI platform with multi-channel connectors . **Tiledesk** positions itself as an open-source alternative to Voiceflow, Botpress, and Landbot for multichannel workflow automation .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📖 Table of Contents

- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ☁️ SaaS/Hosted Platforms

> **📊 Market Context**: The global conversational AI market is estimated at **~$14.79B in 2025**, growing toward **~$82.46B by 2034** at a **~21% CAGR**. The sector is **moderately fragmented** — Google, Microsoft, AWS, IBM, and Cognigy are top players. **Pricing models vary dramatically**: Cognigy starts at **~$2,500/month**, Ada at **$33,000/year** for 60,000 conversations, and Kore.ai offers **5,000 free sessions** per account. No single vendor holds a winner-take-all position; enterprises typically run multi-vendor stacks.

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Microsoft Power Virtual Agents](https://powervirtualagents.microsoft.com/)** | **Microsoft's low-code bot builder within the Power Platform.** Integrated with Teams, Dynamics 365, and Azure services. | **$200/month** for 25,000 messages (tenant packs) | **Free trial**: 30-day trial with full platform access | **~$281B revenue (Microsoft FY2025)** |
| **[Google Dialogflow](https://cloud.google.com/dialogflow)** | Google's conversational AI platform with NLU, intent recognition, and entity extraction. **Dialogflow CX** for advanced flow-based design. | **Dialogflow ES**: Free tier; **$0.002 per text query** after free tier. **Dialogflow CX**: **$0.007 per text query** | **Dialogflow ES free tier**: **1,000 text queries/day**. **CX free trial**: $600 GCP credits for 90 days | **~$350B revenue (Alphabet FY2025)** |
| **[Amazon Lex](https://aws.amazon.com/lex/)** | AWS conversational AI using the same deep learning as Alexa. Intent recognition, slot filling, multi-turn dialogue. | **V2**: **$0.00075 per text request**; **$0.004 per audio request** | **AWS Free Tier**: **10,000 text requests/month** + **5,000 speech requests/month** for 12 months | **~$638B revenue (Amazon FY2025)** |
| **[Cognigy](https://www.cognigy.com/)** | Enterprise conversational AI platform with NLU, dialogue management, and omnichannel deployment. | **~$2,500/month** (starting) | **Free trial**: Full platform access, no credit card required | **Private (~$100M+ raised est.)** |
| **[Yellow.ai](https://yellow.ai/)** | Conversational AI for customer support and employee experience. NLU, voice, multi-channel. | **Premium**: Custom pricing (sales-led) | **Freemium plan**: **5,000 monthly bot conversations**, FAQ module, 2 channels | **~$102M raised, ~$1B valuation est.** |
| **[Kore.ai](https://kore.ai/)** | Enterprise conversational AI with virtual assistants, NLU, multi-channel deployment. | **Pay-as-you-go**: Reload from **$100** | **Free sessions**: **5,000 sessions** per account (up to 5 bots) | **~$150M+ raised, ~$1B valuation est.** |
| **[Ada](https://www.ada.cx/)** | Enterprise AI customer service platform. Facilitating over 4 billion automated interactions. | **Enterprise-only**. AWS Marketplace: **$33,000/year** for 60,000 conversations | **None** — no free tier or free trial | **Private (~$200M+ raised est.)** |

## 🔓 Open-Source GitHub Projects

Sorted by star count (descending). Star badge links to each repo's stargazers page.

| Repo | Description | Stars |
|---|---|---|
| **[Rasa](https://github.com/RasaHQ/rasa)** — **The leading open-source conversational AI framework for enterprise.** NLU pipelines, dialogue management, custom Python actions, multi-channel (Slack, Telegram, Messenger, Twilio). Used by millions of developers, from small teams through enterprise-wide applications . Apache-2.0. | [![Stars](https://img.shields.io/github/stars/RasaHQ/rasa?style=social&color=white)](https://github.com/RasaHQ/rasa/stargazers) | ~19,000 |
| **[Botpress](https://github.com/botpress/botpress)** — **First open-source framework for AI digital assistants.** Visual drag-and-drop builder, managed NLU, multi-lingual support, HITL handoff. Lightweight with zero external dependencies, deploy anywhere . AGPLv3. | [![Stars](https://img.shields.io/github/stars/botpress/botpress?style=social&color=white)](https://github.com/botpress/botpress/stargazers) | ~13,500 |
| **[Tock](https://github.com/theopenconversationkit/tock)** — **Open-source conversational AI toolkit.** Complete platform with Tock Studio UI for building stories and analytics, Conversational DSL for Kotlin/Node.js/Python/REST API, built-in connectors for Messenger, WhatsApp, Google Assistant, Alexa, Twitter, and more. Deploy anywhere in cloud or on-premise with Docker . | [![Stars](https://img.shields.io/github/stars/theopenconversationkit/tock?style=social&color=white)](https://github.com/theopenconversationkit/tock/stargazers) | ~484 |
| **[Tiledesk Chatbot Engine](https://github.com/Tiledesk/tiledesk-chatbot)** — **Open-source alternative to Voiceflow, Botpress, and Landbot.** Node.js-based framework for multichannel workflow automation. Works with Tiledesk Design Studio for visual chatbot design. MIT licensed . | [![Stars](https://img.shields.io/github/stars/Tiledesk/tiledesk-chatbot?style=social&color=white)](https://github.com/Tiledesk/tiledesk-chatbot/stargazers) | ~37 |
| **[Botkit](https://github.com/howdyai/botkit)** — **Open-source developer tool for building chat bots and custom integrations.** `hears()`, `ask()`, `reply()` event handlers, middleware, platform adapters for Microsoft Bot Framework, Slack, Facebook Messenger, Telegram, Webex. Part of the Microsoft Bot Framework . MIT. | [![Stars](https://img.shields.io/github/stars/howdyai/botkit?style=social&color=white)](https://github.com/howdyai/botkit/stargazers) | ~11,200 |
| **[BotMan](https://github.com/botman/botman)** — **The most popular open-source PHP chatbot framework.** Framework-agnostic (Laravel, Symfony), write once deploy everywhere (Slack, Telegram, Messenger, WeChat, Alexa). MIT . | [![Stars](https://img.shields.io/github/stars/botman/botman?style=social&color=white)](https://github.com/botman/botman/stargazers) | ~5,800 |
| **[Kairon](https://github.com/digiteinfotech/kairon)** — **Conversational AI platform to build effective Proactive Digital Assistants using Visual LLM Chaining.** Designed for enterprise with focus on security and integration . | [![Stars](https://img.shields.io/github/stars/digiteinfotech/kairon?style=social&color=white)](https://github.com/digiteinfotech/kairon/stargazers) | ~248 |

**Additional open-source options worth exploring:**

| Repo | Description |
|---|---|
| **[KnowBase AI](https://github.com/SamurAIGPT/ai-knowledge-base)** — Production-ready open-source AI knowledge base & custom chatbot builder. Next.js SaaS with RAG, document upload, URL scraping, Q&A training, citations, and embeddable chatbot widgets. Free alternative to Chatbase, CustomGPT, Botpress, SiteGPT . |
| **[rasa-admin](https://github.com/nesterapp/rasa-admin)** — Open-source alternative for Rasa-X. Admin interface for managing Rasa deployments . |
| **[EDDI](https://github.com/labsai/EDDI)** — Prompt & Conversation Management Middleware for Conversational AI APIs including OpenAI ChatGPT, Hugging Face, Anthropic Claude, Google Gemini, Ollama. Lean, restful, scalable, cloud-native. Java/Quarkus . |
| **[CopilotKit](https://github.com/CopilotKit/CopilotKit)** — In-app chatbot capabilities and intelligent text generation for React developers. Open-sourced . |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Conversational bot builders handle sensitive customer conversations and potentially PII; ensure compliance with GDPR, CCPA, and applicable data protection regulations.
- **Open-source reality**: The open-source ecosystem for conversational bot builders is **mature and production-proven**. **Rasa** is the leading enterprise-grade framework used by millions of developers . **Botpress** provides a visual drag-and-drop builder with zero external dependencies . **Tock** offers a complete platform with multi-channel connectors and Docker deployment . **Tiledesk** positions itself as an open-source alternative to Voiceflow and Botpress for multichannel workflow automation . However, **commercial platforms** (Power Virtual Agents, Dialogflow, Cognigy, Kore.ai) provide **managed infrastructure, enterprise SLAs, and integrated omnichannel deployment** that open-source alternatives require significant operational investment to match. The open-source path is **genuinely viable** for organizations with strong development capacity seeking full control over their conversational AI stack.
- **Pricing caveat**: All pricing figures above are **verified against cited search results** but may change without notice. **Ada has no free tier** and **Cognigy starts at ~$2,500/month**. Always request a formal quote for accurate budgeting.

---

**Made for conversational AI engineers, chatbot developers, customer experience teams, and enterprise architects.**
Let's make conversational bot builders more open, transparent, and accessible.
