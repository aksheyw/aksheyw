# Hi, I'm Akshey 👋

> **Senior Product Leader · Consumer Platforms at 250M+ Device Scale · AI Product Building · 0-to-1**

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

**AI / Automation:** Claude Code (daily) · Codex · OpenAI · Anthropic · Google (Gemini) · OpenRouter · Vapi · Deepgram · ElevenLabs · n8n · Google Antigravity · Bolt.new
**Frontend:** React · Next.js · Tailwind · Capacitor (Android)
**Backend:** Supabase (Postgres + Edge Functions + pgvector) · Firebase · Vercel serverless · Node.js
**Infra:** GitHub Actions · Vercel · Hostinger VPS

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
