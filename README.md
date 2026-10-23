<h1 align="center">Haseeb Tariq</h1>
<p align="center"><b>AI &amp; Automation Engineer</b> · Lahore, Pakistan (GMT+5) · Remote</p>

<p align="center">
  I build AI systems that run in production, not demos: autonomous agents, AI receptionists,
  browser-automation pipelines and full-stack platforms used by real teams every day.
</p>

<p align="center">
  <a href="mailto:contactbyhaseeb@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-contactbyhaseeb%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/haseeb-tariq099"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-haseeb--tariq099-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/haseeb9933?tab=repositories"><img alt="Repositories" src="https://img.shields.io/badge/All%20repos-haseeb9933-181717?style=flat-square&logo=github&logoColor=white"></a>
</p>

---

## What I do

| | |
|---|---|
| **AI agents & LLM apps** | Multi-agent systems and tool-calling agents with LangChain / LangGraph / CrewAI, RAG over private data, structured outputs, human-in-the-loop gates. |
| **Voice & chat receptionists** | 24/7 intake bots on OpenAI + ElevenLabs + Twilio that qualify leads, book appointments and hand off to humans. |
| **Browser automation & scraping** | Selenium / Playwright / DrissionPage bots with persistent sessions, anti-detection and clean structured output. |
| **Workflow automation** | n8n / Make pipelines with retries, alerts and recovery built in, plus tooling that debugs and auto-fixes them. |
| **Full-stack AI products** | Next.js + FastAPI / Fastify + Supabase, deployed on Render or Vercel, with auth, RBAC and reporting. |

---

## Featured work

### Platforms

