<h1 align="center">Ashutosh Shukla</h1>

<p align="center">
  I build things that run in production, not just in demos.
</p>

<p align="center">
  <a href="https://github.com/Ashutosh-Shukla-036">GitHub</a> ·
  <a href="https://www.linkedin.com/in/ashutosh-shukla-1189b625b/">LinkedIn</a> ·
  <a href="https://leetcode.com/u/Ashutoshshukla_123">LeetCode</a> ·
  <a href="https://ashutoshshuklaportfolio.vercel.app">Portfolio</a>
</p>

---

I like working close to the metal — deployment pipelines, system reliability, database internals, Linux server automation. If it touches production and something can go wrong, that's where I want to be.

Currently interning at **LeapMile Robotics**, building backend infrastructure for real robotic systems. Before that I shipped a self-hosted PaaS, a chess engine with Redis caching, and a full-stack media platform — all running live.

---

### What I'm working on

- **Nexus** — a self-hosted PaaS I built from scratch. `git push` → stack detection → systemd orchestration → Nginx routing → live. Automatic rollback on failure. Zero manual steps. Validated across FastAPI, Express, React, and Next.
- Building observability into production systems at LeapMile — metrics, log pipelines, real-time dashboards.

---

### Projects

**[Nexus – Self-Hosted PaaS](https://github.com/Ashutosh-Shukla-036/Nexus)**

> Your own Heroku, on your own server.

Automated the entire deploy pipeline from `git push` to live service — stack detection, systemd service orchestration, Nginx routing, and rollback on failure. Built a real-time dashboard with WebSocket-based journal log streaming, uptime checks, and a Linux service control API. Zero manual intervention across 4 language stacks.

`FastAPI` `PostgreSQL` `asyncpg` `Nginx` `systemd` `React` `WebSockets` `Linux`

---

**[ChessMind – Real-time Chess Analysis](https://github.com/Ashutosh-Shukla-036/Chess)** · [Live](https://ashutoshshuklaportfolio.vercel.app)

> Stockfish in your browser, without melting the server.

Streamed async move evaluations over WebSockets via background threading. Built a fault-tolerant Stockfish engine pool with auto-recycling after 100 requests (no memory leaks in long sessions). Redis caching with SHA-256 keys cut repeat analysis latency by **80%**.

`FastAPI` `Redis` `WebSockets` `Docker` `Stockfish` `React` `TypeScript`

---

**[Aprameya – Film Showcase Platform](https://aprameyaproductions.vercel.app)**

> Production-grade, not portfolio-grade.

Multi-layer caching cut API response time by **25%** under peak load. JWT auth, RBAC, full-text search, advanced filtering — the full stack, shipped and live.

`Node.js` `Express` `MongoDB` `React` `TypeScript` `Tailwind` `JWT`

---

### Day job

**Software Engineer Intern — LeapMile Robotics** · Jan 2026 – Present

- Killed per-request pool creation by architecting a shared PostgreSQL connection pool singleton + schema cache — meaningfully reduced connection overhead across services
- Hunted down and fixed production-critical database bugs in robotic execution pipelines
- Automated remote Linux deployments with pyinfra — Nginx, systemd, SSH, the whole stack

---

### Stack
Languages  →  Python · TypeScript · JavaScript · Java · SQL
Backend    →  FastAPI · Node.js · Express · WebSockets · REST · JWT
Infra      →  Linux · Docker · Nginx · systemd · pyinfra · SSH · CI/CD
Databases  →  PostgreSQL · Redis · MongoDB · asyncpg · Connection Pooling
Frontend   →  React · Tailwind CSS

---

### Misc

- Top 1% @ Tem-E-Thon 2025 (3000+ participants) · Finalist @ VYUHA National Hackathon
- 2nd place — Sustainable Innovation Tech Competition, Skyline University (Dubai)
- Filed an innovation patent in 2025 for a smart rainwater harvesting system (yes, really)
- I play chess. ChessMind exists partly because of that.
