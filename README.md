# Private Projects Showcase

Code-safe case studies for selected private, commercial and product projects by **Samandar Mansurkhodjaev**.

Most of the projects in this repository are not published with source code because they involve private products, commercial work, client context, sensitive domains or unreleased business logic. This showcase explains the engineering work without exposing private code, secrets, customer data or proprietary implementation details.

## Why This Exists

GitHub is usually code-first, but real engineering work is often private. This repository solves that by documenting:

- what each project does;
- the problem and product context;
- my role and ownership;
- stack and architectural decisions;
- quality signals: tests, CI, Docker, type safety, security/privacy boundaries;
- safe demo/screenshot notes where available.

## Featured Case Studies

| Project | Domain | Stack | Main signal |
|---|---|---|---|
| [Leg-ai / Klawis](case-studies/leg-ai-klawis.md) | Legal-tech AI | FastAPI, Next.js, Supabase, RAG | Product-grade AI assistant with citations and jurisdiction logic |
| [TTYL Platform](case-studies/ttyl-platform.md) | Enterprise collaboration | NestJS, Next.js, PostgreSQL, Redis, MinIO | On-prem project management, chat and files platform |
| [AI Classroom](case-studies/ai-classroom.md) | AI analytics | Python, FastAPI, Pydantic, workers | Evidence-based classroom analytics with privacy-first design |
| [Task Manage Bot](case-studies/task-manage-bot.md) | Telegram automation | Python, aiogram, PostgreSQL, OpenAI | Voice-to-task automation with reminders, queues and retries |
| [med-exe](case-studies/med-exe.md) | Health-tech desktop | Rust, Tauri, React, SQLite | Offline clinical calculation desktop app with clean domain boundaries |
| [Marketbot](case-studies/marketbot.md) | E-commerce automation | Python, gRPC, RabbitMQ, React | Microservice-style offers, subscriptions and Telegram notifications |
| [Softly](case-studies/softly.md) | Consumer product | Next.js, Supabase, PWA | Mobile-first relationship product with realtime/private UX patterns |

## Architecture Principles Across Projects

Across these projects, I usually optimize for:

- clear domain boundaries instead of one large “everything file”;
- typed contracts between frontend, backend and workers;
- privacy-aware handling of sensitive data;
- deterministic business logic where accuracy matters;
- async queues/workers for slow or unreliable external operations;
- clean demos and documentation for non-technical stakeholders;
- architecture that can start as MVP and grow without being rewritten.

## What Is Not Included

This repository intentionally does **not** include:

- private source code;
- customer names or customer data;
- secrets, tokens, `.env` files or internal credentials;
- private algorithms that should not be published;
- screenshots containing sensitive information.

## Quick Positioning

These projects show a profile that is broader than “frontend” or “backend” only:

- **Full-stack engineering:** products from database/API to UI and deployment.
- **AI automation:** RAG, structured outputs, AI workers and validation flows.
- **Product thinking:** UX, business outcomes, iteration speed and demo readiness.
- **System design:** queues, services, auth, storage, observability and privacy.
- **Founder-style execution:** building complete products, not isolated code snippets.
