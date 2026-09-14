<div align="center">

# 👋 Boudaoud Ishak

#### *AI & Software Engineer · Data Scientist* ####

 ### ***Open to interesting problems — especially the ones that don't fit in a textbook.***

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

## 🧭 About Me

Final-year CS Engineering student (Data Science track) shipping AI systems that solve real problems for real businesses, and a habit of owning the full pipeline from data to deployment. I go looking for problems without a clean textbook answer: reinforcement learning agents competing across hundreds of zones, language models that have to understand a mix no off-the-shelf tool was built for — that's exactly where I want to be.

---

## ⚡ Flagship Work

### 🤖 Freelancer AI & Software Engineering
*Self-Employed — Nov 2023 to Present*

Two years, ten-plus shipped projects, one recurring theme: clients come with a business problem, not a tech stack — and I own the full path from raw data to a deployed API.

- 🧠 Custom **AI chatbots & agents** — RAG, tool calling, memory, document ingestion — built for real business automation, not demos
- 📊 AI-powered **web apps & dashboards** for client-facing analytics
- 🎯 **Recommendation engines**, demand/sales forecasting, and real-time **fraud detection** pipelines
- 🚀 Production **REST APIs** and ML deployments, Python/FastAPI end to end

`Python` `FastAPI` `LangChain` `RAG` `Vector DBs` `React` `Docker`

---

### Student Researcher
*Université Saad Dahlab de Blida 1 — May 2026 to Present*

Deep RL for Ride-Hailing Surge Pricing
> Extended Lei & Ukkusuri (2023) to optimize continuous surge pricing across **242 NYC zones** (1,365 vehicles) using **TD3, SAC, and PPO**, guided by **Dr. Zengxiang Lei (Purdue)**.

- 💰 **Weekly Profit:** **$240,949** (~18% above published baseline across 5 runs).
- 🌦️ **Weather Lift:** **+$71,024 (+41.8%)** profit increase over non-weather configurations.
- ⚡ **Telemetry Dashboard:** Real-time fare streaming built with Go, Kafka, WebSockets, React & Mapbox GL.

`Python` `Go` `WebSocket` `Kafka` `TD3` `SAC` `PPO` `React` `Mapbox GL`

---
---
---
---
# 🛠️ Some Selected Projects

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

### ⏱️ Unified Multi-Vertical Booking & Scheduling Engine

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

### 💡 AutoLed — Bilingual Automotive E-Commerce & Booking Platform

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

### 🎲 Real-Time Server-Authoritative Game Engines
Suite of competitive multiplayer web games designed with strict zero-trust client architectures, low-latency networking, and persistent fault tolerance:

- 🀱 **[all-five-domino](https://github.com/isaaxk/all-five-domino)** — Physical-freedom multiplayer dominoes with a 2D continuous placement geometry validator (free angles, non-grid), generalized sets from double-6 to double-9 ($>4$ players), zero-leak socket transport isolation, and SQLite (WAL) crash-safe checkpoints.  
  `TypeScript` `React 19` `Node.js` `Socket.io` `SQLite` `TailwindCSS`

- ♠️ **[Royal-Flush](https://github.com/isaaxk/Royal-Flush)** — Fully server-authoritative Texas Hold'em poker engine featuring a full 7-card hand evaluator for all 10 rankings (handling wheel straight & kicker edge cases), combinatorial side-pot resolution for uneven all-ins, and session-based mid-hand reconnection.  
  `Node.js` `Express` `Socket.io` `JavaScript` &nbsp;·&nbsp; 🔗 **[Live Game →](https://isaak-poker.onrender.com/)** · **[Repository →](https://github.com/isaaxk/Royal-Flush)**
- 🍾 **[bottles-n-puzzles](https://github.com/isaaxk/bottles-n-puzzles)** — Synchronized real-time multiplayer party game with sub-second synchronized room starts across varying client network jitter, live drift-free progress streaming, and deterministic tiebreak ranking engines.  
  `Node.js` `WebSockets` `JavaScript` &nbsp;·&nbsp; 🔗 **[Live Game →](https://ishak-s-puzzles.onrender.com)** · **[Repository →](https://github.com/isaaxk/bottles-n-puzzles)**
- 🕵️ **[undercover-1.7](https://github.com/isaaxk/undercover-1.7)** — Re-engineered secret-role party game with hidden-role state machines, non-repetitive categorized word banks, and custom voting/elimination logic.  
  `HTML/CSS` `JavaScript` &nbsp;·&nbsp; 🔗 **[Live Game →](https://isaaxk.github.io/ishak_games/)** · **[Repository →](https://github.com/isaaxk/undercover-1.7)**

### 🚕 [Dynamic Price Optimization — Deep RL for Ride-Hailing](https://github.com/isaaxk/ME)
End-to-end continuous surge pricing system benchmarking **TD3, SAC, and PPO** across 242 NYC zones. Features weather-aware observation spaces (+\$71K profit lift), an ultra-low latency **Go + WebSocket** fare streaming engine, and an interactive **React + Mapbox GL** demand heatmap.
> `Python` `Go` `Kafka` `WebSockets` `TD3` `SAC` `PPO` `React` `Mapbox GL` `Docker`

### 🛍️ [ShopDZ — Algerian E-Commerce Platform](https://github.com/isaaxk/bigg-market)

> Lightweight e-commerce platform built from first principles with zero framework overhead — tailored for the Algerian market with nationwide cash-on-delivery across 58 wilayas.
 🛒  Multi-category catalog browsing (Fashion, Tech, Home, Sports, Toys ...) with persistent cart state 
 ⚡  Pure Vanilla JS architecture 

`JavaScript` `HTML5` `CSS3` `Netlify` &nbsp;·&nbsp; 🔗 **[Live Demo →](https://ishaak-shop-dz.netlify.app/)** · **[Repository →](https://github.com/isaaxk/bigg-market)**



## 🧬 Technical Depth

Beyond the feature lists, here's the engineering that actually made these systems hard to build:

| Domain | Advanced Technique |
|---|---|
| 🌐 Distributed Systems | Multi-service architectures (FastAPI + Next.js + gateway + Postgres/Redis) kept **consistent in real time** across independent services |
| 🔐 Concurrency & Security | Server-authoritative state machines with **per-socket hand isolation**, verified by dedicated security test suites — not just "trust the client" |
| 🗄️ Data Integrity | **PostgreSQL time-range constraints** enforced at the database level to make double-booking structurally impossible, not just app-layer-checked |
| 🎯 Reinforcement Learning | Continuous-action-space RL across **242 competing zones** and 1,365 agents; benchmarked **TD3, SAC, PPO** against each other rather than picking one blind |
| ⚡ Real-Time Infrastructure | Kafka + Go + WebSockets for low-latency streaming pipelines; sub-second synchronized starts across clients under real network jitter |
| 🧮 Algorithmic Correctness | Full 7-card poker hand evaluator (all 10 rankings, wheel straights, kicker ties) and side-pot resolution for uneven all-in stacks — notoriously bug-prone even in commercial platforms |
| 🧠 NLP/RAG | Custom intent-detection pipeline across **four languages/dialects** (Darija, Arabic, French, English) with no off-the-shelf tooling built for that combination |
| 💾 Fault Tolerance | Crash-safe, checkpointed state (SQLite WAL mode) with full session-based reconnection — no game or transaction lost on a dropped connection or server restart |

---

<div align="center">

📧 **truly.isaak@gmail.com**

</div>
