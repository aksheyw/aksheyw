# Hi, I'm Akshey 👋

**Senior Product Leader · 250M+ Device Scale · AI Product Builder · 0-to-1**

> I used to need a team and a quarter to ship a product. Now I need a weekend and an agent.

[![Open to roles](https://img.shields.io/badge/Open_to-senior_product_leadership_%2F_AI_Builder_roles-success?style=for-the-badge&logo=briefcase)](https://www.linkedin.com/in/aksheywalia/)
[![Availability](https://img.shields.io/badge/Available-immediately-22c55e?style=for-the-badge)](https://www.linkedin.com/in/aksheywalia/)
[![Credential](https://img.shields.io/badge/ISB_MBA-Flagbearer_Award_(top_1%25)-orange?style=for-the-badge)](https://aksheywalia.in)

ISB MBA and most recently Group PM at InMobi (Jan 2023 – Apr 2026). I led Go-To-Market and 0-to-1 product across 8 markets on Glance AI Lock Screen, an AI-powered platform pre-installed on 250M+ devices via OEM and telco partnerships. I ship AI products on my own time at github.com/aksheyw, with focused AI and agentic certifications from Vanderbilt, Duke, and Outskill.

---

## A rare 4-way combination

Most senior PMs have one or two of these, and I've shipped all four:

- 📱 **Consumer AI scale:** Group PM on Glance AI Lock Screen (InMobi, Jan 2023 – Apr 2026), 250M+ devices across 8 markets. Led US market entry 100K → 10M devices (100X in 18 months), reaching 6M DAU; ARPU $10 → $15 (+25% YoY); D60 retention 49% → 55%.
- 💸 **Fintech P&L:** built Magicbricks Pay Rent from 0 → INR 50Cr GMV (100% MoM at peak), payment success 95% → 99%, settlement 48hrs → 2hrs, integrated 3 payment gateways with cashback wiring across 5 banks (HDFC, ICICI, Kotak, Standard Chartered, IDFC).
- 🤝 **Fortune 500 partnerships:** OEM: Samsung, Motorola, Sharp, Xiaomi, Realme. Telco: Verizon (US), SoftBank (Japan).
- 🛠 **Hands-on AI builder:** ship real products with Claude Code, Codex, n8n, Vapi, and compatible LLMs from OpenAI, Anthropic, and Google (Gemini). The repos below are my actual config, sanitized and shared.

---

## Case Studies

Short written breakdowns of how I think about the products I build (the problem, the decisions and trade-offs, and what I'd do next):

- **[JobMagnet](https://github.com/aksheyw/jobmagnet-app/blob/main/CASE-STUDY.md)**: making a portfolio feel like it belongs to the company you're applying to; brand as a rendering problem, not a data problem; five agents over one prompt.
- **[GrowFlowAI](https://github.com/aksheyw/GrowFlowAI/blob/main/CASE-STUDY.md)**: removing the capture step entirely; meeting users where they already work; designing engagement with substance.
- **[Kahaani AI](https://github.com/aksheyw/kahaaniAI/blob/main/CASE-STUDY.md)**: moving the constraint from "can we afford to try this" to "what should we try"; honest cost transparency over impressive numbers.
- **[Ship Gate](https://github.com/aksheyw/claude-code-ship-gate/blob/main/CASE-STUDY.md)**: putting a quality gate where the skip flag doesn't exist; knowing when to stop hardening; learning from a real footgun.
- **[Mission Mode](https://github.com/aksheyw/mission-mode-case-study)**: a self-directed PM exercise on growth strategy for English learners in India: segmentation, JTBD, growth model, working prototype.

## Start here: PM thinking

| | |
|---|---|
| **[Mission Mode case study](https://github.com/aksheyw/mission-mode-case-study)** · [live →](https://mission-mode-casestudy.vercel.app/mission_mode_prototype_embed.html) | Self-directed PM exercise on growth strategy for English learners in India. Segmentation, JTBD, wireframes, growth model, working prototype. This is the artifact recruiters usually ask for, so I made it public. |

## AI products shipped

| | |
|---|---|
| **[JobMagnet](https://github.com/aksheyw/jobmagnet-app)** · [gallery →](https://jobmagnet-app.vercel.app/gallery) | Paste a job description + your résumé → a 5-agent pipeline (research → brand → narrative → pitch → code) builds a portfolio site brand-themed for *that* company, then hands you a deployable Next.js project to download. Built in 7 days for the OpenAI × Outskill hackathon. Codex SDK + Next.js + Supabase + Hostinger VPS · ~96s end-to-end. Agent runtime open-sourced at [jobmagnet-codex](https://github.com/aksheyw/jobmagnet-codex). |
| **[GrowFlowAI](https://github.com/aksheyw/GrowFlowAI)** · [demo →](https://grow-flow-ai.vercel.app) | AI task-management. Meeting notes become tasks via Telegram, web, or email. React + Supabase Edge + Capacitor (Android) + n8n + OpenAI (transcription, vision, LLM extraction). CI green, used daily. |
| **[Kahaani AI](https://github.com/aksheyw/kahaaniAI)** · [demo →](https://kahaani-ai-livid.vercel.app) | 3 publication-ready audio scripts in 90 seconds (for ₹2 vs ₹2,000). Built in 4 days. React + Vercel serverless + OpenAI. |

## Claude Code tooling (open-sourced from my own config)

| | |
|---|---|
| **[claude-code-ship-gate](https://github.com/aksheyw/claude-code-ship-gate)** | A pre-push quality gate for Claude Code. It runs your tests, code review, security, and a secret scan before any push to your protected branch and blocks it until they pass, so a `git push --no-verify` can't slip past. Default-on for a personal install, opt-in from the marketplace; say "ship it" to run it. Hardened by a 14-lens review + 3 red-team passes. Install: `/plugin marketplace add aksheyw/claude-code-ship-gate`. |
| **[claude-code-deep-review](https://github.com/aksheyw/claude-code-deep-review)** | 14-lens iterative review methodology. Found 14 production bugs (2 ship-stoppers) on first use. |
| **[claude-code-pm-agents](https://github.com/aksheyw/claude-code-pm-agents)** | 7 product-builder subagents (PM, growth, brand, ASO, SEO, YouTube, comms triage) plus a 9-seat product council that pressure-tests high-stakes calls: 8 seats answer independently and blind, and a Chair surfaces the dissent instead of averaging it. Charter and runbook skill included. |
| **[claude-code-rules](https://github.com/aksheyw/claude-code-rules)** | Opinionated global rules: honesty / earned-confidence, TDD, immutability, branching. |
| **[claude-code-learned-skills](https://github.com/aksheyw/claude-code-learned-skills)** | 12 skills auto-extracted from real debugging and research sessions (Docker/SSH/VPS, ML pipelines, prompting, quality tooling, a project wiki). |
| **[context-bridge](https://github.com/aksheyw/context-bridge)** | Per-project wiki + auto-generated handoff prompts that stop cross-session amnesia. Install: `npx skills add aksheyw/context-bridge`. 5 commands, 11-step save+sync, honesty rules embedded in adopters' CLAUDE.md. CI green on Ubuntu + macOS. |
| **[claude-code-guardrail-hooks](https://github.com/aksheyw/claude-code-guardrail-hooks)** | 4 hooks that block or capture an agent's mistakes at the tool-call boundary: effort-pause, lint-config protection, secret scan, subagent-output capture. Hardened by a 3-model adversarial review. |
| **[career-command-center-template](https://github.com/aksheyw/career-command-center-template)** | Plugin template for an AI-native job-search workflow: 12 skills, marketplace install (`/plugin marketplace add aksheyw/career-command-center-template`), example resume PDF in `examples/`. |

---

## How I work with AI

I treat Claude Code like a real product surface rather than a chat box, so every project I ship has its own subagents, rules, hooks, and skills, built and refined across multiple launches.

The honesty rule alone has changed how I work with Claude Code more than any prompt-engineering trick. It forces Claude to default to *"I haven't verified that. Want me to check?"* instead of confident-sounding fabrication.

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

- **InMobi Real Star Award (2× winner: 2022, 2025):** company's highest individual contribution award
- **InMobi top-performer recognition:** 4 consecutive years (2022-2025)
- **ISB Flagbearer Award** (October 2021): Top 1% of MBA class
- **ISB Alumni Association Board Member** (2024-Present)

---

## Certifications

- **Claude Code: SE with GenAI Agents**, Vanderbilt University (2026)
- **AI Product Management**, Duke University (2026)
- **Agentic AI and AI Agents for Leaders**, Vanderbilt University (2026)
- **Generative AI Strategic Leader**, Vanderbilt University (2025)
- **AI Generalist Accelerator Program**, Outskill (2025)
- **Digital Product Management Specialization**, UVA Darden

---

## Get in touch

Exploring **senior product roles · AI Product Building · 0-to-1 GTM** at AI-first companies, GCCs, and Indian product-led companies. **Available immediately.** Open to relocation across Indian metros.

- 💼 [LinkedIn](https://www.linkedin.com/in/aksheywalia/): primary inbound
- 🌐 [aksheywalia.in](https://aksheywalia.in): portfolio + voice-AI digital twin
- 📧 aksheyw [at] gmail [dot] com

---

<sub>Last updated: 2026-07</sub>
