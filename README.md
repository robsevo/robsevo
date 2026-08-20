<h1 align="center">Robert Sevo</h1>

<p align="center">
  <b>Full-Stack Developer</b> · React · TypeScript · Python · Agentic AI<br>
  📍 Montréal, QC · Bilingual FR / EN
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/robsevo/">LinkedIn</a> ·
  <a href="mailto:robsevo11@gmail.com">Email</a>
</p>

---

## ⚡ I build software that deletes busywork

Self-taught, and I ship end-to-end: React / Next.js front ends, Node and Python services, continuous
deployment, and the unglamorous work of keeping it all running once real people depend on it.

My favourite problems are the ones hiding inside somebody's manual process. The spreadsheet four people
maintain by hand. The checklist nobody follows. The report that eats a morning. Those are usually one
good tool away from being a non-issue, and finding that leverage is the part of the job I actually enjoy.

I work through an agentic, AI-assisted workflow with LLM coding agents and MCP tooling, and I've built
the agent tooling itself, which is a good way to learn exactly how much you should trust it.

Before software: a decade in telecom, technical training, and software QA. It left me with a bias toward
testing things properly, reporting numbers honestly, and building software non-technical people can
actually use without a manual.

---

## 🛠️ What I'm building

### 📺 `tvspot` · streaming that keeps working when the streams don't
*Next.js 15 · React 19 · Vercel · Samsung Tizen*

Mobile-first on-demand and live video, solo from first commit to production traffic. The interesting part
isn't the player, it's everything behind it: a verification service that probes multiple HLS sources in
parallel, scores them, and fails over from dead endpoints before a viewer notices, plus a nightly
pipeline that keeps the verified list fresh so nobody has to babysit it. Ships to living rooms through
Tizen (`.wgt`) and Fire TV wrappers, where a five-button remote is the entire input budget.

### 🤖 `Serge` · a coding agent that shops for its own models
*TypeScript · Bun · MCP*

An open-source terminal agent rebuilt into a cost-aware, multi-model router. Every turn goes to the
cheapest model that can actually handle it, a scarce deep-reasoning seat is held back for the hard ones,
and a different-vendor seat reviews the output, so it runs at near-zero cost and nothing ships unchecked.
Also has guardrail hooks, cross-session memory, and a portable offline build with systemd / launchd /
Windows installers.

### 🏒 `Barnguru` · a hockey season, simulated a possession at a time
*Python · FastAPI · Next.js · Rust*

Monte Carlo simulation engine with a performance-critical Rust core exposed to Python through PyO3 /
maturin, profiled first and rewritten in Rust only where the measurement justified it. Polars and DuckDB
feed predictive models (scikit-learn, XGBoost, Bayesian), scored out-of-sample against a baseline before
anything reaches the dashboard. Largest and longest-running of my projects.

### 📊 `HUB VOX` · 57,000 formulas standing in for a database
*Excel / LibreOffice · zero macros*

The employee training/skill tracking system for the Air Transat account: twelve sheets, macro-free,
identical behaviour in Excel and LibreOffice, tracking a 177-agent roster across Montreal and Tunisia as
one ID-keyed source of truth instead of a pile of hand-maintained trackers. It carries the KPI dashboard
leadership reads and flags at-risk agents P1 / P2 / P3 against a day-by-day objective curve, so nobody
reads twelve cohorts by hand. Constraint-driven work: no macros permitted, no database available, and
every single user non-technical.

### 📝 `Note Builder` · click the scenario, get the note
*Vanilla JavaScript · zero dependencies*

A guided decision tree covering 11 support scenarios, from flight itineraries to hotel cancellations,
that turns manual note-writing and decision fatigue into a few clicks. No framework, no build step,
entirely client-side, so it loads instantly and works with nothing installed and nothing to maintain.

<sub>Also built: native Android TV apps in Kotlin with Media3 ExoPlayer and Retrofit.</sub>

---

## 🧰 Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-D97757?style=flat-square)

| | |
|---|---|
| **Languages** | TypeScript / JavaScript · Python · SQL / MySQL · Rust · Bash |
| **Frontend** | React 19 · Next.js 15 (App Router) · Tailwind · HLS.js · Framer Motion · Samsung Tizen |
| **Backend & Data** | Node.js / Bun · FastAPI · REST · JWT auth · system design · Polars · DuckDB |
| **Ship it** | Linux · Docker · Vercel · GitHub Actions · CircleCI · Git · Playwright |
| **AI & Agents** | MCP · Anthropic & OpenAI SDKs · multi-model routing · prompt and token-budget work |

---

## 🎯 What I'm into

AI-native development · intelligent automation · developer tooling · and finding those little bits of
leverage that turn hours of busywork into a few clicks, and occasionally make someone say:

> *"Wait, it does that automatically?"*

---

<sub>Most of my work lives in private repositories; code walkthroughs and live demos available on request.</sub>
