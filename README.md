<h1 align="center">Muhammad Arose Sibram Khan</h1>
<h3 align="center">Senior Data Engineer · Lead AI Engineer</h3>
<p align="center">I build production ETL/ELT platforms on Azure, AWS and GCP — and the GenAI systems that sit on top of them.</p>

<p align="center">
  <a href="https://arose-niazi.me">Portfolio</a> ·
  <a href="https://arose-niazi.me/arose-resume.pdf">Résumé</a> ·
  <a href="https://www.upwork.com/freelancers/arosen2">Upwork</a> ·
  <a href="mailto:niazi.arose@gmail.com">niazi.arose@gmail.com</a>
</p>

---

## Worked with

Luminor Partners · Rextag Corp · ZigTech Solutions · Helpicon AB · Legateca · ExpertFlow · Eating App · RESI HOP — plus 50+ clients on Upwork, where I'm Top Rated Plus.

These days I lead AI engineering on a production LLM/RAG venture and own cloud & data engineering for enterprise clients. 6+ years, 50+ delivered projects, 90%+ repeat client rate. Based in Lahore, Pakistan; working remotely across US/EU timezones.

## What I actually do

**Data platforms.** Azure Data Factory, Databricks/PySpark, Snowflake and hand-rolled Python ETL moving millions of records a day into warehouses that reporting teams can trust. CDC, SCD Type 2, star schemas, historical snapshotting, cost optimisation.

**GenAI on top of that data.** Production LLM/RAG applications on Amazon Bedrock — including an LLM-to-SQL analytics platform that lets non-technical users ask questions in English and get live dashboards back, with read-only execution, deterministic SQL linting and per-tenant row-level security.

**The integrations nobody wants to touch.** NetSuite (SuiteQL/SuiteTalk, OAuth1 & OAuth2), Shopify REST/GraphQL, Toast POS, HubSpot, ApparelMagic, UKG, Stripe, Twilio.

**Everything around it.** Full-stack apps (FastAPI, React, Node.js, NestJS, Django), infrastructure as code (Terraform, Docker, Kubernetes), CI/CD, and servers I run myself on AWS, Azure, Hetzner, DigitalOcean and OVH.

## Selected work

### AI & GenAI

| Project | What it is |
|---|---|
| **AI Dashboard Runner** | Multi-tenant LLM-to-SQL platform (FastAPI + React on Bedrock/Claude) that turns plain-English prompts into live dashboards — read-only execution, deterministic SQL linting, per-tenant row-level security, JWT + Entra SSO, and a remote MCP connector for programmatic access |
| **GMI Intake** | AI-driven automation of a mentorship programme's application intake — LLM extraction and review in place of manual data entry, feeding AI-supported dashboards |

### Data platforms

| Project | What it is |
|---|---|
| **RASA Floors** | Flooring retailer's analytics platform. SQL Server warehouse (1.2M invoices / 6.5M line items) fed by four independent pipelines — POS/SQLite, an OData property API covering 245K properties, SharePoint AR + inventory, and CRM — plus a FastAPI/React reporting app with 18 report pages, Power BI feeds, and a nightly read-replica serving the AI runner |
| **Rextag** | Energy pipeline-capacity platform. FERC, EIA and EPA filings into on-prem SQL Server via Azure Data Factory over a self-hosted integration runtime, with T-SQL aggregation procedures and a registry tracking the proc, pipeline and trigger keeping every table fresh |
| **Pink Chicken** | 50+ ADF pipelines ingesting millions of e-commerce records daily from Shopify + ApparelMagic into SQL Server and Power BI |
| **Apex Healthcare** | NetSuite → PostgreSQL/Parquet financial warehouse on AWS; executive KPI dashboards via Athena and Tableau |
| **Palmetto** | AirOne + NetSuite + UKG consolidated into Azure Data Lake with historical snapshotting for C-level analytics |
| **NYCT Fleet Maintenance** | 10-step Python ETL with custom CDC, syncing mission-critical transit data off legacy SQL without stressing production |

### Platforms & internal tools

| Project | What it is |
|---|---|
| **Global Mentorship Initiative** | Azure + self-hosted platform for a mentorship non-profit: central SSO service, staff matching portal, a form builder with public renderer, HubSpot sync, WordPress session extraction over an SSH tunnel, and Azure Functions/SQL data-quality reporting — six domains behind nginx/PM2 with automated certificates |
| **North Main Motors** | Dealership management backend (Express 5 + Prisma + PostgreSQL). Python ETL out of the DMS, then automated booking sheets that generate the debit/credit accounting lines for every deal, plus commission plans and funding-source, subprime and year-over-year retail reporting |
| **BPI Portal** | Construction project management platform (Node/React) with JWT auth, multi-phase job tracking and modular REST APIs |

### Personal

| Project | What it is |
|---|---|
| **[Mini Missions](https://mm-ftw.net)** | GTA:SA multiplayer server running since 2008 — 456 missions, full economy, anti-cheat, PHP site, Discord bot. Handed to the community, still online |
| **[SE Tools](https://se-tools.arose-niazi.me)** | 17 step-by-step calculators and simulators for numerical computing, networks and OS courses |

More detail, including case studies, on [arose-niazi.me](https://arose-niazi.me).

## Public repos worth a look

- [**claude-knowledge-base-template**](https://github.com/Arose-Niazi/claude-knowledge-base-template) — a second brain for AI-assisted engineering: raw sources, refined current truth, and a dated changelog of every change and its why
- [**claude-remote-controller**](https://github.com/Arose-Niazi/claude-remote-controller) — drive Claude Code sessions remotely
- [**se-tools**](https://github.com/Arose-Niazi/se-tools) — the course tools suite above, one repo per tool via submodules

Most of my client and platform work lives in private repos.

## Toolbox

**Cloud & data** — Azure (ADF, Synapse, Functions, Key Vault) · AWS (Lambda, S3, Athena, Glue, Redshift, ECS/EKS, Bedrock) · GCP (BigQuery) · Snowflake · Databricks (PySpark)

**AI & GenAI** — LLM application development · RAG · Amazon Bedrock · Claude · LLM-to-SQL · prompt engineering · MCP (Model Context Protocol) · multi-tenant row-level security

**ETL/ELT & orchestration** — Azure Data Factory · dbt · Apache Spark · custom Python ETL · CDC / SCD Type 2 · Docker · Kubernetes · Terraform · CI/CD (Jenkins, GitHub Actions)

**Languages & databases** — Python (Pandas, SQLAlchemy, Boto3) · T-SQL · PL/pgSQL · Snowflake SQL · SuiteQL · TypeScript/JavaScript · Bash · PostgreSQL · MySQL · Azure SQL · Amazon RDS · MongoDB · Redis

**Full-stack & reporting** — FastAPI · Flask · Django · React · Next.js · Node.js · NestJS · Strapi · Prisma · Power BI · Tableau

**Infrastructure** — AWS · Azure · Hetzner · DigitalOcean · OVH — server setup, warehouse deployment, cost optimisation

---

<p align="center"><i>Open to remote data engineering and AI engineering work. The fastest way to reach me is <a href="mailto:niazi.arose@gmail.com">email</a>.</i></p>
