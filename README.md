# Private Projects Showcase

Code-safe case studies and bilingual project cards for selected private, commercial and product projects by **Samandar Mansurkhodjaev**.

Most of the projects in this repository are not published with source code because they involve private products, commercial work, client context, sensitive domains or unreleased business logic. This showcase explains the engineering work without exposing private code, secrets, customer data or proprietary implementation details.

## Why This Exists

GitHub is usually code-first, but real engineering work is often private. This repository solves that by documenting:

- what each project does;
- the problem and product context;
- my role and ownership;
- stack and architectural decisions;
- quality signals: tests, CI, Docker, type safety, security/privacy boundaries;
- safe demo/screenshot notes where available.

## Portfolio Cards

Start here for a fast, polished overview of the strongest projects:

**[Open bilingual project cards](project-cards.md)** — English/Russian cards for Forge, TTYL Platform, Klawis, BelfProctor, VFS Killer Main, Sentinel Edge, Task-manager, med-exe, Marketbot, CoupleOS and 3d-landing.

For separate shareable one-page cards, open the **[Project Card Gallery](cards/README.md)**.

## Featured Case Studies

| Project | Domain | Stack | Main signal |
|---|---|---|---|
| [Klawis](case-studies/klawis.md) | Legal-tech AI | FastAPI, Next.js, Supabase, RAG | Product-grade AI assistant with citations and jurisdiction logic |
| [TTYL Platform](case-studies/ttyl-platform.md) | Enterprise collaboration | NestJS, Next.js, PostgreSQL, Redis, MinIO | On-prem project management, chat and files platform |
| [Forge / Learning OS](case-studies/forge-learning-os.md) | EdTech / AI-native learning | Next.js 15, React 19, Prisma, Auth.js, Zod | Product-first learning platform with evidence engine, portfolio cases and client-offer workflow |
| [Sentinel Edge / smart-system](case-studies/sentinel-edge.md) | Embedded / IoT | Arduino C++, Node.js, React, Vite | Local smart environment system with firmware, serial protocol and realtime dashboard |
| [AI Classroom](case-studies/ai-classroom.md) | AI analytics | Python, FastAPI, Pydantic, workers | Evidence-based classroom analytics with privacy-first design |
| [Task Manage Bot](case-studies/task-manage-bot.md) | Telegram automation | Python, aiogram, PostgreSQL, OpenAI | Voice-to-task automation with reminders, queues and retries |
| [med-exe](case-studies/med-exe.md) | Health-tech desktop | Rust, Tauri, React, SQLite | Offline clinical calculation desktop app with clean domain boundaries |
| [Marketbot](case-studies/marketbot.md) | E-commerce automation | Python, gRPC, RabbitMQ, React | Microservice-style offers, subscriptions and Telegram notifications |
| [CoupleOS](case-studies/coupleos.md) | Consumer relationship product | Next.js, Supabase, PWA | Mobile-first relationship product with private UX and retention mechanics |
| [3d-landing](case-studies/3d-landing.md) | Creative frontend | Three.js, WebGL, Vite | Cinematic landing with scroll-driven 3D scene and frontend polish |
| [BelfProctor](case-studies/belfproctor.md) | Proctoring / monitoring | C#, Node.js, Express, Prisma, PostgreSQL, React | Client-agent, encrypted telemetry, admin panel and Windows deployment |
| [VFS Killer Main](case-studies/vfs-killer-main.md) | Browser automation / VFS workflow | Python, Playwright/Camoufox, aiogram, Docker | High-friction external workflow automation with bot control and diagnostics |

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

---

# Русская версия

Этот репозиторий нужен для того, чтобы показывать сильные приватные и коммерческие проекты без публикации исходного кода. Часть моих самых серьёзных работ нельзя открыть публично: там есть клиентский контекст, приватная бизнес-логика, чувствительные данные, внутренние процессы или ещё не выпущенные продукты.

Вместо публикации кода здесь собраны безопасные case studies:

- что делает проект;
- какую проблему он решает;
- какая была моя зона ответственности;
- какой стек использовался;
- как устроена архитектура;
- почему архитектура выбрана именно так;
- какие инженерные сигналы важны для работодателя или техлида.

## Карточки проектов

Для быстрого просмотра сильнейших проектов откройте:

**[Bilingual project cards](project-cards.md)** — карточки на английском и русском для Forge, TTYL Platform, Klawis, BelfProctor, VFS Killer Main, Sentinel Edge, Task-manager, med-exe, Marketbot, CoupleOS и 3d-landing.

Для отдельных shareable one-page карточек откройте **[Project Card Gallery](cards/README.md)**.

## Что показывают эти проекты

| Направление | Что видно по проектам |
|---|---|
| Full-stack engineering | Я могу вести продукт от базы данных и API до интерфейса, деплоя и документации |
| AI automation | Умею строить RAG, AI workers, structured outputs, аналитические пайплайны и Telegram/операционные AI-боты |
| Сложная автоматизация | Парсеры, browser automation, очереди, retry-логика, диагностика, работа с нестабильными внешними системами |
| Enterprise/system design | Права доступа, аудит, realtime, файлы, storage, очереди, мониторинг, on-prem deployment |
| Product thinking | Думаю не только о коде, но и о бизнес-результате, UX, демонстрации, поддержке и развитии продукта |
| Privacy-aware engineering | Не раскрываю приватный код, клиентские данные, секреты, `.env` и внутренние алгоритмы |

## Ключевые кейсы

| Проект | Домен | Главный сигнал |
|---|---|---|
| [Klawis](case-studies/klawis.md) | Legal-tech AI | AI-ассистент с RAG, цитированием и логикой юрисдикции |
| [TTYL Platform](case-studies/ttyl-platform.md) | Enterprise collaboration | On-prem платформа для проектов, чатов, файлов, поиска и аудита |
| [Forge / Learning OS](case-studies/forge-learning-os.md) | EdTech / AI-native learning | Личный продукт: project-first платформа с evidence engine, портфолио, client offers и админкой |
| [Sentinel Edge / smart-system](case-studies/sentinel-edge.md) | Embedded / IoT | Локальная smart-система с firmware, serial protocol и realtime dashboard |
| [AI Classroom](case-studies/ai-classroom.md) | AI analytics | Аналитика учебного процесса с privacy-first подходом |
| [Task Manage Bot](case-studies/task-manage-bot.md) | Telegram automation | Voice-to-task bot с очередями, напоминаниями и retry-логикой |
| [med-exe](case-studies/med-exe.md) | Health-tech desktop | Offline desktop app с доменной логикой и чистыми границами |
| [Marketbot](case-studies/marketbot.md) | E-commerce automation | Event-driven платформа для офферов, подписок и Telegram-уведомлений |
| [CoupleOS](case-studies/coupleos.md) | Consumer relationship product | Mobile-first продукт для пар с приватным UX, rituals и retention mechanics |
| [3d-landing](case-studies/3d-landing.md) | Creative frontend | Three.js/WebGL landing с визуальным frontend polish |
| [BelfProctor](case-studies/belfproctor.md) | Proctoring / monitoring | Клиент-агент, защищённая телеметрия, админ-панель и Windows deployment |
| [VFS Killer Main](case-studies/vfs-killer-main.md) | Browser automation / VFS workflow | Автоматизация сложного внешнего workflow через browser automation и Telegram bot |
