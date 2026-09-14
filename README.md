<div align="center">

# 👋 Boudaoud Ishak

## AI & Software Engineer · Data Scientist

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

## 🧭 The Short Version

Final-year CS Engineering student (Data Science track) shipping AI systems that solve real problems for real businesses, and a habit of owning the full pipeline from data to deployment. I go looking for problems without a clean textbook answer: reinforcement learning agents competing across hundreds of zones, language models that have to understand a mix no off-the-shelf tool was built for — that's exactly where I want to be.

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
---


## 🛠️ Other Selected Projects

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

---

### 🀱 Domino Table — Physical-Freedom Real-Time Multiplayer Dominoes

> Started from a very specific problem: a standard double-six domino set only has 28 tiles, which caps a real game at 4 players — and family gatherings are rarely exactly 4 people. So I generalized it: **double-six, double-seven ... double-nine sets** and added many features and customizations.

**The complex parts:**
- **Free-placement geometry, not a fixed grid.** Physical dominoes don't snap to a grid — players put tiles anywhere on a 2D felt surface, at any angle, from either end of a branching chain. That means every move has to be geometrically validated (does this tile's pip value actually match an open end at this position?) rather than just checked against a linear array like most digital domino games do.
- **Generalized rule engine across five tile sets.** Double-six, seven, eight, and nine sets don't just add more tiles — they change the pip-value range, the total tile count, and the math behind valid matches. The scoring and move-validation logic had to be written generically against tile-set size rather than hardcoded for 28 tiles.
- **Server-authoritative concurrency.** Every placement, draw, and pass is validated and serialized server-side so two players can't act on the same open end in a race condition — critical once you allow more than 4 simultaneous players.
- **Zero-leak hand isolation.** Each player's tiles are only ever sent to their own socket — verified with a dedicated security test suite, not just assumed safe because "the client won't render it."
- **Crash-safe state.** Every state transition is checkpointed to SQLite (WAL mode), so a server restart or a dropped connection mid-game doesn't wipe out a match — a real risk with 5+ players and longer game sessions.
- **Dual scoring engines.** Classic (pip-sum) and All Fives/Muggins (multiples-of-five on open chain ends) are structurally different scoring models, both implemented and kept in sync with the same move engine.

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

> Built for the same reason as the rest: I wanted poker night with full control over the experience. Underneath that simple goal is a fully server-authoritative poker engine.

**The complex parts:**
- **7-card hand evaluation across all 10 rankings.** With 2 hole cards + 5 community cards, the evaluator has to find the *best possible* 5-card hand out of 21 combinations, correctly handling notorious edge cases: the Ace-5 "wheel" straight (A-2-3-4-5, where the Ace counts low), and tie-breaking by kicker cards when two players hold the same hand category.
- **Side-pot resolution for uneven all-ins.** When players go all-in with different stack sizes, the pot has to split into a main pot and one or more side pots, each with its own eligible-player list — a combinatorial problem that's a well-known source of bugs even in commercial poker platforms.
- **Server-authoritative state, zero trust in the client.** Every bet, fold, call, and raise is validated server-side against the current betting round and stack sizes — the client never decides what's a legal action.
- **Zero-leak hole cards.** Each player's hole cards are transmitted only to their own socket, so there's no way to inspect an opponent's cards even via browser DevTools.
- **Session-based reconnection mid-hand.** If a player's connection drops mid-hand, they can reconnect to the same seat with the same stack and cards — instead of losing their spot or forfeiting the pot.

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

> Another full-control build: a simple, beginner-friendly party game anyone can pick up in seconds, no explanation needed — just join the room and race.

**The complex parts:**
- **True synchronized start across clients.** Every player has to begin the identical sequence at the exact same instant, despite each client having a different network latency to the server — a naive "send start signal" approach means players effectively start at different times.
- **Live progress streaming without drift.** As players race, their progress has to update on every other client in near real time, without the state gradually desyncing over the course of a round.
- **Deterministic tie resolution under real-world timing noise.** With network jitter, two players can appear to finish at nearly the same server timestamp — the ranking engine has to apply a strict, deterministic tiebreak order (completion → time → errors → shared ranks) so every client computes the *identical* final ranking, not just "whoever's packet arrived first."

