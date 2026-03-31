## Apex Bridge Technology

Software studio focused on system architecture and backend delivery. Remote-first, based in Kazakhstan. [Astana Hub](https://astanahub.com) resident.

**What we do:** Architecture reviews · Performance sprints · Maintenance & SLA

**Stack:** Java/Spring Boot · C#/.NET · Node.js/TypeScript · PostgreSQL · AWS · Kafka · Redis · Docker

---

### 🐛 BugSpotter — our product

AI-powered bug reporting platform with session replay, semantic deduplication, and LLM enrichment. Open-source SDK, Chrome Extension, and admin panel.

| Repo | Description | Stack |
|------|-------------|-------|
| [bugspotter-sdk](https://github.com/apex-bridge/bugspotter-sdk) | Browser SDK with session replay, PII sanitization, 345 tests | TypeScript, rrweb, Playwright |
| [bugspotter-extension](https://github.com/apex-bridge/bugspotter-extension) | Chrome Extension for one-click bug capture | TypeScript, Chrome APIs |
| [bugspotter-intelligence](https://github.com/apex-bridge/bugspotter-intelligence) | RAG service for bug analysis with multi-LLM support | Python, FastAPI, pgvector |
| [dedupkit](https://github.com/apex-bridge/dedupkit) | Standalone semantic deduplication library | Python, embeddings |

**How it works:** capture bug reports with one click → AI deduplicates via vector similarity → LLM generates summaries and severity ratings → integrates with Jira, Slack, Discord.

🌐 [apexbridge.tech](https://apexbridge.tech) · 🐛 [bugspotter.io](https://bugspotter.io)
