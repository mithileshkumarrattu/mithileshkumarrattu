# Hi, I’m Methelesh Kumar Rattu 👋

<p align="center">
  <img src="YOUR_HERO_IMAGE_URL_HERE" alt="Methelesh Kumar Rattu — software engineer and product builder" width="100%" />
</p>

<p align="center">
  <a href="mailto:rattumethelesh@gmail.com">Email</a> •
  <a href="https://github.com/mithileshkumarrattu">GitHub</a> •
  <a href="YOUR_LINKEDIN_URL_HERE">LinkedIn</a> •
  <a href="YOUR_PORTFOLIO_URL_HERE">Portfolio</a>
</p>

## About me

I’m a final-year Computer Science Engineering student and an IIT Madras BS Data Science learner who enjoys turning real-world requirements into usable, reliable software.

My work sits at the intersection of:

- Full-stack web applications and product workflows.
- Real-time systems, APIs, payments, and database-backed platforms.
- AI-assisted engineering and retrieval-augmented generation.
- Blockchain and Web3 experiments.
- Deployment, debugging, security, and operational reliability.

I like starting with the user problem, modelling the workflow, designing the interface, implementing the backend/data flow, testing edge cases, and iterating from feedback.

## What I build

| Area | What it means in my work |
|---|---|
| Product applications | Role-based portals, dashboards, forms, learning systems, and operational tools |
| Full-stack systems | React/Next.js interfaces connected to APIs, authentication, databases, and external services |
| Real-time software | WebSocket pipelines, reconnect handling, REST reconciliation, monitoring, and alerts |
| AI applications | Gemini/API integrations, RAG pipelines, embeddings, reranking, and grounded responses |
| Fintech/Web3 | Payment flows, server-side verification, paper-trading systems, ERC-20 testnet experiments |
| Reliability | Transactions, duplicate prevention, audit records, environment variables, logs, and deployment workflows |

## Featured work

### Aadhrita — Techno-Cultural Fest Platform

<p align="center">
  <img src="YOUR_AADHRITA_IMAGE_URL_HERE" alt="Aadhrita project preview" width="90%" />
</p>

A multi-role fest-management platform designed for large-scale participant registration and campus operations.

- Participant registration, event discovery, dynamic forms, and team workflows.
- Student, coordinator, security, campus-manager, and admin roles.
- QR-based entry validation, duplicate-scan prevention, and access audit logs.
- Server-side payment initiation and callback/checksum verification.
- Firestore transactions/atomic writes for sensitive workflow updates.
- Admin dashboards, exports, event management, and operational controls.

**Stack:** Next.js, React, TypeScript, Tailwind CSS, Firebase Auth, Firestore, Paytm, Solidity, ethers.js, Hardhat.

**What I learned:** Real systems need server-side validation, auditability, failure handling, and clear role boundaries—not only a polished UI.

