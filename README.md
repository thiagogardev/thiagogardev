### Thiago Garofalo · AI Engineer · Forward Deployed

AI engineer who puts systems into production and answers for the business result. Before the code came 25 years running industrial B2B companies, and that is where the problems I solve with AI come from: the side of the person who decides.

**Claude API · MCP · RAG · evals in production · TypeScript · Python**

[Portfolio and case studies](https://garofalodeveloper.com/en/) · [LinkedIn](https://www.linkedin.com/in/thiago-garofalo-792a2653/) · [versão em português](https://garofalodeveloper.com)

#### What I have built and run today, from code to infrastructure

- **[WhatsApp support hub](https://garofalodeveloper.com/en/cases/central-atendimento.html)**: one number for three SaaS products. Claude answers only from the Help Center (201 articles), declines what is out of scope and hands off to a human with a ticket and a watched deadline. Cost per question tracked on the dashboard.
- **[Sales bot for Acoplin](https://garofalodeveloper.com/en/cases/robo-acoplin.html)**: qualifies leads from ads, checks the company tax ID with the Federal Revenue and hands the order to a salesperson. No LLM, by choice: a closed flow covered by 28 automated tests. In the first 3 days, 47% of conversations became orders.
- **[Genesis](https://garofalodeveloper.com/en/cases/genesis.html)**: B2B sales intelligence that cross-references public data (procurement and mining registries), ranks leads with an LLM and is evaluated with Precision@K.
- **[Escrituro](https://garofalodeveloper.com/en/cases/escrituro.html) and [Clinalta](https://garofalodeveloper.com/en/cases/clinalta.html)**, SaaS products of Asset Tecnologia, my software company. Escrituro serves accounting firms, with e-invoice capture and Simples Nacional tax calculation integrated with the federal Serpro API. Clinalta runs medical clinics, with ICD-10 and an audit log of every access to patient records.
- **In-house ERP** that replaced SAP Business One: quotes with ICMS ST tax calculation, e-invoices, finance, purchasing and inventory, used every day by the team.
- **[Tax legislation monitor](https://garofalodeveloper.com/en/cases/icms-st.html)** in Python: collects 37 official sources and alerts when a rule changes.
- **[Infrastructure](https://garofalodeveloper.com/en/cases/infraestrutura.html)**: from a ransomware attack to three clouds in five days, with hourly immutable backups and tested restores.

#### Open source

| Repository | What it does | Stack |
|---|---|---|
| [**agente-emporio-musica**](https://github.com/thiagogardev/agente-emporio-musica) | Customer service agent with a hand-written tool-calling loop: policy manual in context, five tools over the store data, identity check before showing an order. 34 tests that run without calling the model | Python, Claude API |
| [**agentes-rede-streaming**](https://github.com/thiagogardev/agentes-rede-streaming) | Architecture of six agents that forecast demand peaks on a streaming network and prepare capacity before them: quantile forecasting, optimization, RAG and GraphRAG, human approval by stages | LangGraph, Spark, Databricks |
| [**icms-st-dados**](https://github.com/thiagogardev/icms-st-dados) | Brazil's ICMS tax-substitution rules as open data, with the validity of each wording and the SHA-256 of every source read. 79 tests in CI | Python |
| [**monofasico-br**](https://github.com/thiagogardev/monofasico-br) | Decides whether a product is single-phase PIS/COFINS, always citing the law and article; "to be confirmed" when the invoice cannot prove a condition | TypeScript |
| [**custo-importacao-br**](https://github.com/thiagogardev/custo-importacao-br) | Landed cost of importing 1 kg of any of 8,782 NCMs and the domestic price ceiling, only from official open data | TypeScript |

#### How I work

- **I measure before I trust:** regression tests that run without calling the model, Precision@K and cost per call.
- **Critical rules live in code**, not only in the prompt. And not every problem needs an LLM.
- **I code every day with Claude Code**, using my own skills and subagents, and I review every line that ships.

#### Stack

TypeScript · Next.js · Node.js · Python · Claude API · MCP · RAG with pgvector · PostgreSQL · Docker · Oracle Cloud · AWS · GitHub Actions

#### Background

B.Eng. in Production Engineering, holder of two patents on quick couplings with safety locks. Postgraduate program in Cognitive Systems with AI Agents in progress. Open to remote roles as AI Engineer or Forward Deployed Engineer.
