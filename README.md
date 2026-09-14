<div align="center">

# 👋 Boudaoud Ishak

### AI & Software Engineer · Data Scientist

*Turning research papers into products that run at 2am without anyone watching them*

📍 Blida, Algeria · ✉️ truly.isaak@gmail.com · ☎️ +213 552 738 007
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ishak-boudaoud-8729ba251)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

</div>

---

## 🧭 The Short Version

Final-year Computer Science Engineering student (Data Science track) who's spent the last two years doing the thing most people only theorize about: **shipping AI systems that touch real users and real money.** Ten-plus freelance projects, one deep RL research system beating a published academic baseline by 18%, and a habit of ending up as the person who owns the pipeline end-to-end — data, model, backend, deployment.

I like problems that don't have a clean textbook answer. Surge pricing across 242 competing zones. Four-language intent detection with almost no NLP tooling built for the combination. That's the fun part.

---

## ⚡ Flagship Work

### Student Researcher
*Student Researcher, Université Saad Dahlab de Blida 1 — May 2026 to Present*

Deep RL for Ride-Hailing Surge Pricing

> Started from a real paper — *"Scalable RL Approaches for Dynamic Pricing in Ride-Hailing Systems"* (Lei & Ukkusuri, 2023) — and built past it.

The setup: **242 NYC zones**, **1,365 simulated vehicles**, a continuous action space, three competing RL algorithms benchmarked against each other (TD3, SAC, PPO).

**What actually moved the needle:**

| Metric | Result |
|---|---|
| 💰 Weekly profit achieved | **$240,949** across 5 independent runs |
| 📈 Improvement over published baseline | **~18% above** |
| 🌦️ Profit lift from weather-aware features alone | **+$71,024 (+41.8%)** |
| 🚖 Simulated passengers served weekly | **~576,805** |

Then it got a real-time monitoring dashboard on top — Kafka, Go, WebSockets, React, Mapbox GL — because a model nobody can *see* working isn't finished. Built under guidance from **Dr. Zengxiang Lei (Purdue University)**.

`Python` `Go` `WebSocket` `Kafka` `TD3` `SAC` `PPO` `React` `Mapbox GL`

---

### 🤖 Freelance AI & Software Engineering
*Self-Employed — Nov 2023 to Present*

Two years, ten-plus shipped projects, one recurring theme: clients come with a business problem, not a tech stack — and I own the full path from raw data to a deployed API.

- 🧠 Custom **AI chatbots & agents** — RAG, tool calling, memory, document ingestion — built for real business automation, not demos
- 📊 AI-powered **web apps & dashboards** for client-facing analytics
- 🎯 **Recommendation engines**, demand/sales forecasting, and real-time **fraud detection** pipelines
- 🚀 Production **REST APIs** and ML deployments, Python/FastAPI end to end

`Python` `FastAPI` `LangChain` `RAG` `Vector DBs` `React` `Docker`

---

## 🛠️ Selected Projects

### 🤖 Multilingual WhatsApp Commerce Automation Platform

> A microservices platform exploring automated conversational commerce over WhatsApp, with the core engineering challenge being reliable intent detection across a mixed-language environment (Algerian Darija, Arabic, French, English) that most NLP tooling isn't designed for — while keeping four independent services consistent in real time.

| | |
|---|---|
| 🧩 | Multi-service architecture (backend, dashboard, messaging gateway, data layer) kept in sync in real time |
| 🧠 | Custom NLP/RAG pipeline for intent detection across four languages/dialects |
| ⚙️ | Agent-driven conversational flows with stateful action execution |
| 🧑‍💼 | Self-service client configuration portal |
| 🔄 | Automated data sync via webhooks |

`Python (FastAPI)` `Next.js` `PostgreSQL` `Redis` `Docker` `WhatsApp` `RAG/NLP`

---

### 🪒 Unified Multi-Vertical Booking & Scheduling Engine

> A booking platform exploring how a single scheduling engine can serve fundamentally different business models — staff-based (appointments) and pool-based (shared-resource) capacity — without either leaking assumptions into the other's data model.

| | |
|---|---|
| 🧮 | Dual-capacity scheduling abstraction (resource-based + pool-based) on one engine |
| 🔒 | PostgreSQL time-range constraints for concurrency-safe booking |
| 📱 | Self-hosted WhatsApp messaging integration |
| 📇 | Phone-based identity/session handling |
| 🪑 | Waitlist with automatic slot recycling |

`React 19` `TypeScript` `Vite` `TailwindCSS` `Supabase (Postgres/Edge Functions/RLS)` `Deno` `Node.js` `Baileys`

---

### 💡 AutoLed Blida — Bilingual Automotive E-Commerce & Booking Platform

> A full-stack bilingual platform for a real automotive lighting business, combining a product storefront, appointment booking, and a complete no-code operations back-office. The engineering challenge is breadth under real business constraints: true RTL/LTR bilingual support down to typography, nationwide delivery-cost logic, and an admin system flexible enough for a non-technical shop owner to run day-to-day.