| Project | What it is | Stack | Code |
|---|---|---|---|
| **Momentum** | Internal project-tracking and resource-planning platform at Digital Nexa that replaced Forecast.it. Live in production for 190 projects and 58 team members. P&L and margin reporting, four-tier budget alerts, drag-to-extend allocation, timesheet locking, event-driven email. | Next.js 14, Fastify, TypeScript, Supabase Postgres, Render | Private (employer) |
| **NEXA Ops Handbook** | Authenticated company handbook for ~75 staff: SOPs, platform logins, team directory, docs, onboarding checklists, global search and a ⌘K command palette. | Next.js 15, React 19, Supabase SSR auth, Tailwind, Radix | Private (employer) |
| **Convo AI** | Turns client chat logs and GA4 analytics into private, tokenised AI-insight dashboards. Scheduled ingest, Claude for sentiment / topic / intent, admin panel for onboarding. | FastAPI, SQLAlchemy 2, PostgreSQL, Anthropic API, APScheduler | Private (employer) |
| **Ops Hub (The Factory)** | Team operations hub: AI task extraction from meeting notes via a 3-agent pipeline with a Governor step, real-time channel chat, WebRTC voice calls, voice messages, invoicing and an RBAC admin panel. | React 18, FastAPI, Supabase, WebRTC, Claude, GPT-4o | [haseeb-portfolio/schmoozzer-hub](https://github.com/haseeb9933/haseeb-portfolio/tree/main/schmoozzer-hub) |

### AI agents and automation

| Project | What it is | Stack | Code |
|---|---|---|---|
| **Axon Bridge** | Web console that runs n8n workflows, streams live logs and browser frames over WebSockets, detects failures, performs LLM root-cause analysis and applies autonomous Selenium fixes in a retry loop. | React, Vite, FastAPI, Selenium, asyncio, Gemini / OpenAI | [haseeb-portfolio/Axon-Bridge](https://github.com/haseeb9933/haseeb-portfolio/tree/main/Axon-Bridge) |
| **AI Receptionist** | n8n-orchestrated voice and chat receptionist: intent classification, FAQ answers, appointment booking into Google Calendar, lead capture to Sheets, email alerts and human handoff. | n8n, OpenAI, ElevenLabs, Twilio, Google Calendar / Sheets | [Receptionist](https://github.com/haseeb9933/Receptionist) |
| **NOVA, n8n copilot** | Chrome extension sidecar that watches the n8n editor, deduplicates errors, captures the engineer's hypothesis and fix, builds a Supabase knowledge base and answers with a context-aware GPT-4o-mini chat. | Chrome MV3, JavaScript, Supabase, OpenAI | [haseeb-portfolio/NOVA](https://github.com/haseeb9933/haseeb-portfolio/tree/main/NOVA) |
| **Bidsquare outreach bot** | Downloads YouTube videos, transcribes with Whisper, extracts frames, identifies valuable antiques with Claude and posts expert comments with randomised strategies and rate limits. | Python, FastAPI, Playwright, Claude, Whisper, n8n | [haseeb-portfolio/bidsquare](https://github.com/haseeb9933/haseeb-portfolio/tree/main/bidsquare) |
| **LinkedIn-to-Email automation** | Selenium scraper for dynamic, infinite-scroll pages with persistent login; 10,000+ leads deduplicated through Sheets state; Gemini drafts a personalised email per lead behind a human approval gate before Gmail sends it. | n8n, Selenium, Gemini, Gmail API | Private (client) |
| **TikTok news video pipeline** | News URL in, review-ready 1080×1920 MP4 out: GPT-4o script, Leonardo visuals, ElevenLabs narration, SRT captions from character-level timestamps, human review checkpoint. | n8n, GPT-4o, Leonardo AI, ElevenLabs, Shotstack | Private (client) |

### Browser automation, trading and data

| Project | What it is | Stack | Code |
|---|---|---|---|
| **LinkedIn Automation API** | API-key-protected Flask REST service: comment with human-like typing and duplicate detection, follow with connection-request fallback, extract posts with engagement metadata. | Flask, Selenium, Chrome profile / cookie auth | [haseeb-portfolio/linkedin--automation](https://github.com/haseeb9933/haseeb-portfolio/tree/main/linkedin--automation) |
| **TikTok & Instagram scraper** | FastAPI endpoint over headless Selenium that returns profile and post data as clean JSON, parsing 10.5K / 2.1M style counts into integers. | Python, FastAPI, Selenium, BeautifulSoup | [tiktok-instagram-scraper](https://github.com/haseeb9933/tiktok-instagram-scraper) |
| **Rubber Band trading bot** | Binance Futures bot running a 13-stage martingale / Fibonacci strategy with bracket orders, fill webhooks synced to an n8n state machine, email alerts and a stage-12 stop-loss, plus a backtesting suite. | Python, FastAPI, SQLite, Binance WebSocket / REST, n8n | [haseeb-portfolio/Binance](https://github.com/haseeb9933/haseeb-portfolio/tree/main/Binance) |
| **Retail Sales Dashboard** | End-to-end retail analysis: Pandas cleaning and EDA, Seaborn visualisations and an interactive Power BI dashboard for stakeholders. | Python, Pandas, Seaborn, Power BI | [Retail-Sales-Data-Dashboard](https://github.com/haseeb9933/Retail-Sales-Data-Dashboard) |
| **ML & forecasting notebooks** | Stock-price prediction, US real-estate valuation, macro time series, startup-growth and restaurant datasets, each with feature engineering, training and evaluation. | Python, scikit-learn, Pandas, deep learning | [Full_Stack_AI__Haseeb](https://github.com/haseeb9933/Full_Stack_AI__Haseeb) |

Every project in [haseeb-portfolio](https://github.com/haseeb9933/haseeb-portfolio) ships with runnable code, an `.env.example` and a full technical documentation file.

---

## Experience

| | | |
|---|---|---|
| **Digital Nexa** (Dubai, remote) | AI Engineer | Mar 2026 – present |
| **Schmoozzer** (Ecuador, remote) | AI Engineer | Sep 2025 – Mar 2026 |
| **EnlightSystems** (Islamabad) | AI Intern | Jul 2025 – Sep 2025 |
| **CodAgentic** (remote) | AI Intern | May 2025 – Jul 2025 |

Also co-engineer at **3X AI Automation**, an AI automation agency. Site source: [3x-aiautomation-portfolio](https://github.com/haseeb9933/3x-aiautomation-portfolio).

---

## Stack

**AI / LLM** · LangChain · LangGraph · CrewAI · OpenAI GPT-4o · Anthropic Claude · Gemini · ElevenLabs · Whisper · RAG · structured outputs

**Automation** · n8n · Make · Zapier · Selenium · Playwright · Puppeteer · DrissionPage · BeautifulSoup · Twilio · HubSpot · Google APIs

**Backend** · Python · FastAPI · Flask · Node.js · Fastify · Express · WebSockets · asyncio · PostgreSQL · Supabase · SQLite

**Frontend** · TypeScript · React · Next.js 14/15 · Tailwind · Chrome Extensions (MV3)

**Infra** · Docker · AWS (EC2, S3) · Vercel · Render · Turborepo · GitHub Actions · Nginx + systemd

<p align="center">
  <img alt="GitHub stats" height="165" src="https://github-readme-stats.vercel.app/api?username=haseeb9933&show_icons=true&hide_border=true&hide_title=true&theme=transparent">
  <img alt="Top languages" height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=haseeb9933&layout=compact&hide_border=true&theme=transparent">
</p>

---

## Working with me

Open to full-time roles, contracts and freelance builds in AI agents, automation and full-stack AI products.
Send the problem you are trying to solve to **contactbyhaseeb@gmail.com** and I will tell you straight whether I am the right fit.
