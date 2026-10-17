Manish Soni — Software engineer
=================================

Backend engineering, full‑stack development, and pragmatic AI integrations.

---

About
-----

I build backend systems and APIs that prioritize reliability, clear interfaces, and measurable behavior. My work aims to move ideas to production with a focus on maintainable code, sensible defaults, and testable services.

Core technologies
-----------------

Java · JavaScript · C++ · SQL

React · Node.js · Express.js · MySQL · MongoDB

REST APIs · Git · Docker · AWS fundamentals · LLM integration

---

What I can build
-----------------

- Production-ready REST APIs and backend services with automated tests and clear error handling.
- Full-stack web products with pragmatic frontends and server-side correctness.
- AI‑integrated features that connect LLMs or inference APIs to deterministic backend logic.

---

Featured projects
-----------------

1) NeuraChat — AI collaborative coding environment
   - Problem: Real-time, context-aware assistant for developer workflows.
   - Tech: Frontend (HTML/JS), Backend (Node.js, Express), LLM integration (see repo).
   - Repo: https://github.com/manish23092003/Neura-Chat
   - Live demo: (no public deployment linked in repo)
   - Engineering note: README highlights work to "improve response time and user experience" — the project prioritizes API design and latency management for multi-turn interactions.

2) AgentFlow — Autonomous procurement agent (Algorand x402 testnet)
   - Problem: Automating discovery, evaluation, and managed payments for premium research resources.
   - Tech: Monorepo—React frontend, Node.js/Express backend, PostgreSQL + Prisma, Algorand TestNet integrations.
   - Repo: https://github.com/manish23092003/agentflow
   - Live demo: (no public deployment linked in repo)
   - Engineering note: Uses a deterministic state‑machine orchestrator for research flows and implements x402 payment handling—an explicit design choice to keep procurement workflows auditable and resumable.

3) Smart Expense Tracker API — Backend API with tests
   - Problem: Simple, testable expense tracking API with clear validation and documented endpoints.
   - Tech: Node.js, Express, Swagger UI, Jest/Supertest integration tests.
   - Repo: https://github.com/manish23092003/smart-expense-tracker-api
   - Live demo: (runs locally; API docs available via /api-docs per project README)
   - Engineering note: README documents separation of server and app and a testing-first approach; the code uses async file I/O and explicit rounding to ensure numeric precision.

4) Copy Unlocker — Chrome extension
   - Problem: Restore selection & copying on pages that intentionally or accidentally block these actions.
   - Tech: Manifest V3 extension, content scripts, lightweight vanilla JS.
   - Repo: https://github.com/manish23092003/copy-unlocker
   - Live demo: install locally (see project README for load-unpacked instructions).
   - Engineering note: The extension is explicitly designed to run fully locally without external APIs—this keeps privacy and security simple and auditable.

5) AI Test Generator — Test generation (in development)
   - Problem: Generate and run unit tests automatically for Python code using AST + AI assistance.
   - Tech: FastAPI backend, Pytest execution, React frontend (Monaco editor) — see repo for architecture.
   - Repo: https://github.com/manish23092003/AI-Test-Generator
   - Live demo: (not deployed)
   - Engineering note: Combines deterministic AST parsing with LLM-driven cases; README documents a safe, sandboxed execution model for generated tests.

---

Try the projects locally
------------------------

Clone and inspect any project to run it locally. Example:

    git clone https://github.com/manish23092003/smart-expense-tracker-api.git
    cd smart-expense-tracker-api
    # follow the project's README for install & run steps

Each repository linked above includes setup & run instructions in its own README. I keep runnable instructions inside project repositories so you can verify behavior and inspect tests immediately.

---

How to evaluate fit
-------------------

- Need a backend engineer who writes testable, well‑documented services: look at smart-expense-tracker-api (tests + swagger).
- Need an engineer who can integrate LLMs pragmatically into product flows: NeuraChat and AI-Test-Generator show LLM integration with backend controls.
- Need someone who can prototype browser tooling: copy-unlocker demonstrates minimal, privacy-first browser extension work.

---

Inspect my code
---------------

All project source is available under my GitHub account: https://github.com/manish23092003

If you want a guided walkthrough of any project (design choices, APIs, or architecture), tell me which one and I will prepare a short technical brief.

---

Design & maintenance notes
--------------------------

- This profile emphasizes readable structure, minimal visual noise, and direct links to working repositories.
- No external images or badges are included so the README remains robust across GitHub themes and mobile.
- Keep entries short; expand project descriptions inside each repository where implementation detail belongs.