| | |
|---|---|
| 🌍 | Full French ⇄ Arabic bilingual UI with automatic RTL layout switching |
| 🎬 | Interactive before/after lighting comparison and live product demo animation |
| 🛒 | Order + appointment booking flow with nationwide delivery calculation |
| 🛠️ | No-code admin editing: products, categories, prices, contact info, site announcements |
| 🔐 | Full admin back-office: order tracking, appointments, products, images, delivery prices, CSV export, sales stats |

`React (Vite)` `Node/Express` `TailwindCSS` `Render Deployment`

---

### 🎲 A Note on the Games

Every multiplayer game in this portfolio started the same way: a family or friend gathering, and an off-the-shelf app that didn't fit it. I wanted full control over the experience — the rules, the scale, the difficulty — and something easy enough for beginners to sit down and play immediately.

---

### 🀱 Domino Table — Physical-Freedom Real-Time Multiplayer Dominoes

> Started from a very specific family problem: a standard double-six domino set only has 28 tiles, which caps a real game at 4 players — and family gatherings are rarely exactly 4 people. So instead of just digitizing the classic game, I generalized it: **double-six through double-nine sets**, so the table scales up to fit however many family members and friends actually showed up. The result became a production-grade multiplayer platform that breaks from rigid digital-domino conventions, letting players freely arrange tiles in 2D space on a felt table exactly like the physical game, with a dynamic scoring engine evaluating open chain ends on every move. Every action is validated and serialized server-side to prevent race conditions, hands are cryptographically isolated per-socket, and every state transition is checkpointed to survive server restarts.

| | |
|---|---|
| 👨‍👩‍👧‍👦 | Scalable tile sets (double-six → double-nine) so more than 4 people can play at once |
| 🎲 | True physical-table freedom: tiles placed anywhere on a 2D plane |
| 🔒 | Zero-leak hand masking enforced at the transport layer — verified by a dedicated security test suite |
| 💾 | Persistent, crash-safe state via SQLite (WAL mode), with full reconnection support |
| 🧮 | Two full scoring engines: Classic (pip-sum) and All Fives/Muggins |
| ✅ | 26/26 automated tests passing, including a full multi-client WebSocket simulation |
| 📱 | Mobile-first UI with pinch-zoom/pan felt canvas across 10 distinct game states |

`TypeScript` `React 19` `Node.js` `Socket.io` `SQLite` `Vite` `TailwindCSS`

---

### ♠️ Royal Hold'em — Real-Time Multiplayer Texas Hold'em Poker

> Built for the same reason as the rest: I wanted poker night with full control over the experience — no app-store restrictions, no confusing interfaces that scare off beginners, just a clean table my friends could actually sit down and play at. Underneath that simple goal is a fully server-authoritative poker engine built from scratch. The real difficulty is correctness under complexity: a 7-card hand evaluator disambiguates all 10 hand rankings including tricky edge cases (Ace-5 wheel straights, kicker ties), and side-pot resolution for uneven all-in stacks is combinatorially fiddly — a classic source of bugs even in commercial platforms.

| | |
|---|---|
| 🃏 | Complete 7-card hand evaluator, all 10 rankings, full edge-case handling |
| 💰 | Full side-pot and multi-way pot resolution for uneven stacks |
| 🔒 | Zero-leak architecture — hole cards sent only to their owner's socket |
| 🔁 | Session-based reconnection with no lost seats or progress |
| ✅ | Automated test suite (hand evaluation + full game-cycle simulation) |

`Node.js` `Express` `Socket.io` `JavaScript`

---

### 🍾 Bottle Race — Real-Time Multiplayer Matching Game

> Another full-control build: a simple, beginner-friendly party game anyone can pick up in seconds, no explanation needed — just join the room and race. The core engineering challenge is concurrency: every client must start at the exact same synchronized instant and stream live progress without drift, while a deterministic ranking engine resolves ties identically across every client even under real network latency.

| | |
|---|---|
| 🏁 | Host-configurable rooms with 6 difficulty tiers and QR-code invites |
| ⚡ | Fully synchronized start with live opponent progress tracking |
| 🏆 | Deterministic tiebreak ranking engine (completion → time → errors → shared ranks) |
| 🎯 | Automatic finish detection, no submit button |

`Node.js` `WebSocket` `JavaScript`

---

### 🛍️ Storefront — Vanilla JS E-Commerce Prototype

> A lightweight e-commerce front-end built without any framework — cart, checkout, and admin logic implemented from first principles.

`JavaScript` `HTML/CSS`

---

### 🕵️ Undercover — Party Game, Reimagined

> Most Undercover apps draw from a small, fixed word pool — play a few rounds with the same group and you start seeing repeats, which kills the fun fast. I rebuilt it with a much larger, customizable word bank and my own game logic, so the same group of family or friends can play round after round without the game running dry.

`HTML/CSS/JS`

---

## 🎓 Education

**Engineering Degree in Computer Science — Data Science Track**
Saad Dahleb University, Blida 1, Algeria · 4th Year (2022 – Present)

---

## 🌍 Languages

🇩🇿 **Arabic** — Native &nbsp;·&nbsp; 🇫🇷 **French** — Intermediate &nbsp;·&nbsp; 🇬🇧 **English** — Intermediate

---

<div align="center">

*Open to interesting problems — especially the ones that don't fit in a textbook.*

📧 **truly.isaak@gmail.com**

</div>