[View repository](https://github.com/mithileshkumarrattu/YOUR_AADHRITA_REPOSITORY)

### MVGR Training & Placement Portal

<p align="center">
  <img src="YOUR_PLACEMENT_PORTAL_IMAGE_URL_HERE" alt="Training and Placement Portal preview" width="90%" />
</p>

A placement workflow platform for recruiter drives, eligibility checks, multi-round candidate progression, and attendance operations.

- Recruiter drive and eligibility management.
- Multi-round candidate advancement workflows.
- Role-based student, recruiter, coordinator, and admin access.
- Firestore transaction-backed updates to reduce race-condition problems.
- Signed QR attendance passes and duplicate-scan prevention.
- Validated during a live event with 480 candidates and 458 verified check-ins.

**Stack:** Next.js, TypeScript, React, Firebase, Firebase Admin SDK, Firestore, QR scanning.

**What I learned:** State transitions must be validated and recorded atomically when multiple users or staff members may update the same workflow.

[View repository](https://github.com/mithileshkumarrattu/YOUR_PLACEMENT_REPOSITORY)

### AlphaCandle — Real-Time FinTech Signal Engine

<p align="center">
  <img src="YOUR_ALPHACANDLE_IMAGE_URL_HERE" alt="AlphaCandle real-time trading system preview" width="90%" />
</p>

A Python-based real-time market-data and paper-trading system operated on a Linux VPS.

- Batched WebSocket subscriptions for a 208-symbol NSE F&O universe.
- Reconnect handling for feed interruptions and stale-connection detection.
- REST-based reconciliation to recover or validate current data state.
- Risk-managed paper-trading logic with stop-distance-based sizing.
- Telegram alerts for feed status, errors, recovery, and diagnostics.
- Remote deployment, process monitoring, logs, and environment-variable management.

**Stack:** Python, Pandas, WebSockets, REST APIs, DhanHQ API, Linux VPS, Telegram Bot API.

**What I learned:** A real-time system needs recovery paths, observability, secure configuration, and operational alerts—not only business logic.

[View repository](https://github.com/mithileshkumarrattu/YOUR_ALPHACANDLE_REPOSITORY)

### EeZ Invest — Learning and Mock-Test Platform

<p align="center">
  <img src="YOUR_EEZINVEST_IMAGE_URL_HERE" alt="EeZ Invest project preview" width="90%" />
</p>

A course, mock-test, admissions, and student-management platform with public, student, and admin workflows.

- Course catalogue, curriculum, student classroom, and mock-test simulator.
- Admin tools for courses, users, admissions, coupons, tests, and announcements.
- Authentication and protected student/admin areas.
- Payment order creation, callback handling, transaction verification, and enrollment workflows.
- Server-side pricing and coupon validation.
- Structured failure, retry, payment-status, and operational flows.

**Stack:** Next.js App Router, React, TypeScript, Firebase Auth, Firestore, Firebase Admin SDK, Paytm, Tailwind CSS, shadcn/UI.

**What I learned:** Payment and enrollment flows must treat the browser as untrusted and use verified server-side state as the source of truth.

[View repository](https://github.com/mithileshkumarrattu/YOUR_EEZINVEST_REPOSITORY)

## AI-assisted engineering

I use AI tools and coding agents as engineering accelerators—not as substitutes for validation or ownership.

My workflow is:

```text
Understand the requirement
        ↓
Research possible approaches
        ↓
Create a small implementation plan
        ↓
Use an AI tool/agent for scaffolding or targeted changes
        ↓
Inspect the diff and data flow
        ↓
Run the application, build, lint, and relevant tests
        ↓
Check security, edge cases, and environment variables
        ↓
Commit a focused change
```

I use AI for:

- Repository exploration and codebase summaries.
- UI scaffolding and component variations.
- API and database-flow suggestions.
- Debugging hypotheses and error analysis.
- Test-case generation.
- Documentation and refactoring ideas.
- RAG experimentation and prompt/context design.

I still verify generated code by reading it, running it, testing failure paths, checking permissions, and reviewing the Git diff.

## RAG and AI systems

I have explored retrieval-augmented generation systems that connect language models to private or project-specific knowledge.

A typical pipeline is:

```text
Documents
   ↓
Chunking and cleaning
   ↓
Embeddings
   ↓
Vector database
   ↓
Similarity retrieval
   ↓
Optional reranking
   ↓
Grounded prompt context
   ↓
LLM response
```

The goal is to improve relevance and grounding while reducing unsupported answers. Important production concerns include source attribution, access control, chunk quality, retrieval evaluation, latency, and fallback behaviour.

## Technical toolkit

### Languages

<p>
  <img src="https://img.shields.io/badge/JavaScript-ES6%2B-f7df1e?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178c6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3.x-3776ab?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Solidity-Ethereum-363636?style=flat-square&logo=solidity&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-Database-4479a1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML%2FCSS-Web-e34f26?style=flat-square&logo=html5&logoColor=white" />
</p>

### Web development

<p>
  <img src="https://img.shields.io/badge/React-UI-61dafb?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-App%20Router-000000?style=flat-square&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-Runtime-339933?style=flat-square&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-APIs-000000?style=flat-square&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-Styling-06b6d4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/shadcn%2FUI-Components-111827?style=flat-square" />
</p>

### Data, cloud, and infrastructure

<p>
  <img src="https://img.shields.io/badge/Firebase-Auth%20%7C%20Firestore-ffca28?style=flat-square&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/PostgreSQL-Supabase-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Pinecone-Vector%20Search-000000?style=flat-square" />
  <img src="https://img.shields.io/badge/Vercel-Deployment-000000?style=flat-square&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Git%20%26%20GitHub-Version%20Control-f05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux%20VPS-Remote%20Services-fcc624?style=flat-square&logo=linux&logoColor=black" />
</p>

### Integrations and platform work

- Firebase Authentication: Google, email/password, and phone-based flows.
- Firestore: document modelling, queries, transactions, and audit records.
- Payment gateways: server-side order creation, callback/webhook verification, and reconciliation.
- QR workflows: pass generation, scanning, validation, and duplicate prevention.
- WebSockets: live data, reconnect handling, and REST reconciliation.
- Blockchain: Solidity, ERC-20, ethers.js, Hardhat, Sepolia testnet, and MetaMask.
- Deployment: Vercel, Firebase, Supabase, environment configuration, and VPS operations.

## Engineering principles

- Understand the user workflow before choosing technology.
- Treat the browser as untrusted for sensitive operations.
- Keep secrets out of source code and Git history.
- Validate input on the server, not only in the UI.
- Make payment/webhook operations idempotent.
- Use transactions for related state changes.
- Design explicit loading, error, retry, and empty states.
- Log important failures without exposing sensitive data.
- Prefer small, reviewable changes over large unverified changes.
- Use AI to accelerate engineering while retaining human review and ownership.

## Currently learning

- Deeper React and TypeScript fundamentals.
- Node.js and backend API design.
- PostgreSQL data modelling and SQL optimisation.
- Automated testing with unit, integration, and end-to-end tests.
- Production observability, CI/CD, and cloud architecture.
- Secure AI/RAG application design.

## A few things I enjoy

- Turning messy requirements into clear workflows.
- Building dashboards and operational tools.
- Debugging production-like failures.
- Exploring AI-assisted development workflows.
- Designing polished interfaces with practical UX.

<p align="center">
  <img src="YOUR_FOOTER_IMAGE_URL_HERE" alt="Thanks for visiting" width="90%" />
</p>
<picture align="center">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tobiasmeyhoefer/tobiasmeyhoefer/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tobiasmeyhoefer/tobiasmeyhoefer/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/tobiasmeyhoefer/tobiasmeyhoefer/output/github-snake.svg" />
</picture>