| | |
|---|---|
| 🏁 | Host-configurable rooms with 6 difficulty tiers and QR-code invites |
| ⚡ | Fully synchronized start with live opponent progress tracking |
| 🏆 | Deterministic tiebreak ranking engine (completion → time → errors → shared ranks) |
| 🎯 | Automatic finish detection, no submit button |

`Node.js` `WebSocket` `JavaScript`

---

### 🕵️ Undercover — Party Game, Reimagined

> Most Undercover apps draw from a small, fixed word pool — play a few rounds with the same group and you start seeing repeats, which kills the fun fast. I rebuilt it with a much larger, customizable word bank and my own game logic, so the same group of family or friends can play round after round without the game running dry.

- **Hidden-role state management.** Each player has a different, secret role (civilian, undercover, sometimes a blank) tied to a shared-but-slightly-different word pair — the game state has to track who knows what without ever leaking a role to the wrong client.
- **Scalable, non-repetitive word bank.** A large, categorized word-pair bank had to be built and structured so the game can pull fresh, appropriately-difficult pairs round after round without obvious repeats or mismatched difficulty.
- **Custom elimination/voting logic.** Turn order, voting, and elimination all had to be built as a real state machine — handling ties, re-votes, and edge cases like everyone voting for themselves — rather than hardcoded for one fixed player count.

`HTML/CSS/JS`

---

### 🛍️ Storefront — Vanilla JS E-Commerce Prototype

> A lightweight e-commerce front-end built without any framework — cart, checkout, and admin logic implemented from first principles.

`JavaScript` `HTML/CSS`

---

## 🧬 Technical Depth

Beyond the feature lists, here's the engineering that actually made these systems hard to build:

| Domain | Advanced Technique |
|---|---|
| 🎯 Reinforcement Learning | Continuous-action-space RL across **242 competing zones** and 1,365 agents; benchmarked **TD3, SAC, PPO** against each other rather than picking one blind |
| 🌐 Distributed Systems | Multi-service architectures (FastAPI + Next.js + gateway + Postgres/Redis) kept **consistent in real time** across independent services |
| 🔐 Concurrency & Security | Server-authoritative state machines with **per-socket hand isolation**, verified by dedicated security test suites — not just "trust the client" |
| 🗄️ Data Integrity | **PostgreSQL time-range constraints** enforced at the database level to make double-booking structurally impossible, not just app-layer-checked |
| ⚡ Real-Time Infrastructure | Kafka + Go + WebSockets for low-latency streaming pipelines; sub-second synchronized starts across clients under real network jitter |
| 🧮 Algorithmic Correctness | Full 7-card poker hand evaluator (all 10 rankings, wheel straights, kicker ties) and side-pot resolution for uneven all-in stacks — notoriously bug-prone even in commercial platforms |
| 🧠 NLP/RAG | Custom intent-detection pipeline across **four languages/dialects** (Darija, Arabic, French, English) with no off-the-shelf tooling built for that combination |
| 💾 Fault Tolerance | Crash-safe, checkpointed state (SQLite WAL mode) with full session-based reconnection — no game or transaction lost on a dropped connection or server restart |

---

## 🛠️ Full Stack Snapshot

<table>
<tr><td width="150"><b>AI / ML</b></td><td>Deep RL (SAC, TD3, PPO) · LLMs · RAG · AI Agents · NLP · Time-Series Forecasting · Recommender Systems · Anomaly/Fraud Detection</td></tr>
<tr><td><b>Languages</b></td><td>Python · JavaScript · TypeScript · C · Java</td></tr>
<tr><td><b>Frameworks</b></td><td>LangChain · TensorFlow/Keras · PyTorch · Scikit-learn · FastAPI · Flask · React · Node.js · Express.js</td></tr>
<tr><td><b>Data & Infra</b></td><td>Apache Kafka · WebSockets · PostgreSQL · MongoDB · MySQL · Redis · Vector Databases · Docker · Kubernetes · Prometheus · Grafana</td></tr>
<tr><td><b>System Design</b></td><td>REST · GraphQL · Microservices · Event-driven Architecture · Real-time, concurrency-safe systems</td></tr>
</table>

---

<div align="center">


📧 **truly.isaak@gmail.com**

</div>
