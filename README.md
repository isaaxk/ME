<div align="center">
# 🚀 Projects Showcase
 
*A collection of full-stack platforms, real-time multiplayer systems, and automation tools*
 
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
 
</div>
---
 
## 🤖 Multilingual WhatsApp Commerce Automation Platform
 
> A microservices platform exploring automated conversational commerce over WhatsApp, with the core engineering challenge being reliable intent detection across a mixed-language environment (Algerian Darija, Arabic, French, English) that most NLP tooling isn't designed for — while keeping four independent services consistent in real time.
 
**Highlights**
 
| | |
|---|---|
| 🧩 | Multi-service architecture (backend, dashboard, messaging gateway, data layer) kept in sync in real time |
| 🧠 | Custom NLP/RAG pipeline for intent detection across four languages/dialects |
| ⚙️ | Agent-driven conversational flows with stateful action execution |
| 🧑‍💼 | Self-service client configuration portal |
| 🔄 | Automated data sync via webhooks |
 
`Python (FastAPI)` `Next.js` `PostgreSQL` `Redis` `Docker` `WhatsApp` `RAG/NLP`
 
---
 
## 🪒 Unified Multi-Vertical Booking & Scheduling Engine
 
> A booking platform exploring how a single scheduling engine can serve fundamentally different business models — staff-based (appointments) and pool-based (shared-resource) capacity — without either leaking assumptions into the other's data model.
 
**Highlights**
 
| | |
|---|---|
| 🧮 | Dual-capacity scheduling abstraction (resource-based + pool-based) on one engine |
| 🔒 | PostgreSQL time-range constraints for concurrency-safe booking |
| 📱 | Self-hosted WhatsApp messaging integration |
| 📇 | Phone-based identity/session handling |
| 🪑 | Waitlist with automatic slot recycling |
 
`React 19` `TypeScript` `Vite` `TailwindCSS` `Supabase (Postgres/Edge Functions/RLS)` `Deno` `Node.js` `Baileys`
 
---
 
## 💡 AutoLed Blida — Bilingual Automotive E-Commerce & Booking Platform
 
> A full-stack bilingual platform for a real automotive lighting business, combining a product storefront, appointment booking, and a complete no-code operations back-office. The engineering challenge is breadth under real business constraints: true RTL/LTR bilingual support down to typography, nationwide delivery-cost logic, and an admin system flexible enough for a non-technical shop owner to run day-to-day.
 
**Highlights**
 
| | |
|---|---|
| 🌍 | Full French ⇄ Arabic bilingual UI with automatic RTL layout switching |
| 🎬 | Interactive before/after lighting comparison and live product demo animation |
| 🛒 | Order + appointment booking flow with nationwide delivery calculation |
| 🛠️ | No-code admin editing: products, categories, prices, contact info, site announcements |
| 🔐 | Full admin back-office: order tracking, appointments, products, images, delivery prices, CSV export, sales stats |
 
`React (Vite)` `Node/Express` `TailwindCSS` `Render Deployment`
 
---
 
## 🀱 Domino Table — Physical-Freedom Real-Time Multiplayer Dominoes
 
> A production-grade multiplayer dominoes platform that breaks from rigid digital-domino conventions, letting players freely arrange tiles in 2D space on a felt table exactly like the physical game — while a dynamic scoring engine evaluates open chain ends on every move. Every action is validated and serialized server-side to prevent race conditions, hands are cryptographically isolated per-socket, and every state transition is checkpointed to survive server restarts.
 
**Highlights**
 
| | |
|---|---|
| 🎲 | True physical-table freedom: tiles placed anywhere on a 2D plane |
| 🔒 | Zero-leak hand masking enforced at the transport layer — verified by a dedicated security test suite |
| 💾 | Persistent, crash-safe state via SQLite (WAL mode), with full reconnection support |
| 🧮 | Two full scoring engines: Classic (pip-sum) and All Fives/Muggins |
| ✅ | 26/26 automated tests passing, including a full multi-client WebSocket simulation |
| 📱 | Mobile-first UI with pinch-zoom/pan felt canvas across 10 distinct game states |
 
`TypeScript` `React 19` `Node.js` `Socket.io` `SQLite` `Vite` `TailwindCSS`
 
---
 
## ♠️ Royal Hold'em — Real-Time Multiplayer Texas Hold'em Poker
 
> A fully server-authoritative poker engine built from scratch. The real difficulty is correctness under complexity: a 7-card hand evaluator disambiguates all 10 hand rankings including tricky edge cases (Ace-5 wheel straights, kicker ties), and side-pot resolution for uneven all-in stacks is combinatorially fiddly — a classic source of bugs even in commercial platforms.
 
**Highlights**
 
| | |
|---|---|
| 🃏 | Complete 7-card hand evaluator, all 10 rankings, full edge-case handling |
| 💰 | Full side-pot and multi-way pot resolution for uneven stacks |
| 🔒 | Zero-leak architecture — hole cards sent only to their owner's socket |
| 🔁 | Session-based reconnection with no lost seats or progress |
| ✅ | Automated test suite (hand evaluation + full game-cycle simulation) |
 
`Node.js` `Express` `Socket.io` `JavaScript`
 
---
 
## 🍾 Bottle Race — Real-Time Multiplayer Matching Game
 
> A synchronized multiplayer puzzle game where every player races the identical sequence in real time. The core challenge is concurrency: every client must start at the exact same synchronized instant and stream live progress without drift, while a deterministic ranking engine resolves ties identically across every client even under real network latency.
 
**Highlights**
 
| | |
|---|---|
| 🏁 | Host-configurable rooms with 6 difficulty tiers and QR-code invites |
| ⚡ | Fully synchronized start with live opponent progress tracking |
| 🏆 | Deterministic tiebreak ranking engine (completion → time → errors → shared ranks) |
| 🎯 | Automatic finish detection, no submit button |
 
`Node.js` `WebSocket` `JavaScript`
 
---
 
## 🛍️ Storefront — Vanilla JS E-Commerce Prototype
 
> A lightweight e-commerce front-end built without any framework — cart, checkout, and admin logic implemented from first principles.
 
`JavaScript` `HTML/CSS`
 
---
 
## 🕵️ Undercover — Party Game, Reimagined
 
> A browser-based version of the classic social deduction party game, rebuilt with custom mechanics.
 
`HTML/CSS/JS`
 
---
 
<div align="center">
*More details available on request*
 
</div>
 
