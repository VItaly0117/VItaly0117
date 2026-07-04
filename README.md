### Hi, I'm Vitalii 👋

Junior Python/Backend developer (AI-leaning), also comfortable with .NET.
Applied Physics student at Cherkasy National University, building real
things instead of tutorial projects — and reporting honest results even
when they're not flattering.

I work AI-augmented every day. Claude Code is part of my normal workflow,
but I always review and understand what it generates before it ships.

---

### 🔭 What I've built

**[Cerberus](https://github.com/VItaly0117/cerberus)** — a statistical-arbitrage
paper-trading bot for Polymarket. Watches order books in real time over
WebSockets, detects taker-arbitrage opportunities, simulates FOK/FAK
execution with a fee model and risk manager, reports results over Telegram.

- 106 automated tests
- Ran a 72-hour live paper-trading validation, caught real bugs during it
  (fee-formula error, NULL edge cases, misconfigured retry caps)
- Honest result after fixing them: **-0.9% to -1.4% net edge** — the
  strategy is structurally unprofitable at current fees, and that's
  reported here on purpose, not hidden

**[Project Sentinel](https://github.com/VItaly0117/project-sentinel)** — a
trading-runtime MVP for Bybit with a modular time-series training pipeline
behind it.

- Deterministic trading logic (XGBoost confidence layer or rule-based
  z-score mean reversion), dry-run-first safety design
- 30 runtime tests + 17 training-pipeline tests + 17 data-ingest tests
- Dockerized multi-bot deployment (PostgreSQL, read-only FastAPI dashboard,
  per-bot schema isolation), with a documented VPS deployment/rollback guide

Same discipline runs through both: catch what makes your own numbers look
better than they are, before you trust them.

---

### 🧰 Stack

Python (asyncio, FastAPI, XGBoost, pandas) · C# / .NET 8 · TypeScript ·
PostgreSQL · Docker · SQL

### 📫 Reach me

kalinichenko.vitalii123@gmail.com · [LinkedIn](www.linkedin.com/in/віталій-калініченко-7a0321358) <!-- add your LinkedIn URL here -->

Looking for a fully remote Junior Python/Backend or Junior .NET role.
