# ai-platform-engineering-portfolio

## Portfolio Overview

This repository is the landing point for a portfolio of sanitized case studies and learning labs built to document a career transition from enterprise infrastructure into AI Platform Engineering, with a specific focus on agent integration and tool platform work.

Every linked repo is an independent development exercise: a portfolio demonstration, sanitized case study, or learning lab. None represent production systems, live services, or real business operations.

## Repository Index

| Repo | Focus |
|---|---|
| [ai-learning-platform-case-study](../ai-learning-platform-case-study) | Learning platform: paths, lessons, progress, quizzes, certificates, admin analytics |
| [wallet-auth-dashboard-case-study](../wallet-auth-dashboard-case-study) | Wallet-connected auth/dashboard concept, admin wallet registry |
| [content-automation-engine-case-study](../content-automation-engine-case-study) | Multi-platform content generation pipeline with human editorial review |
| [rewards-eligibility-admin-case-study](../rewards-eligibility-admin-case-study) | Admin-only eligibility, campaign, and distribution reporting system |
| [agent-tool-registry-lab](../agent-tool-registry-lab) | **Flagship lab** — AI agent tool registry: discovery, schemas, versioning, governance, observability |
| [supabase-schema-lab](../supabase-schema-lab) | *(future)* Focused schema-design learning exercises |
| [api-routes-reference-lab](../api-routes-reference-lab) | *(future)* Focused API route design and contract learning exercises |

## Career Transition Positioning

This portfolio documents independent, self-directed learning and system design work undertaken to move from an enterprise infrastructure background toward AI Platform Engineering — specifically the intersection of backend platform design and agent/tool integration.

## Tools Used

- Vercel (deployment concepts)
- Supabase (PostgreSQL database design)
- GitHub (version control)
- Cursor and Claude (AI-assisted development)
- ChatGPT (architecture planning, troubleshooting, documentation, prompt engineering)
- SQL (schema design, relational modeling)
- Python (entry level, scripting/tooling exposure)
- Docker (learning in progress)
- MCP (Model Context Protocol — learning in progress, forward-looking alignment)

## Skills Demonstrated

- Relational database schema design
- API route planning and resource-oriented contract design
- Authentication and access-control modeling (including non-traditional identity models)
- Admin/reporting dashboard design (search, pagination, export)
- Governance and audit-trail modeling
- Observability and execution logging concepts
- Tool/agent registry and service-contract design
- Technical documentation and system diagramming (Mermaid)

## What Is Intentionally Excluded

- Any reference to specific companies, products, or businesses operated by the author
- Real credentials, API keys, tokens, or environment values
- Real customer, user, or production data
- Private or internal URLs, including Supabase project URLs
- Proprietary business logic

## Interview Talking Points

- Each case study was built to practice a specific platform concern end-to-end: schema design, API planning, access control, or admin reporting.
- The `agent-tool-registry-lab` repo is the most directly relevant to Agent Integration & Tool Platform Engineering — it models tool registration, discovery, schema contracts, versioning, permissions, and execution observability.
- The portfolio is intentionally sanitized so it can be discussed openly without exposing any private or proprietary information, while still showing real system-design reasoning.

## 30/60/90-Day Learning Roadmap

**Days 1-30 — Foundations**
- Deepen SQL and relational modeling practice (indexes, constraints, normalization tradeoffs)
- Review Docker fundamentals: images, containers, basic Compose setups
- Read the MCP specification and map it against `agent-tool-registry-lab`

**Days 31-60 — Applied Platform Work**
- Extend `agent-tool-registry-lab` with a working tool-permission check and execution logging
- Practice writing OpenAPI-style contracts for the routes documented in `api-routes-reference-lab`
- Build a small Docker-based local dev environment for one case study

**Days 61-90 — Integration & Depth**
- Prototype a minimal MCP-style server wrapping one or two tools from the registry lab
- Add basic observability (structured logs, latency tracking) to one case study
- Document a governance model (roles, permissions, audit trail) applied consistently across two repos

## Links Section

- [ai-learning-platform-case-study](../ai-learning-platform-case-study)
- [wallet-auth-dashboard-case-study](../wallet-auth-dashboard-case-study)
- [content-automation-engine-case-study](../content-automation-engine-case-study)
- [rewards-eligibility-admin-case-study](../rewards-eligibility-admin-case-study)
- [agent-tool-registry-lab](../agent-tool-registry-lab)
- [supabase-schema-lab](../supabase-schema-lab)
- [api-routes-reference-lab](../api-routes-reference-lab)

## Folder Structure

```
ai-platform-engineering-portfolio/
├── README.md
├── docs/
│   ├── architecture.md
│   ├── database-schema.md
│   ├── api-routes.md
│   ├── dashboard-features.md
│   ├── security-notes.md
│   ├── lessons-learned.md
│   └── interview-talk-track.md
├── diagrams/
│   ├── system-overview.md
│   └── data-flow.md
├── sql/
│   └── example-schema.sql
├── api/
│   └── route-examples.md
└── screenshots/
    └── README.md
```

## Disclaimer

> This schema is a sanitized learning version based on independent development work. It does not contain production data, private credentials, proprietary logic, or real customer records.
