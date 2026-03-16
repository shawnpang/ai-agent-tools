# AI Agent Tools Landscape (2025-2026)

> Market size: $7.84B (2025) → $52.6B projected (2030) at 46.3% CAGR

---

## Browser / Web Access

| Tool | What It Does | Integration | Popularity | Pricing Model |
|------|-------------|-------------|------------|---------------|
| [Browser Use](https://browser-use.com/) | Open-source framework for autonomous web browsing | Python SDK on Playwright, model-agnostic | 78K GitHub stars | Open source (MIT) |
| [Browserbase](https://www.browserbase.com/) | Cloud-hosted browser sessions with anti-detection | API, compatible with Playwright/Puppeteer/Selenium | 50M+ sessions, 1K+ customers | SaaS, $40M Series B |
| [Stagehand](https://www.stagehand.dev/) | AI-native browser automation SDK (by Browserbase) | TypeScript SDK — `act()`, `extract()`, `observe()` | v3 shipped Feb 2026 | Open source |
| [Steel](https://github.com/nichochar/steel-browser) | Open-source browser API for agents | Self-hostable browser sandbox | Growing OSS community | Open source |
| [Playwright MCP](https://github.com/nichochar/playwright-mcp) | Microsoft's MCP server for browser automation | MCP protocol for any MCP-compatible client | First-party Microsoft | Open source |
| [Crawl4AI](https://github.com/unclecode/crawl4ai) | Web crawler that outputs LLM-ready content | Python, self-hosted | 51K GitHub stars | Open source |
| [Firecrawl](https://www.firecrawl.dev/) | Managed URL-to-Markdown/JSON extraction API | REST API, cloud SaaS | Widely used in agent pipelines | SaaS |
| [Apify](https://apify.com/) | Platform with 2,000+ ready-made scraping actors | Marketplace of pre-built scrapers | Established platform | SaaS + marketplace |

---

## Payments / Financial

| Tool | What It Does | Integration | Popularity | Pricing Model |
|------|-------------|-------------|------------|---------------|
| [Stripe Agent Toolkit](https://docs.stripe.com/agents) | Create payment links, issue cards, process transactions | Python/TS SDKs, OpenAI/LangChain/CrewAI/Vercel AI | 78% of Forbes AI 50, 700+ AI startups | Usage-based |
| [Marqeta](https://www.marqeta.com/platform/mcp-server) | Card issuing with dedicated MCP server | MCP protocol — provision cards, manage spend, flag anomalies | Enterprise-grade | Enterprise |
| [Lithic](https://www.lithic.com/) | Programmable virtual cards with fine-grained spend controls | API, partnered with Arcade for agentic commerce | Growing | API-based |
| [Mastercard Agent Pay](https://www.mastercard.com/) | Network-level agent payment rails | Partnerships with Stripe, Google, Antom | All U.S. cardholders by holiday 2026 | Network fees |
| [agent-cards](https://www.npmjs.com/package/agent-cards) | CLI for prepaid virtual Visa cards for AI agents | CLI + MCP server | Early stage / beta | Prepaid cards |

---

## Code Execution Sandboxes

| Tool | What It Does | Integration | Differentiator | Pricing Model |
|------|-------------|-------------|----------------|---------------|
| [E2B](https://e2b.dev/) | Sandboxed code execution via Firecracker microVMs | API, ~150ms cold start | Hardware-level isolation, open source | Freemium |
| [Daytona](https://www.daytona.io/) | Stateful sandboxed workspaces for agents | Container-based, 27-90ms cold start | Persistent state across sessions | SaaS |
| [Modal](https://modal.com/) | Serverless compute for ML/AI workloads | Python-first, gVisor containers, GPU support | Best for GPU + ML workloads | Usage-based |

---

## Computer Use / Desktop Automation

| Tool | What It Does | Integration | Status |
|------|-------------|-------------|--------|
| [Anthropic Computer Use](https://docs.anthropic.com/en/docs/computer-use) | Claude sees screens, clicks, types like a human | API — screenshots + UI interaction | Beta, SOTA on OSWorld benchmark |
| [OpenAI Operator (CUA)](https://openai.com/operator) | GPT-4o-based browser automation agent | Managed virtual browser environment | Research preview |
| [Google Project Mariner](https://deepmind.google/) | Browser automation agent from DeepMind | Research preview | Research preview |

---

## Search APIs

| Tool | What It Does | Best For | Key Stat | Pricing Model |
|------|-------------|---------|---------|---------------|
| [Tavily](https://tavily.com/) | AI-optimized search with content extraction | Quality | 93.3% accuracy (SimpleQA), 800K+ devs | Freemium |
| [Exa](https://exa.ai/) | Neural/semantic embeddings search | Deep research | Concept-based, sub-350ms latency | Usage-based |
| [Perplexity Sonar](https://docs.perplexity.ai/) | Search + LLM synthesis with citations | Speed | Returns synthesized answers | Usage-based |
| [Serper](https://serper.dev/) | Raw Google SERPs via API | Volume / cost | ~2s latency, cheapest at scale | Usage-based |

---

## Memory / State

| Tool | What It Does | Integration | Key Stat | Pricing Model |
|------|-------------|-------------|---------|---------------|
| [Mem0](https://mem0.ai/) | Graph-based agent memory platform | Managed + self-hosted, API | 26% accuracy boost, 90%+ token savings | Freemium |
| [Zep (Graphiti)](https://www.getzep.com/) | Enterprise memory with temporal reasoning | Three-tier knowledge graph | Tracks how facts change over time | Enterprise |
| [LangMem](https://github.com/langchain-ai/langmem) | Memory integrated with LangGraph | Tool calls within LangGraph workflows | Tight LangGraph integration | Open source |

---

## Authentication / Identity

| Tool | What It Does | Integration | Status |
|------|-------------|-------------|--------|
| [WorkOS](https://workos.com/) | Enterprise SSO/SCIM, M2M OAuth for agents | OAuth/OIDC, prebuilt connectors (Okta, Azure AD, Google) | Co-chairs OpenID AI Identity working group |
| [Auth0](https://auth0.com/) | Standardized OAuth/OIDC flows for agent tool calling | OAuth/OIDC | Upcoming product for agents |
| [Nango](https://nango.dev/) | Open-source OAuth management for 700+ APIs | Manages full OAuth dance, token storage, refresh | ~12 new integrations/month |
| [Arcade](https://arcade.dev/) | Agent tool calling with auth/governance | Pre-built tool catalog, SDK, MCP support | Security-focused |

---

## Communication / Messaging

| Tool | What It Does | Integration |
|------|-------------|-------------|
| [Slack (Agentforce)](https://slack.com/) | Salesforce AI agents inside Slack | Native Slack integration with Salesforce data |
| Gmail MCP | Read/send email, manage labels | MCP server |
| Slack MCP | Read/send messages, manage channels | MCP server |
| Discord MCP | Bot interactions via MCP | MCP server |
| [Resend](https://resend.com/) / [SendGrid](https://sendgrid.com/) | Email APIs increasingly used by agents | REST API / function calling |

---

## File Storage

| Tool | What It Does | Integration |
|------|-------------|-------------|
| [Fast.io](https://fast.io/) | Agent-specific cloud storage — sign up, upload, manage permissions | API, purpose-built for agent workflows |
| [Poly](https://poly.ai/) | Cloud file storage with AI search (YC-backed) | Cloud-hosted |
| S3 / GCS / Azure Blob | Standard object storage | API / MCP servers |

---

## Agent Orchestration Frameworks

| Framework | What It Does | Key Stat | Best For |
|-----------|-------------|---------|---------|
| [LangGraph](https://www.langchain.com/langgraph) | Stateful multi-step agent workflows | 90M+ monthly downloads, 400 companies | Complex stateful workflows |
| [CrewAI](https://www.crewai.com/) | Role-based multi-agent collaboration | 44.6K GitHub stars | Fast prototyping, role-based agents |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | OpenAI's official agent framework | 19K+ GitHub stars | OpenAI ecosystem |
| [Anthropic Agent SDK](https://github.com/anthropics/anthropic-sdk-python) | Claude-based agent building | New | Claude ecosystem |
| [Google ADK](https://github.com/google/adk-python) | Google ecosystem agents | New | Google/Gemini ecosystem |
| [Smolagents](https://github.com/huggingface/smolagents) | Lightweight open-source agents (HuggingFace) | New | Lightweight / open-source |

---

## Observability / Evaluation

| Tool | What It Does | Key Stat | Pricing Model |
|------|-------------|---------|---------------|
| [Langfuse](https://langfuse.com/) | Open-source tracing, prompt management, evals | Acquired by ClickHouse (Jan 2026), 26M+ SDK installs | Open source + cloud |
| [LangSmith](https://www.langchain.com/langsmith) | LangChain-native observability, multi-turn eval | Virtually no overhead | SaaS |
| [Arize](https://arize.com/) | Enterprise-grade observability (Phoenix open-source) | $70M Series C, 19 of Fortune 50 | Enterprise |
| [Braintrust](https://www.braintrust.dev/) | Eval-first platform with OpenTelemetry | Strong experimentation loop | SaaS |

---

## Integration Platforms

| Tool | What It Does | Key Stat |
|------|-------------|---------|
| [Composio](https://composio.dev/) | Managed auth, pre-built tools, execution controls | 27K GitHub stars |
| [Nango](https://nango.dev/) | Open-source OAuth for 700+ APIs | Hundreds of agent companies |
| [Arcade](https://arcade.dev/) | Agent tool calling with MCP + security/governance | Partnered with Lithic |
| [Pipedream](https://pipedream.com/) | Workflow automation (acquired by Workday Nov 2025) | Enterprise stack |

---

## Guardrails / Safety

| Tool | What It Does | Key Stat |
|------|-------------|---------|
| [NVIDIA NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | Content safety, topic control, jailbreak detection | ~0.5s latency, 50% better protection |
| [Guardrails AI](https://www.guardrailsai.com/) | Validation framework — toxicity, PII scrubbing | Open source, integrates with NeMo |

---

## Workflow / Durable Execution

| Tool | What It Does | Differentiator |
|------|-------------|----------------|
| [Temporal](https://temporal.io/) | Open-source workflow orchestration | 99.99% SLA, multi-region, created by ex-Uber engineers |
| [Inngest](https://www.inngest.com/) | Durable functions replacing queues/state management | Developer-friendly |
| [Trigger.dev](https://trigger.dev/) | Background jobs with tool calling, retries, human-in-the-loop | Built for AI agent workloads |

---

## Vector Databases / RAG

| Tool | What It Does | Differentiator |
|------|-------------|----------------|
| [Pinecone](https://www.pinecone.io/) | Managed cloud-native vector DB | Hybrid search + serverless scaling |
| [Weaviate](https://weaviate.io/) | AI-native DB with built-in vectorization | Multimodal support |
| [PostgreSQL + pgvector](https://github.com/pgvector/pgvector) | Vector search extension for Postgres | Dominant choice for GenAI in 2025-2026 |
| [Milvus](https://milvus.io/) | Open-source high-performance vector DB | Scalable, open source |

---

## MCP Ecosystem

> Created by Anthropic (Nov 2024), donated to Linux Foundation (Dec 2025). 97M+ monthly SDK downloads, 10K+ active servers. Supported by Claude, ChatGPT, Cursor, Gemini, VS Code.

| Category | Notable MCP Servers |
|----------|-------------------|
| Version Control | GitHub |
| Browser | Playwright |
| Cloud | AWS (EC2, S3, IAM, CloudWatch) |
| Databases | PostgreSQL, Supabase, SQLite |
| Payments | Marqeta, Stripe |
| Communication | Slack, Gmail, Discord |
| Search | Tavily, Exa |
| Monitoring | Sentry |
| Data | dbt |
| File Systems | Filesystem |

**Directory:** [MCP.so](https://mcp.so/) indexes 3,000+ servers with quality ratings.
