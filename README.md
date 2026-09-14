<div align="center">

# 👨‍💻 Ishak Boudaoud

### **AI & Systems Engineer · Data Scientist**
*Turning research and complex engineering problems into production-grade systems.*

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&pause=1000&color=00D2FF&center=true&vCenter=true&width=750&height=40&lines=%24+sys.deploy(model%3D'Deep_RL'%2C+action_space%3D'continuous'%2C+zones%3D242);%24+db.enforce(constraint%3D'EXCLUDE_USING_GIST'%2C+race_condition%3Dfalse);%24+nlp.resolve_intent(dialects%3D%5B'Darija'%2C+'Arabic'%2C+'French'%2C+'English'%5D);%24+stream.telemetry(pipeline%3D%5B'Go'%2C+'Kafka'%2C+'WebSockets'%5D)" alt="Terminal Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ishak-boudaoud-8729ba251)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:truly.isaak@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/isaaxk)
[![Location](https://img.shields.io/badge/Blida%2C%20Algeria-24292F?style=flat-square&logo=googlemaps&logoColor=white)](#)
[![Views](https://komarev.com/ghpvc/?username=isaaxk&style=flat-square&color=00D2FF&label=PROFILE+VIEWS)](https://github.com/isaaxk)

</div>

---

### 🧭 Overview

Final-year Computer Science Engineering student (**Data Science track**) at *Université Saad Dahlab de Blida 1* with **2+ years** of hands-on experience building and shipping production software. 

I focus on problems where standard off-the-shelf tools fall short:
- **Reinforcement learning agents** competing across high-dimensional, continuous-action spaces.
- **Multilingual NLP pipelines** engineered for unstandardized, code-switched dialects (Algerian Darija, Arabic, French, English).
- **High-concurrency distributed engines** where race conditions and data integrity are enforced at the database kernel level rather than fragile application code.

---

### ⚡ Flagship Research: Deep RL for Ride-Hailing Surge Pricing

> Based on *"Scalable RL Approaches for Dynamic Pricing in Ride-Hailing Systems"* (Lei & Ukkusuri, 2023) — extended with continuous action spaces and weather-aware features under the guidance of **Dr. Zengxiang Lei (Purdue University)**.

| Metric | Result | Benchmark Context |
|:---|:---:|:---|
| 💰 **Weekly Profit Achieved** | **\$240,949** | Across 5 independent random seeds |
| 📈 **Published Paper Lift** | **+18.0%** | Outperformed published benchmark |
| 🌦️ **Weather Feature Lift** | **+\$71,024 (+41.8%)** | Over identical non-weather configuration |
| 🚖 **Simulated Scale** | **~576,805** | Passengers served weekly across **242 NYC zones** (1,365 vehicles) |
| ⚡ **Telemetry Pipeline** | **<50ms** | End-to-end streaming fare pipeline (Go + WebSockets + Kafka) |

`Python` `PyTorch` `TD3` `SAC` `PPO` `Go` `Apache Kafka` `WebSockets` `React` `Mapbox GL` `Docker`

---

### 🧬 Technical Depth: How I Build

*Beyond simple feature lists, here is the engineering behind the systems I build:*

| Domain | Architectural Challenge | Engineering Solution |
|:---|:---|:---|
| **Distributed Systems** | Multi-service consistency in real time | Designed a 4-tier microservices architecture (FastAPI, Next.js, gateway, data layer) kept synchronized via deterministic webhook triggers and Redis caching. |
| **Concurrency & Integrity** | Preventing double-booking in shared pools | Replaced brittle application-layer locks with native **PostgreSQL time-range exclusion constraints** (`EXCLUDE USING GIST`) directly in the database engine. |
| **Server-Authoritative State** | Cheating prevention in multiplayer systems | Built zero-trust WebSocket state machines where tile placements and hole cards are masked at the transport layer — verified by dedicated automated security test suites. |
| **Continuous Geometry** | Physics-grounded board game validation | Developed a continuous 2D plane geometry validator supporting arbitrary tile angles and generalized sets (double-6 through double-9) rather than simple linear arrays. |
| **Fault Tolerance** | Session persistence under connection drops | Implemented crash-safe state checkpointing with **SQLite WAL mode** and session-token resumption, eliminating game or transaction loss on drops. |
| **Mixed-Dialect NLP** | Intent detection with zero training corpora | Built a dialect-resilient RAG/NLP pipeline specifically tuned for mixed **Algerian Darija, Arabic, French, and English** code-switching. |

---

### 🛠️ Tech Stack & Toolchain
