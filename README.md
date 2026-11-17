# Marco Drummond

AI engineer and founder in Belo Horizonte, Brazil. I build agentic systems that run in production for real users, and the tooling that keeps agent-written code reliable.

## What I build

- **Bridge** — founder. The AI platform for BNI, the world's largest business referral network (355,000+ members, 11,800+ chapters, 78 countries). Built for every level of the network (global, regional and chapter, each with its own configuration) and in production across the BNI Minas region: 26 agents over WhatsApp, Telegram, e-mail and web, eight languages, Zoom attendance reconciliation with human review and sync with BNI Connect. → [bridge.american-infogest.com](https://bridge.american-infogest.com)
- **PHC** — forward deployed engineer. The operating platform for a home-care network becoming a franchisor: leads, contracts, care plans, scheduling, HR, payroll, finance, LGPD compliance and a public API, with agents across the operation. → [app.personalhumancare.com](https://app.personalhumancare.com)
- **OfficeBot** — omnichannel customer service with AI for many organizations and business verticals (legal, healthcare, aesthetics, accounting, schools, HR, retail and more): WhatsApp, Telegram, Instagram and Messenger behind one channel contract, an orchestrator with function calling, semantic search over each organization's knowledge base, sales funnel and human handoff. → [app.officebot.com.br](https://app.officebot.com.br)
- **OfficeBiz** — real-time meeting intelligence, local-first: live playbook checklist, tips and alerts from the attributed transcript, analyzed by a model running on the user's machine.
- **Smart Browser** — my own Model Context Protocol server and Chromium extension that let coding agents read and act on real web pages (DOM, forms, network, performance), written in TypeScript without an MCP library.

## Before AI: EconomizePlus (case study)

Loyalty and CRM platform for fuel stations, an Infogest product where I was the architect and main developer (about 80% of the code). The hard part was legacy hardware: a Node.js backend with long-running daemons that read fueling events from the stations' pump controllers and MySQL, reconciled them and turned them into loyalty data; an Ionic/Angular app with Firebase, published on the Apple and Google stores; and a back office for the stations.

## How I work

- Coding agents are my daily toolchain (Claude Code), inside a harness I built: skills, sub-agents, pre-tool hooks that block unsafe changes, spec-first and test-first gates, and review of every diff.
- The model never gets the final word: structured outputs validated at runtime, the backend decides, and low-confidence cases go to a person.
- I measure before I claim: prompt-evaluation batteries, tracing of every model call with cost and latency, multi-provider routing (Claude, OpenAI, Gemini, Ollama).

## Stack

TypeScript · Node.js · NestJS · React · Next.js · PostgreSQL / pgvector · Redis · BullMQ · Docker · GitHub Actions · Jest · Vitest · Playwright

Most of my work lives in private client repositories. Happy to walk through architecture and code in a call.

[LinkedIn](https://www.linkedin.com/in/madrummond/) · [Infogest](https://www.american-infogest.com) · drummond@infogest.com.br
