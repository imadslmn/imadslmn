# Imad — AI engineer, founder of [Solrus](https://solrus.pro)

I build software, ERP systems and AI automations for businesses in Algeria — from Algiers, hands-on,
with a small team.

Most of what I ship is unglamorous and load-bearing: back-office tools for accounting firms,
manufacturers, HR and childcare, order and reporting automations, and the compliance plumbing that
lets an Algerian company use frontier AI without its customers' data leaving the country.

## Open source

| | |
|---|---|
| [**claude-plugins**](https://github.com/imadslmn/claude-plugins) | Solrus marketplace for Claude Code. Includes **algeria-data-protection**: a skill that keeps AI-backed projects compliant with Algeria's personal-data law (18-07 / 25-11, ANPDP) — data residency, a de-identifying egress gateway for foreign LLM APIs, a working PII redactor for Algerian formats, and the compliance paper trail in French. `/plugin install algeria-data-protection --marketplace imadslmn/claude-plugins` |

## What I work with

**Backend & data** — Python (FastAPI), TypeScript (Next.js, Node), PostgreSQL, Redis
**AI & automation** — Claude, OpenAI, RAG on self-hosted vector stores, n8n (self-hosted), Claude Code as a daily tool
**Mobile & desktop** — Flutter, Windows desktop apps that integrate with Algerian accounting software
**Infra** — Linux VPS on Algerian hosting, Docker, CI with compliance checks baked in

## How I think about building here

- The data stays in Algeria. The model can be anywhere; the names, phones and NINs can't.
- A client should be able to run the system without me. Documentation and a clean `compliance/`
  folder are deliverables, not extras.
- Boring architecture, honest estimates, and one chokepoint for anything that leaves the server.

## Contact

- Website: [solrus.pro](https://solrus.pro)
- LinkedIn: [linkedin.com/in/YOUR-HANDLE](https://www.linkedin.com/in/YOUR-HANDLE)
- Email: contact@solrus.pro

Open to work with Algerian SMEs and agencies that want an AI feature done properly, and to
corrections on the data-protection plugin from DPOs and lawyers who know the texts better than I do.
