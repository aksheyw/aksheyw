# Hi, I'm Akshey 👋

**Senior Product Leader · 250M+ Device Scale · AI Product Builder · 0-to-1**

> I used to need a team and a quarter to ship a product. Now I need a weekend and an agent.

[![Open to roles](https://img.shields.io/badge/Open_to-senior_product_leadership_%2F_AI_Builder_roles-success?style=for-the-badge&logo=briefcase)](https://www.linkedin.com/in/aksheywalia/)
[![Availability](https://img.shields.io/badge/Available-immediately-22c55e?style=for-the-badge)](https://www.linkedin.com/in/aksheywalia/)
[![Credential](https://img.shields.io/badge/ISB_MBA-Flagbearer_Award_(top_1%25)-orange?style=for-the-badge)](https://aksheywalia.in)

ISB MBA (Flagbearer Award, top 1%) and most recently Group PM at InMobi (Jan 2023 – Apr 2026). I led Go-To-Market and 0-to-1 product across 8 markets on Glance AI Lock Screen — an AI-powered platform pre-installed on 250M+ devices via OEM and telco partnerships. I ship AI products on my own time at github.com/aksheyw, with focused AI and agentic certifications from Vanderbilt, Duke, and Outskill.

---

## A rare 4-way combination

Most senior PMs have one or two of these — I've shipped all four:

- 📱 **Consumer AI scale** — Group PM on Glance AI Lock Screen (InMobi, Jan 2023 – Apr 2026), 250M+ devices across 8 markets. Led US market entry 100K → 6M devices (60X in 18 months); ARPU $10 → $15 (+25% YoY); D60 retention 49% → 55%.
- 💸 **Fintech P&L** — built Magicbricks Pay Rent from 0 → INR 50Cr GMV (100% MoM at peak), payment success 95% → 99%, settlement 48hrs → 2hrs, integrated 3 payment gateways with cashback wiring across 5 banks (HDFC, ICICI, Kotak, Standard Chartered, IDFC).
- 🤝 **Fortune 500 partnerships** — OEM: Samsung, Motorola, Sharp, Xiaomi, Realme. Telco: Verizon (US), SoftBank (Japan).
- 🛠 **Hands-on AI builder** — ship real products with Claude Code, Codex, n8n, Vapi, and compatible LLMs from OpenAI, Anthropic, and Google (Gemini). The repos below are my actual config, sanitized and shared.

---

## Case Studies

Short written breakdowns of how I think about the products I build — the problem, the decisions and trade-offs, and what I'd do next:

- **[JobMagnet](https://github.com/aksheyw/jobmagnet-app/blob/main/CASE-STUDY.md)** — making a portfolio feel like it belongs to the company you're applying to; brand as a rendering problem, not a data problem; five agents over one prompt.
- **[GrowFlowAI](https://github.com/aksheyw/GrowFlowAI/blob/main/CASE-STUDY.md)** — removing the capture step entirely; meeting users where they already work; designing engagement with substance.
- **[Kahaani AI](https://github.com/aksheyw/kahaaniAI/blob/main/CASE-STUDY.md)** — moving the constraint from "can we afford to try this" to "what should we try"; honest cost transparency over impressive numbers.
- **[Ship Gate](https://github.com/aksheyw/claude-code-ship-gate/blob/main/CASE-STUDY.md)** — putting a quality gate where the skip flag doesn't exist; knowing when to stop hardening; learning from a real footgun.
- **[Mission Mode](https://github.com/aksheyw/mission-mode-case-study)** — a self-directed PM exercise on growth strategy for English learners in India: segmentation, JTBD, growth model, working prototype.

## Start here — PM thinking

| | |
|---|---|
| **[Mission Mode case study](https://github.com/aksheyw/mission-mode-case-study)** · [live →](https://mission-mode-casestudy.vercel.app/mission_mode_prototype_embed.html) | Self-directed PM exercise on growth strategy for English learners in India. Segmentation, JTBD, wireframes, growth model, working prototype. The artifact recruiters usually ask for, made public. |

## AI products shipped

| | |
|---|---|
| **[JobMagnet](https://github.com/aksheyw/jobmagnet-app)** · [gallery →](https://jobmagnet-app.vercel.app/gallery) | Paste a job description + your résumé → a 5-agent pipeline (research → brand → narrative → pitch → code) builds a portfolio site brand-themed for *that* company, then hands you a deployable Next.js project to download. Built in 7 days for the OpenAI × Outskill hackathon. Codex SDK + Next.js + Supabase + Hostinger VPS · ~96s end-to-end. |
| **[GrowFlowAI](https://github.com/aksheyw/GrowFlowAI)** · [demo →](https://grow-flow-ai.vercel.app) | AI task-management. Meeting notes become tasks via Telegram, web, or email. React + Supabase Edge + Capacitor (Android) + n8n + OpenAI (transcription, vision, LLM extraction). CI green, used daily. |
| **[Kahaani AI](https://github.com/aksheyw/kahaaniAI)** · [demo →](https://kahaani-ai-livid.vercel.app) | 3 publication-ready audio scripts in 90 seconds — for ₹2 vs ₹2,000. Built in 4 days. React + Vercel serverless + OpenAI. |

## Claude Code tooling (open-sourced from my own config)

| | |
|---|---|
| **[claude-code-ship-gate](https://github.com/aksheyw/claude-code-ship-gate)** | A pre-push quality gate for Claude Code. It runs your tests, code review, security, and a secret scan before any push to your protected branch and blocks it until they pass, so a `git push --no-verify` can't slip past. Default-on for a personal install, opt-in from the marketplace; say "ship it" to run it. Hardened by a 14-lens review + 3 red-team passes. Install: `/plugin marketplace add aksheyw/claude-code-ship-gate`. |
| **[claude-code-deep-review](https://github.com/aksheyw/claude-code-deep-review)** | 14-lens iterative review methodology. Found 14 production bugs (2 ship-stoppers) on first use. |
| **[claude-code-pm-agents](https://github.com/aksheyw/claude-code-pm-agents)** | 7 product-builder subagents — PM, growth, brand, ASO, SEO, YouTube, comms triage. |
| **[claude-code-rules](https://github.com/aksheyw/claude-code-rules)** | Opinionated global rules: honesty / earned-confidence, TDD, immutability, branching. |
| **[claude-code-learned-skills](https://github.com/aksheyw/claude-code-learned-skills)** | 3 Docker / SSH / VPS skills auto-extracted from real debugging sessions. |
| **[context-bridge](https://github.com/aksheyw/context-bridge)** | Per-project wiki + auto-generated handoff prompts that stop cross-session amnesia. Install: `npx skills add aksheyw/context-bridge`. 5 commands, 11-step save+sync, honesty rules embedded in adopters' CLAUDE.md. v0.1.2 shipped with matrix CI green on Ubuntu + macOS. |
| **[career-command-center-template](https://github.com/aksheyw/career-command-center-template)** | Plugin template for an AI-native job-search workflow — 10 skills, marketplace install (`/plugin marketplace add aksheyw/career-command-center-template`), example resume PDF in `examples/`. |

---

## How I work with AI

I treat Claude Code like a real product surface, not a chat box. Every project I ship has its own subagents, rules, hooks, and skills — built and refined across multiple launches.

The honesty rule alone has changed how I work with Claude Code more than any prompt-engineering trick — it forces Claude to default to *"I haven't verified that — want me to check?"* instead of confident-sounding fabrication.

---

## Stack

**AI & Agents**

![Claude Code](https://img.shields.io/badge/Claude_Code-191919?style=flat&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=flat&logo=data:image/svg+xml;base64,PHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+T3BlbkFJPC90aXRsZT48cGF0aCBkPSJNMjIuMjgxOSA5LjgyMTFhNS45ODQ3IDUuOTg0NyAwIDAgMC0uNTE1Ny00LjkxMDggNi4wNDYyIDYuMDQ2MiAwIDAgMC02LjUwOTgtMi45QTYuMDY1MSA2LjA2NTEgMCAwIDAgNC45ODA3IDQuMTgxOGE1Ljk4NDcgNS45ODQ3IDAgMCAwLTMuOTk3NyAyLjkgNi4wNDYyIDYuMDQ2MiAwIDAgMCAuNzQyNyA3LjA5NjYgNS45OCA1Ljk4IDAgMCAwIC41MTEgNC45MTA3IDYuMDUxIDYuMDUxIDAgMCAwIDYuNTE0NiAyLjkwMDFBNS45ODQ3IDUuOTg0NyAwIDAgMCAxMy4yNTk5IDI0YTYuMDU1NyA2LjA1NTcgMCAwIDAgNS43NzE4LTQuMjA1OCA1Ljk4OTQgNS45ODk0IDAgMCAwIDMuOTk3Ny0yLjkwMDEgNi4wNTU3IDYuMDU1NyAwIDAgMC0uNzQ3NS03LjA3Mjl6bS05LjAyMiAxMi42MDgxYTQuNDc1NSA0LjQ3NTUgMCAwIDEtMi44NzY0LTEuMDQwOGwuMTQxOS0uMDgwNCA0Ljc3ODMtMi43NTgyYS43OTQ4Ljc5NDggMCAwIDAgLjM5MjctLjY4MTN2LTYuNzM2OWwyLjAyIDEuMTY4NmEuMDcxLjA3MSAwIDAgMSAuMDM4LjA1MnY1LjU4MjZhNC41MDQgNC41MDQgMCAwIDEtNC40OTQ1IDQuNDk0NHptLTkuNjYwNy00LjEyNTRhNC40NzA4IDQuNDcwOCAwIDAgMS0uNTM0Ni0zLjAxMzdsLjE0Mi4wODUyIDQuNzgzIDIuNzU4MmEuNzcxMi43NzEyIDAgMCAwIC43ODA2IDBsNS44NDI4LTMuMzY4NXYyLjMzMjRhLjA4MDQuMDgwNCAwIDAgMS0uMDMzMi4wNjE1TDkuNzQgMTkuOTUwMmE0LjQ5OTIgNC40OTkyIDAgMCAxLTYuMTQwOC0xLjY0NjR6TTIuMzQwOCA3Ljg5NTZhNC40ODUgNC40ODUgMCAwIDEgMi4zNjU1LTEuOTcyOFYxMS42YS43NjY0Ljc2NjQgMCAwIDAgLjM4NzkuNjc2NWw1LjgxNDQgMy4zNTQzLTIuMDIwMSAxLjE2ODVhLjA3NTcuMDc1NyAwIDAgMS0uMDcxIDBsLTQuODMwMy0yLjc4NjVBNC41MDQgNC41MDQgMCAwIDEgMi4zNDA4IDcuODcyem0xNi41OTYzIDMuODU1OEwxMy4xMDM4IDguMzY0IDE1LjExOTIgNy4yYS4wNzU3LjA3NTcgMCAwIDEgLjA3MSAwbDQuODMwMyAyLjc5MTNhNC40OTQ0IDQuNDk0NCAwIDAgMS0uNjc2NSA4LjEwNDJ2LTUuNjc3MmEuNzkuNzkgMCAwIDAtLjQwNy0uNjY3em0yLjAxMDctMy4wMjMxbC0uMTQyLS4wODUyLTQuNzczNS0yLjc4MThhLjc3NTkuNzc1OSAwIDAgMC0uNzg1NCAwTDkuNDA5IDkuMjI5N1Y2Ljg5NzRhLjA2NjIuMDY2MiAwIDAgMSAuMDI4NC0uMDYxNWw0LjgzMDMtMi43ODY2YTQuNDk5MiA0LjQ5OTIgMCAwIDEgNi42ODAyIDQuNjZ6TTguMzA2NSAxMi44NjNsLTIuMDItMS4xNjM4YS4wODA0LjA4MDQgMCAwIDEtLjAzOC0uMDU2N1Y2LjA3NDJhNC40OTkyIDQuNDk5MiAwIDAgMSA3LjM3NTctMy40NTM3bC0uMTQyLjA4MDVMOC43MDQgNS40NTlhLjc5NDguNzk0OCAwIDAgMC0uMzkyNy42ODEzem0xLjA5NzYtMi4zNjU0bDIuNjAyLTEuNDk5OCAyLjYwNjkgMS40OTk4djIuOTk5NGwtMi41OTc0IDEuNDk5Ny0yLjYwNjctMS40OTk3WiIvPjwvc3ZnPg==&logoColor=white)
![Google Antigravity](https://img.shields.io/badge/Google_Antigravity-202124?style=flat&logo=data:image/png;base64,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)
![OpenClaw](https://img.shields.io/badge/OpenClaw-F70514?style=flat&logo=data:image/png;base64,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&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)

**Build**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

---

## Recognition

- **InMobi Real Star Award (2× winner: 2022, 2025)** — company's highest individual contribution award
- **InMobi top-performer recognition** — 4 consecutive years (2022-2025)
- **ISB Flagbearer Award** (October 2021) — Top 1% of MBA class
- **ISB Alumni Association Board Member** (2024-Present)

---

## Certifications

Focused AI and agentic certifications from Vanderbilt, Duke, and Outskill:

- **Claude Code: SE with GenAI Agents** — Vanderbilt University (2026)
- **AI Product Management** — Duke University (2026)
- **Agentic AI and AI Agents for Leaders** — Vanderbilt University (2026)
- **Generative AI Strategic Leader** — Vanderbilt University (2025)
- **AI Generalist Accelerator Program** — Outskill (2025)
- **Digital Product Management Specialization** — UVA Darden

---

## Get in touch

Exploring **senior product roles · AI Product Building · 0-to-1 GTM** at AI-first companies, GCCs, and Indian product-led companies. **Available immediately.** Open to relocation across Indian metros.

- 💼 [LinkedIn](https://www.linkedin.com/in/aksheywalia/) — primary inbound
- 🌐 [aksheywalia.in](https://aksheywalia.in) — portfolio + voice-AI digital twin
- 📧 aksheyw [at] gmail [dot] com

---

<sub>Last updated: 2026-05</sub>
