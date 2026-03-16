# AI Agent Tools Landscape (2025-2026)

> Market size: $7.84B (2025) → $52.6B projected (2030) at 46.3% CAGR

When you give an agent a goal, it needs to touch the real world. That means infrastructure across five layers:

| Layer | Question it answers |
|-------|-------------------|
| [**Eyes** — Perceive](#eyes--perceive) | Can it find what it needs? |
| [**Brain** — Remember](#brain--remember) | Will it remember what it learned? |
| [**Hands** — Act](#hands--act) | Can it actually do things? |
| [**Wallet** — Pay](#wallet--pay) | Can it spend money safely? |
| [**Leash** — Trust](#leash--trust) | How do you keep it from going rogue? |

---

## Eyes — Perceive

> Read-only information gathering. Crawlers, search APIs — no side effects.

### Web Crawlers

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [Crawl4AI](https://github.com/unclecode/crawl4ai) | Web crawler that outputs LLM-ready content | 51K GitHub stars | Open source |
| [Firecrawl](https://www.firecrawl.dev/) | Managed URL-to-Markdown/JSON extraction | Widely used in agent pipelines | SaaS |
| [Apify](https://apify.com/) | 2,000+ ready-made scraping actors | Established platform | SaaS + marketplace |

### Search APIs

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [Tavily](https://tavily.com/) | AI-optimized search with content extraction | 93.3% accuracy (SimpleQA), 800K+ devs | Freemium |
| [Exa](https://exa.ai/) | Neural/semantic embeddings search | Sub-350ms latency | Usage-based |
| [Perplexity Sonar](https://docs.perplexity.ai/) | Search + LLM synthesis with citations | Returns synthesized answers | Usage-based |
| [Serper](https://serper.dev/) | Raw Google SERPs via API | ~2s latency, cheapest at scale | Usage-based |

---

## Brain — Remember

> Persistent memory and retrieval. Without this, agents are stateless and limited to single-session tasks.

### Memory / State

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [Mem0](https://mem0.ai/) | Graph-based agent memory platform | 26% accuracy boost, 90%+ token savings | Freemium |
| [Zep (Graphiti)](https://www.getzep.com/) | Enterprise memory with temporal reasoning | Tracks how facts change over time | Enterprise |
| [LangMem](https://github.com/langchain-ai/langmem) | Memory integrated with LangGraph | Tight LangGraph integration | Open source |

### Vector Databases / RAG

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [Pinecone](https://www.pinecone.io/) | Managed cloud-native vector DB | Hybrid search + serverless scaling | SaaS |
| [Weaviate](https://weaviate.io/) | AI-native DB with built-in vectorization | Multimodal support | Open source + cloud |
| [PostgreSQL + pgvector](https://github.com/pgvector/pgvector) | Vector search extension for Postgres | Dominant choice for GenAI 2025-2026 | Open source |
| [Milvus](https://milvus.io/) | High-performance vector DB | Scalable, open source | Open source |

---

## Hands — Act

> Everything that changes the world. Browser automation, computer use, code execution, communication, integrations, workflows.

### Browser Automation

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [Browser Use](https://browser-use.com/) | Open-source autonomous web browsing | 78K GitHub stars | Open source (MIT) |
| [Browserbase](https://www.browserbase.com/) | Cloud browser sessions with anti-detection | 50M+ sessions, 1K+ customers | SaaS, $40M Series B |
| [Stagehand](https://www.stagehand.dev/) | AI-native browser SDK — `act()`, `extract()`, `observe()` | v3 shipped Feb 2026 | Open source |
| [Steel](https://github.com/nichochar/steel-browser) | Open-source browser API for agents | Growing OSS community | Open source |
| [Playwright MCP](https://github.com/nichochar/playwright-mcp) | Microsoft's MCP server for browser automation | First-party Microsoft | Open source |

### Computer Use

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [Anthropic Computer Use](https://docs.anthropic.com/en/docs/computer-use) | Claude sees screens, clicks, types like a human | SOTA on OSWorld benchmark | API (beta) |
| [OpenAI Operator (CUA)](https://openai.com/operator) | GPT-4o-based browser automation agent | Managed virtual browser | Research preview |
| [Google Project Mariner](https://deepmind.google/) | Browser automation agent from DeepMind | — | Research preview |

### Code Execution

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [E2B](https://e2b.dev/) | Sandboxed execution via Firecracker microVMs | ~150ms cold start, hardware isolation | Freemium |
| [Daytona](https://www.daytona.io/) | Stateful sandboxed workspaces for agents | 27-90ms cold start | SaaS |
| [Modal](https://modal.com/) | Serverless compute for ML/AI workloads | GPU support, gVisor containers | Usage-based |

### Communication

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [Resend](https://resend.com/) / [SendGrid](https://sendgrid.com/) | Email APIs increasingly used by agents | REST API / function calling | SaaS |
| [Slack (Agentforce)](https://slack.com/) | Salesforce AI agents inside Slack | Native Salesforce integration | Enterprise |
| Gmail MCP | Read/send email, manage labels | MCP server | — |
| Slack MCP | Read/send messages, manage channels | MCP server | — |
| Discord MCP | Bot interactions via MCP | MCP server | — |

### File Storage

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [Fast.io](https://fast.io/) | Agent-specific cloud storage | Purpose-built for agent workflows | SaaS |
| [Poly](https://poly.ai/) | Cloud file storage with AI search | YC-backed | SaaS |
| S3 / GCS / Azure Blob | Standard object storage | API / MCP servers | Usage-based |

### Integrations

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [Composio](https://composio.dev/) | Managed auth, pre-built tools, execution controls | 27K GitHub stars | SaaS |
| [Pipedream](https://pipedream.com/) | Workflow automation | Acquired by Workday Nov 2025 | Enterprise |

### Workflows

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [Temporal](https://temporal.io/) | Open-source workflow orchestration | 99.99% SLA, multi-region | Open source + cloud |
| [Inngest](https://www.inngest.com/) | Durable functions replacing queues/state | Developer-friendly | SaaS |
| [Trigger.dev](https://trigger.dev/) | Background jobs with retries, human-in-the-loop | Built for AI agent workloads | SaaS |

---

## Wallet — Pay

> Spending money on behalf of users. Scoped access, virtual cards, approval flows — nobody's giving an agent an unlimited credit card.

### Payments

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [Stripe Agent Toolkit](https://docs.stripe.com/agents) | Payment links, card issuing, transactions | 78% of Forbes AI 50, 700+ AI startups | Usage-based |
| [Marqeta](https://www.marqeta.com/platform/mcp-server) | Card issuing with MCP server | Enterprise-grade | Enterprise |
| [Lithic](https://www.lithic.com/) | Programmable virtual cards, fine-grained spend controls | Partnered with Arcade | API-based |
| [Mastercard Agent Pay](https://www.mastercard.com/) | Network-level agent payment rails | All U.S. cardholders by holiday 2026 | Network fees |
| [agent-cards](https://www.npmjs.com/package/agent-cards) | CLI for prepaid virtual Visa cards for AI agents | Early stage / beta | Prepaid cards |

---

## Leash — Trust

> The control plane across every other layer. Auth, guardrails, observability, human-in-the-loop.

### Authentication

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [WorkOS](https://workos.com/) | Enterprise SSO/SCIM, M2M OAuth for agents | Co-chairs OpenID AI Identity working group | SaaS |
| [Auth0](https://auth0.com/) | Standardized OAuth/OIDC for agent tool calling | Upcoming agent product | SaaS |
| [Nango](https://nango.dev/) | Open-source OAuth for 700+ APIs | ~12 new integrations/month | Open source + cloud |
| [Arcade](https://arcade.dev/) | Agent tool calling with auth/governance | Security-focused, partnered with Lithic | SaaS |

### Guardrails

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [NVIDIA NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | Content safety, topic control, jailbreak detection | ~0.5s latency, 50% better protection | Open source |
| [Guardrails AI](https://www.guardrailsai.com/) | Validation framework — toxicity, PII scrubbing | Integrates with NeMo | Open source |

### Observability

| Tool | What It Does | Key Stat | Pricing |
|------|-------------|----------|---------|
| [Langfuse](https://langfuse.com/) | Open-source tracing, prompt management, evals | Acquired by ClickHouse, 26M+ SDK installs | Open source + cloud |
| [LangSmith](https://www.langchain.com/langsmith) | LangChain-native observability, multi-turn eval | Virtually no overhead | SaaS |
| [Arize](https://arize.com/) | Enterprise-grade observability (Phoenix open-source) | $70M Series C, 19 of Fortune 50 | Enterprise |
| [Braintrust](https://www.braintrust.dev/) | Eval-first platform with OpenTelemetry | Strong experimentation loop | SaaS |
