# Gaurav Trivedi

### Principal Technical Writer at Red Hat
### Building AI systems, automation tooling, and documentation workflows in public
### Studying to become an AI Solutions Architect by designing and shipping systems

I’m adapting early: documenting the disruption, automating workflows, and learning to design the systems behind them — **in public**.

---

## The Operating Model

This profile documents one ongoing transition: **mastering a craft, automating it, and moving one layer higher.**

The stack is built on three layers:

* **The Craft** → what I write
* **The Engine** → what I build
* **The Architecture** → what I am becoming

---

## Quick Start

If you're new here:

1. [Read what I'm writing on the blog](https://beingtechnicalwriter.com)
2. [Explore documentation automation tools](#layer-2--the-automation-engine)
3. [See the AI Architecture roadmap](#layer-3--the-architecture-pivot)
4. [Follow the public journey](https://github.com/gtrivedi88/ai-solutions-architect)

---

## System Telemetry

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=gtrivedi88&show_icons=true&theme=transparent&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gtrivedi88&layout=compact&theme=transparent&hide_border=true" alt="Top Languages" />
</div>

* **20+** public repositories
* **50+** technical articles
* **5** workflow automation tools shipped
* Building a **365-day** AI Solutions Architecture roadmap in public

---

## Tech Stack

### AI / LLM
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000) ![Azure](https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)

### Documentation
![Antora](https://img.shields.io/badge/Antora-E03C31?style=for-the-badge) ![DITA](https://img.shields.io/badge/DITA-000000?style=for-the-badge) ![Vale](https://img.shields.io/badge/Vale-000000?style=for-the-badge) ![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

### Frontend / Backend
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

### DevOps / Infrastructure
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white) ![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=GitHub%20Pages&logoColor=white)

---

## Layer 1 · The Craft

**Day job:** Principal Technical Writer at **Red Hat** — maintaining open-source documentation at enterprise scale. 

**Outside work:** **[beingtechnicalwriter.com](https://beingtechnicalwriter.com)** — a blog about what is actually happening to technical writing right now, told by someone who is still doing it.

Recent output logs:
* What survival as a technical writer looks like in 2026
* Google Antigravity, Cursor AI, and the IDE wars from a docs lens
* Why AI is good at first drafts and bad at API references
* A first-person tour through learning AI architecture from inside the writing chair

If you write for a living and you're wondering whether you should be afraid, the honest answer is on the blog. So is what to do about it.

---

## Layer 2 · The Automation Engine

Production-grade tooling designed to eliminate repetitive manual work. Zero prototypes. Built from repeated operational pain.

### [content-editorial-assistant](https://github.com/gtrivedi88/content-editorial-assistant) &nbsp; `★ 12 · ⑂ 14`
The docs-and-build artifact for the Content Editorial Assistant (CEA) platform — an AI-assisted editorial system for technical content. Why the metric matters: **more forks than stars** means people aren't just bookmarking, they're picking it up and adapting it. Mermaid architecture diagrams, REST + WebSocket API reference, Antora-built and GitHub-Pages-deployed.
**Stack:** Python · Antora · GitHub Actions

### [cqa-assessment](https://github.com/gtrivedi88/cqa-assessment)
A toolkit that evaluates, remediates, and scores Red Hat modular documentation against all **54 parameters of CQA 2.1**. Twelve specialized guides plus eleven zero-dependency Python scripts, executed in sequence so early fixes don't cascade into false positives downstream. The guides are plain markdown, so the whole framework runs natively under Claude Code, Cursor, Copilot, Windsurf, or Gemini CLI — tool-agnostic by design. Before-and-after reports plug directly into JIRA and PR review.
**Stack:** Python 3.9+ (zero deps) · Vale · DITA 1.3 · MIT

### [redhat-docs-agent-tools](https://github.com/gtrivedi88/redhat-docs-agent-tools)
A plugin marketplace of Claude Code skills and agent tools for Red Hat documentation workflows. One command — `/plugin install <name>@redhat-docs-agent-tools` — and a repetitive doc operation becomes an agent call. Auto-deploys via GitHub Pages on every merge.
**Stack:** Claude Code SDK · Zensical · GitHub Actions · Apache-2.0

### [productivity](https://github.com/gtrivedi88/productivity)
A Flask + React productivity tracker. Tracks workload patterns, predicts completion risk, and visualizes behavior trends over time with **cognitive-load classification on tasks and streak gamification**. Features a dark UI that doesn't hurt at 11 pm.
**Stack:** Flask 3 · React 18 · Chart.js · SQLite · MIT

### [unlockpdf](https://github.com/gtrivedi88/unlockpdf)
Utility for recovering access to password-protected PDFs in workflows. Written because once a quarter someone hands me a locked PDF of my own and tells me to "just deal with it." The correct response to recurring I/O bottlenecks is to script them out of existence.
**Stack:** Python · Flask · MIT

> More in the lab — a custom Hugging Face model for style-guide rewriting ([style-guide-base](https://github.com/gtrivedi88/style-guide-base) → [`gtrivedi/style-guide-base`](https://huggingface.co/gtrivedi/style-guide-base)), a RAG pipeline for rule enforcement ([rag-style-guide-base](https://github.com/gtrivedi88/rag-style-guide-base)), and a Claude Code agent for DITA migration ([dita-migration-agent](https://github.com/gtrivedi88/dita-migration-agent)). Scroll the pinned tiles for the rest.

---

## Layer 3 · The Architecture Pivot

The next step isn't another writing role. It's **AI Solutions Architecture** — designing the systems that connect models, data pipelines, and human endpoints inside the enterprise. A 365-day structured pivot, executed in public.

### [ai-solution-architect](https://github.com/gtrivedi88/ai-solution-architect) — the syllabus
A 365-day gamified curriculum across four seasons: automation foundations (Make.com, Airtable, Python APIs) → enterprise workflows (ServiceNow CSA) → applied LLMs and responsible AI (LangChain, decision dashboards) → a human-in-the-loop capstone. The whole thing is a Flask app with XP, streaks, and certification milestones — because if I'm going to ask myself to study for a year, the system has to be engineered not to fail.

### [ai-solutions-architect](https://github.com/gtrivedi88/ai-solutions-architect) — the logs
The day-by-day record of actually doing it. `day_1` through `day_n`. Wins, dead-ends, what I learned, what I'd redo. If you're considering a similar pivot from writing/dev/PM into AI architecture, this is the un-edited tape.

---

## Current Execution State

* **Writing:** [the latest on the blog](https://beingtechnicalwriter.com)
* **Building:** the next plugin in [redhat-docs-agent-tools](https://github.com/gtrivedi88/redhat-docs-agent-tools)
* **Studying:** Season 1 of [the architecture syllabus](https://github.com/gtrivedi88/ai-solution-architect)
* **Open to:** AI Solutions Architect roles — specifically routing enterprise documentation, developer experience, or human-in-the-loop systems
* **Reachable:** [LinkedIn](https://www.linkedin.com/in/gauravtrivedi88/) | [@beingtechwriter on X](https://x.com/beingtechwriter)

---

<sub>This page is a living document. If you came back and something changed, that's the point.</sub>
