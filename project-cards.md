# Project Cards

Beautiful, code-safe project cards for selected work by **Samandar Mansurkhodjaev**.

These cards are designed for recruiters, tech leads, founders and clients who need a fast but credible overview: what the project does, why it matters, what stack was used, and what engineering signal it demonstrates.

> Source code is public only where safe. Private/commercial projects are presented through architecture and product case studies without exposing customer data, secrets or proprietary implementation details.

## Shareable One-Page Cards

For cleaner per-project sharing, open the **[Project Card Gallery](cards/README.md)**. It contains separate English/Russian one-page cards for each strong project.

## Quick Index

| Project | Category | Strongest signal |
|---|---|---|
| [Forge / Learning OS](#forge--learning-os) | EdTech / product platform | Founder-style product engineering, evidence engine, portfolio and client-offer workflows |
| [TTYL Platform](#ttyl-platform) | Enterprise collaboration | On-prem system design: projects, chat, files, search, audit and realtime |
| [Klawis](#klawis) | Legal-tech AI | Deployed legal AI with RAG, citations, legal routing and active roadmap |
| [BelfProctor](#belfproctor) | Proctoring / monitoring | Windows client-agent, protected telemetry, admin panel and deployment packaging |
| [VFS Killer Main](#vfs-killer-main) | Browser automation | Playwright/Camoufox automation, Telegram control, diagnostics and Docker runtime |
| [Sentinel Edge](#sentinel-edge--smart-system) | Embedded / IoT | Arduino firmware, serial protocol, Node bridge and realtime React dashboard |
| [Task-manager / Task Manage Bot](#task-manager--task-manage-bot) | Telegram automation | Clean bot architecture, reminders, async jobs and task workflows |
| [med-exe](#med-exe) | Health-tech desktop | Offline Tauri/Rust desktop architecture for sensitive medical logic |
| [Marketbot](#marketbot) | E-commerce automation | Event-driven offers, subscriptions, affiliate links and Telegram notifications |
| [CoupleOS / Softly](#coupleos--softly) | Consumer relationship product | Founder-led live product with emotional UX, privacy and retention mechanics |
| [3d-landing](#3d-landing) | Creative frontend | Three.js/WebGL landing, visual frontend and adaptive performance |

---

## Forge / Learning OS

<p>
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-15-111111?style=flat-square">
  <img alt="React" src="https://img.shields.io/badge/React-19-149eca?style=flat-square">
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-Data%20Model-2d3748?style=flat-square">
  <img alt="Product" src="https://img.shields.io/badge/Signal-Founder%20Product%20Engineering-0f766e?style=flat-square">
</p>

| Field | English | Русский |
|---|---|---|
| What it is | A project-first Learning OS for AI-native builders: projects, missions, evidence, portfolio cases and client-offer workflows in one product. | Product-first Learning OS для AI-native билдеров: проекты, миссии, evidence, portfolio cases и client offers в одной системе. |
| Problem | Most learning platforms measure passive progress, not real capability. Forge turns learning into visible proof: artifacts, gates, cases and proposals. | Большинство образовательных платформ измеряют просмотры и “галочки”, а не реальный навык. Forge превращает обучение в доказательства: артефакты, gates, кейсы и офферы. |
| Architecture | Next.js App Router, Server Actions, Prisma, Auth.js, Zod, typed content seed, service layer, portfolio/proposal routes and verification jobs. | Next.js App Router, Server Actions, Prisma, Auth.js, Zod, typed content seed, сервисный слой, portfolio/proposal routes и verification jobs. |
| Why it matters | Shows founder-style product engineering: not only code, but product logic, UX, domain modeling, learning mechanics and market-facing output. | Показывает founder-style мышление: не только код, но продуктовая логика, UX, доменная модель, механика обучения и результат, который можно показать рынку. |
| Links | [Case study](case-studies/forge-learning-os.md) | [Описание кейса](case-studies/forge-learning-os.md) |

---

## TTYL Platform

<p>
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-Backend-e0234e?style=flat-square">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-Data-336791?style=flat-square">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-Realtime-b91c1c?style=flat-square">
  <img alt="Enterprise" src="https://img.shields.io/badge/Signal-Enterprise%20System%20Design-1d4ed8?style=flat-square">
</p>

| Field | English | Русский |
|---|---|---|
| What it is | A self-hosted collaboration platform for project management, chat, files, search, notifications and audit logs. | Self-hosted collaboration platform для проектов, чатов, файлов, поиска, уведомлений и audit logs. |
| Problem | Some teams need modern collaboration tools but cannot or do not want to move internal data into external SaaS products. | Некоторым командам нужны современные collaboration tools, но они не хотят или не могут отдавать внутренние данные внешним SaaS-платформам. |
| Architecture | Domain-separated platform: identity, workspace/projects, messaging, files, search, notifications, audit, realtime gateway, workers and object storage. | Платформа разделена по доменам: identity, workspace/projects, messaging, files, search, notifications, audit, realtime gateway, workers и object storage. |
| Why it matters | Strong system-design signal: permissions, realtime, files, queues, storage and on-prem deployment are treated as first-class concerns. | Сильный system-design сигнал: права, realtime, файлы, очереди, storage и on-prem deployment продуманы как ключевые части системы. |
| Links | [Case study](case-studies/ttyl-platform.md) | [Описание кейса](case-studies/ttyl-platform.md) |

---

## Klawis

<p>
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-API-009688?style=flat-square">
  <img alt="RAG" src="https://img.shields.io/badge/RAG-Citations-6d28d9?style=flat-square">
  <img alt="LegalTech" src="https://img.shields.io/badge/Domain-LegalTech-334155?style=flat-square">
  <img alt="Live" src="https://img.shields.io/badge/Live-klawis.uz-15803d?style=flat-square">
  <img alt="AI" src="https://img.shields.io/badge/Signal-AI%20Architecture-7c3aed?style=flat-square">
</p>

| Field | English | Русский |
|---|---|---|
| What it is | A deployed legal AI navigator that turns a user situation into structured legal direction, likely jurisdiction, documents, timelines and source-backed explanation. | Задеплоенный Legal AI navigator, который превращает ситуацию пользователя в структурированное юридическое направление: юрисдикция, документы, сроки и объяснение с источниками. |
| Problem | Legal answers must be traceable. A generic chatbot is not enough when accuracy, jurisdiction and citations matter. | Юридические ответы должны быть проверяемыми. Обычного chatbot недостаточно, когда важны точность, юрисдикция и ссылки на источники. |
| Architecture | Deterministic legal routing + retrieval/citations + AI explanation layer + validation/evaluation pipeline. | Deterministic legal routing + retrieval/citations + AI explanation layer + validation/evaluation pipeline. |
| Why it matters | Demonstrates applied AI beyond prompt engineering: domain routing, RAG, citation discipline, active product roadmap and sensitive-domain UX. | Показывает applied AI глубже prompt engineering: доменная маршрутизация, RAG, дисциплина цитирования, roadmap развития и UX для чувствительного домена. |
| Links | [Live product](https://klawis.uz) · [Case study](case-studies/klawis.md) | [Live product](https://klawis.uz) · [Описание кейса](case-studies/klawis.md) |

---

## BelfProctor

<p>
  <img alt="CSharp" src="https://img.shields.io/badge/C%23-Windows%20Agent-512bd4?style=flat-square">
  <img alt="Node" src="https://img.shields.io/badge/Node.js-API-339933?style=flat-square">
  <img alt="React" src="https://img.shields.io/badge/React-Admin-149eca?style=flat-square">
  <img alt="Monitoring" src="https://img.shields.io/badge/Signal-Proctoring%20System-991b1b?style=flat-square">
</p>

| Field | English | Русский |
|---|---|---|
| What it is | A private proctoring and workstation monitoring system with a Windows client-agent, backend ingestion API and admin review panel. | Приватная система прокторинга и мониторинга рабочих станций: Windows client-agent, backend ingestion API и admin review panel. |
| Problem | Real monitoring systems need installation, heartbeat, secure uploads, retry behavior, policy distribution and admin visibility. | Реальная monitoring-система требует установки, heartbeat, защищённых загрузок, retry-логики, policy distribution и админской наблюдаемости. |
| Architecture | Windows service agent, encrypted telemetry/uploads, Node/Express API, PostgreSQL/Prisma, React/Vite admin panel and deployment scripts. | Windows service agent, encrypted telemetry/uploads, Node/Express API, PostgreSQL/Prisma, React/Vite admin panel и deployment scripts. |
| Why it matters | Shows ability to work beyond web UI: client-agent behavior, sensitive telemetry, deployment packaging and operational UX. | Показывает умение работать шире веба: client-agent, чувствительная телеметрия, deployment packaging и operational UX. |
| Links | [Case study](case-studies/belfproctor.md) | [Описание кейса](case-studies/belfproctor.md) |

---

## VFS Killer Main

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-Automation-3776ab?style=flat-square">
  <img alt="Playwright" src="https://img.shields.io/badge/Playwright-Browser%20Control-2f855a?style=flat-square">
  <img alt="Telegram" src="https://img.shields.io/badge/Telegram-Bot-229ed9?style=flat-square">
  <img alt="Diagnostics" src="https://img.shields.io/badge/Signal-Diagnostics%20First-92400e?style=flat-square">
</p>

| Field | English | Русский |
|---|---|---|
| What it is | A private browser-automation system for a high-friction external workflow, controlled through Telegram and supported by diagnostic tools. | Приватная browser-automation система для сложного внешнего workflow, с управлением через Telegram и диагностическими инструментами. |
| Problem | Real browser workflows fail because of timing, sessions, external state, proxy/network issues and anti-automation friction. | Реальные browser workflows ломаются из-за таймингов, сессий, внешнего состояния, proxy/network проблем и anti-automation friction. |
| Architecture | Python workflow engine, Playwright/Camoufox browser layer, Telegram bot interface, Docker runtime, diagnostics and local state boundaries. | Python workflow engine, Playwright/Camoufox browser layer, Telegram bot interface, Docker runtime, diagnostics и границы локального состояния. |
| Why it matters | Demonstrates practical automation under unstable real-world constraints, not just scripting happy paths. | Показывает практическую автоматизацию в нестабильных реальных условиях, а не просто “скрипт для happy path”. |
| Links | [Case study](case-studies/vfs-killer-main.md) | [Описание кейса](case-studies/vfs-killer-main.md) |

---

## Sentinel Edge / smart-system

<p>
  <img alt="Arduino" src="https://img.shields.io/badge/Arduino-Firmware-00878f?style=flat-square">
  <img alt="Node" src="https://img.shields.io/badge/Node.js-Serial%20Bridge-339933?style=flat-square">
  <img alt="React" src="https://img.shields.io/badge/React-Realtime%20Dashboard-149eca?style=flat-square">
  <img alt="IoT" src="https://img.shields.io/badge/Signal-Embedded%20%2B%20Full--stack-0f766e?style=flat-square">
</p>

| Field | English | Русский |
|---|---|---|
| What it is | A local-only smart environment system: Arduino-style firmware, serial telemetry, Node.js bridge and React/Vite operator dashboard. | Локальная smart environment система: Arduino-style firmware, serial telemetry, Node.js bridge и React/Vite operator dashboard. |
| Problem | Embedded demos often stop at sensor readings. This project adds baseline learning, anomaly scoring, FSM states, explainable events and a real operator console. | Embedded-демо часто заканчиваются показом значений датчиков. Здесь есть baseline learning, anomaly scoring, FSM states, explainable events и полноценная operator console. |
| Architecture | C++ firmware modules, compact `TEL`/`EVT`/`CMD` serial protocol, Node WebSocket bridge, bounded React state and realtime charts. | C++ firmware modules, компактный serial protocol `TEL`/`EVT`/`CMD`, Node WebSocket bridge, bounded React state и realtime charts. |
| Why it matters | Shows breadth: embedded constraints, protocol design, realtime dashboard and honest edge-intelligence documentation. | Показывает широту: embedded constraints, protocol design, realtime dashboard и честно описанный edge-intelligence подход. |
| Links | [Public repo](https://github.com/SamandarMansurkhodjaev2713/sentinel-edge-smart-system) · [Case study](case-studies/sentinel-edge.md) | [Публичный repo](https://github.com/SamandarMansurkhodjaev2713/sentinel-edge-smart-system) · [Описание кейса](case-studies/sentinel-edge.md) |

---

## Task-manager / Task Manage Bot

<p>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-Public%20Bot-000000?style=flat-square">
  <img alt="Python" src="https://img.shields.io/badge/Python-AI%20Workflow-3776ab?style=flat-square">
  <img alt="Telegram" src="https://img.shields.io/badge/Telegram-Automation-229ed9?style=flat-square">
  <img alt="Reliability" src="https://img.shields.io/badge/Signal-Reliable%20Automation-166534?style=flat-square">
</p>

| Field | English | Русский |
|---|---|---|
| What it is | A Telegram task automation direction: public Rust task-manager plus private AI-powered Task Manage Bot case study. | Направление Telegram task automation: public Rust Task-manager и приватный AI-powered Task Manage Bot case study. |
| Problem | Tasks created in chats and voice messages are easy to lose without assignment, deadlines, reminders and review loops. | Задачи из чатов и голосовых сообщений легко теряются без назначения, сроков, напоминаний и review loop. |
| Architecture | Bot workflow, task domain logic, database layer, reminders/outbox, retries, idempotency and structured logging. | Bot workflow, task domain logic, database layer, reminders/outbox, retries, idempotency и structured logging. |
| Why it matters | Shows practical automation: turning informal communication into operational workflow with reliability patterns. | Показывает практическую автоматизацию: превращение неструктурированной коммуникации в operational workflow с reliability patterns. |
| Links | [Public repo](https://github.com/SamandarMansurkhodjaev2713/Task-manager) · [Case study](case-studies/task-manage-bot.md) | [Публичный repo](https://github.com/SamandarMansurkhodjaev2713/Task-manager) · [Описание кейса](case-studies/task-manage-bot.md) |

---

## med-exe

<p>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-Core-000000?style=flat-square">
  <img alt="Tauri" src="https://img.shields.io/badge/Tauri-Desktop-24c8db?style=flat-square">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-Offline-003b57?style=flat-square">
  <img alt="Health" src="https://img.shields.io/badge/Signal-Sensitive%20Domain-991b1b?style=flat-square">
</p>

| Field | English | Русский |
|---|---|---|
| What it is | An offline Windows desktop application for cardiometabolic risk calculation and patient profile management. | Offline Windows desktop application для расчёта cardiometabolic risk и управления patient profiles. |
| Problem | Medical/research tools need deterministic logic, reproducibility and privacy-aware local execution. | Медицинские/research-инструменты требуют deterministic logic, reproducibility и privacy-aware локального запуска. |
| Architecture | Tauri desktop shell, React/TypeScript UI, Rust domain/calculation engine, typed IPC and SQLite persistence. | Tauri desktop shell, React/TypeScript UI, Rust domain/calculation engine, typed IPC и SQLite persistence. |
| Why it matters | Demonstrates desktop architecture, Rust domain modeling and clean separation between UI and sensitive calculation logic. | Показывает desktop architecture, Rust domain modeling и чистое разделение UI от чувствительной расчётной логики. |
| Links | [Case study](case-studies/med-exe.md) | [Описание кейса](case-studies/med-exe.md) |

---

## Marketbot

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-Services-3776ab?style=flat-square">
  <img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-Events-ff6600?style=flat-square">
  <img alt="gRPC" src="https://img.shields.io/badge/gRPC-Contracts-244c5a?style=flat-square">
  <img alt="Commerce" src="https://img.shields.io/badge/Signal-Commerce%20Automation-7c2d12?style=flat-square">
</p>

| Field | English | Русский |
|---|---|---|
| What it is | An e-commerce automation platform for collecting offers, managing subscriptions, generating affiliate links and sending Telegram notifications. | E-commerce automation platform для сбора офферов, управления подписками, генерации affiliate links и Telegram-уведомлений. |
| Problem | Offer products need ingestion, filtering, subscriptions, notification delivery, admin visibility and failure handling. | Offer-продукты требуют ingestion, фильтров, подписок, доставки уведомлений, admin visibility и обработки сбоев. |
| Architecture | Microservice-style backend: ingestion, subscriptions, notifications, affiliate service, Telegram bot, admin BFF, gRPC and RabbitMQ. | Microservice-style backend: ingestion, subscriptions, notifications, affiliate service, Telegram bot, admin BFF, gRPC и RabbitMQ. |
| Why it matters | Demonstrates event-driven backend design and operational thinking around commerce notifications. | Показывает event-driven backend design и operational thinking вокруг commerce notifications. |
| Links | [Case study](case-studies/marketbot.md) | [Описание кейса](case-studies/marketbot.md) |

---

## CoupleOS / Softly

<p>
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-App-111111?style=flat-square">
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-Auth%20%2B%20Data-3ecf8e?style=flat-square">
  <img alt="PWA" src="https://img.shields.io/badge/PWA-Mobile--first-5b21b6?style=flat-square">
  <img alt="Founder" src="https://img.shields.io/badge/Role-Founder-be185d?style=flat-square">
  <img alt="Live" src="https://img.shields.io/badge/Live-SoftlyLove.uz-15803d?style=flat-square">
  <img alt="Product" src="https://img.shields.io/badge/Signal-Consumer%20Product%20Thinking-be185d?style=flat-square">
</p>

| Field | English | Русский |
|---|---|---|
| What it is | A founder-led live mobile-first product for couples: emotional check-ins, memories, rituals, private interactions, questions and lightweight relationship flows. | Founder-led live mobile-first продукт для пар: emotional check-ins, воспоминания, rituals, private interactions, вопросы и лёгкие relationship flows. |
| Problem | Relationship products need to feel personal and safe while still having retention mechanics, privacy-aware data handling and fast mobile UX. | Relationship-продукты должны ощущаться личными и безопасными, но при этом иметь retention mechanics, приватную работу с данными и быстрый mobile UX. |
| Architecture | Next.js/React mobile-first app, Supabase auth/database/storage, feature modules, PWA direction, push-notification flow and clear prototype/production boundaries. | Next.js/React mobile-first app, Supabase auth/database/storage, feature modules, PWA direction, push-notification flow и понятные границы prototype/production. |
| Why it matters | Shows founder-style consumer product thinking: emotional UX, privacy, product mechanics, mobile polish, retention and design taste. | Показывает founder-style consumer product thinking: эмоциональный UX, приватность, product mechanics, mobile polish, retention и вкус к дизайну. |
| Links | [Live product](https://softlylove.uz) · [One-page card](cards/coupleos.md) · [Case study](case-studies/coupleos.md) | [Live product](https://softlylove.uz) · [Карточка](cards/coupleos.md) · [Описание кейса](case-studies/coupleos.md) |

---

## 3d-landing

<p>
  <img alt="Three.js" src="https://img.shields.io/badge/Three.js-WebGL-111111?style=flat-square">
  <img alt="Vite" src="https://img.shields.io/badge/Vite-Frontend-646cff?style=flat-square">
  <img alt="Creative" src="https://img.shields.io/badge/Signal-Visual%20Frontend-7e22ce?style=flat-square">
  <img alt="Public" src="https://img.shields.io/badge/Repo-Public-15803d?style=flat-square">
</p>

| Field | English | Русский |
|---|---|---|
| What it is | A cinematic Three.js/WebGL landing with scroll-driven 3D scene, visual storytelling and adaptive performance. | Cinematic Three.js/WebGL landing со scroll-driven 3D scene, visual storytelling и adaptive performance. |
| Problem | Portfolio/frontend projects often look static. This project shows interactive visual engineering and motion-driven presentation. | Portfolio/frontend проекты часто выглядят статично. Этот проект показывает interactive visual engineering и motion-driven presentation. |
| Architecture | Vite frontend, Three.js scene, animation loop, responsive layout and performance-aware asset/rendering choices. | Vite frontend, Three.js scene, animation loop, responsive layout и performance-aware asset/rendering choices. |
| Why it matters | Adds visual range to the portfolio: not only backend/systems, but polished high-impact frontend presentation. | Добавляет визуальную широту портфолио: не только backend/systems, но и polished high-impact frontend presentation. |
| Links | [Public repo](https://github.com/SamandarMansurkhodjaev2713/3d-landing) · [Case study](case-studies/3d-landing.md) | [Публичный repo](https://github.com/SamandarMansurkhodjaev2713/3d-landing) · [Описание кейса](case-studies/3d-landing.md) |

---

## How To Read These Cards

For a recruiter: start with **Forge**, **Sentinel Edge**, **Task-manager**, **CoupleOS / Softly** and **3d-landing** to see breadth, product taste and public proof.

For a tech lead: start with **TTYL Platform**, **Klawis**, **BelfProctor**, **VFS Killer Main**, **Marketbot** and **med-exe** to see architecture, domain complexity and system design.

For a founder/client: start with **Forge**, **CoupleOS / Softly**, **Marketbot**, **Task-manager** and **Klawis** to see product thinking and business workflow automation.

---

# Русская версия: как читать витрину

Для HR: начните с **Forge**, **Sentinel Edge**, **Task-manager**, **CoupleOS / Softly** и **3d-landing** — там быстро видна широта, продуктовый вкус и публичные доказательства.

Для техлида: начните с **TTYL Platform**, **Klawis**, **BelfProctor**, **VFS Killer Main**, **Marketbot** и **med-exe** — там видны архитектура, доменная сложность и системное мышление.

Для founder/client: начните с **Forge**, **CoupleOS / Softly**, **Marketbot**, **Task-manager** и **Klawis** — там лучше всего видны продуктовая логика и автоматизация бизнес-процессов.
