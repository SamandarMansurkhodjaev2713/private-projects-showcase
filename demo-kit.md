# Demo & Interview Kit

Demo and interview playbook for showing selected work by **Samandar Mansurkhodjaev**.

Use this document when someone asks: "What projects should I look at?", "What exactly did you build?", "Can you show your architecture?", or "Why is the code private?"

For live links, GitHub Actions proof and screenshot/video priorities, also open the [Visual Evidence Pack](visual-evidence-pack.md).

## Safe Demo Rules

1. Do not show customer names, private infrastructure, `.env`, credentials, private datasets or internal business rules.
2. Prefer project cards, sanitized screenshots, architecture diagrams, short videos and live demos only when the demo environment is clean.
3. For commercial/private projects, show the product idea, role, stack, architecture and decision reasoning instead of source code.
4. For public projects, show README, structure, key modules, docs, tests and running demo if available.
5. If a question requires sensitive detail, answer at the architecture level and explain what cannot be disclosed.

## Правила безопасного показа

1. Не показывать названия клиентов, private infrastructure, `.env`, credentials, private datasets и внутреннюю бизнес-логику.
2. Использовать project cards, sanitized screenshots, architecture diagrams, короткие видео и live demo только если среда полностью очищена.
3. Для коммерческих и приватных проектов показывать идею продукта, роль, стек, архитектуру и причины решений вместо исходного кода.
4. Для публичных проектов показывать README, структуру, key modules, docs, tests и running demo, если он есть.
5. Если вопрос требует чувствительных деталей, отвечать на уровне архитектуры и прямо объяснять, что раскрывать нельзя.

## Audience Routes

| Audience | 3-minute route | 10-15 minute route |
|---|---|---|
| HR / Recruiter | Profile README -> [Project cards](project-cards.md) -> [Forge](cards/forge-learning-os.md) -> [Sentinel Edge](cards/sentinel-edge.md) | Add [CoupleOS / Softly](cards/coupleos.md), [3d-landing](cards/3d-landing.md), [Task-manager](cards/task-manage-bot.md) |
| Tech lead | [TTYL](cards/ttyl-platform.md) -> [Klawis](cards/klawis.md) -> [BelfProctor](cards/belfproctor.md) | Add [VFS Killer Main](cards/vfs-killer-main.md), [Marketbot](cards/marketbot.md), [med-exe](cards/med-exe.md), [Sentinel Edge](cards/sentinel-edge.md) |
| Founder / Client | [Forge](cards/forge-learning-os.md) -> [Marketbot](cards/marketbot.md) -> [Task Manage Bot](cards/task-manage-bot.md) | Add [Klawis](cards/klawis.md), [VFS Killer Main](cards/vfs-killer-main.md), [CoupleOS / Softly](cards/coupleos.md) |
| Investor / Partner | [Forge](cards/forge-learning-os.md) -> [CoupleOS / Softly](cards/coupleos.md) -> [TTYL](cards/ttyl-platform.md) | Add [Klawis](cards/klawis.md), [Sentinel Edge](cards/sentinel-edge.md), [3d-landing](cards/3d-landing.md) |

## Маршруты показа

| Аудитория | Маршрут на 3 минуты | Маршрут на 10-15 минут |
|---|---|---|
| HR / рекрутер | Profile README -> [Project cards](project-cards.md) -> [Forge](cards/forge-learning-os.md) -> [Sentinel Edge](cards/sentinel-edge.md) | Добавить [CoupleOS / Softly](cards/coupleos.md), [3d-landing](cards/3d-landing.md), [Task-manager](cards/task-manage-bot.md) |
| Техлид | [TTYL](cards/ttyl-platform.md) -> [Klawis](cards/klawis.md) -> [BelfProctor](cards/belfproctor.md) | Добавить [VFS Killer Main](cards/vfs-killer-main.md), [Marketbot](cards/marketbot.md), [med-exe](cards/med-exe.md), [Sentinel Edge](cards/sentinel-edge.md) |
| Founder / клиент | [Forge](cards/forge-learning-os.md) -> [Marketbot](cards/marketbot.md) -> [Task Manage Bot](cards/task-manage-bot.md) | Добавить [Klawis](cards/klawis.md), [VFS Killer Main](cards/vfs-killer-main.md), [CoupleOS / Softly](cards/coupleos.md) |
| Инвестор / партнёр | [Forge](cards/forge-learning-os.md) -> [CoupleOS / Softly](cards/coupleos.md) -> [TTYL](cards/ttyl-platform.md) | Добавить [Klawis](cards/klawis.md), [Sentinel Edge](cards/sentinel-edge.md), [3d-landing](cards/3d-landing.md) |

## 30-Second Opening

### English

I build complete technical products: frontend, backend, AI workflows, automation, Telegram bots, dashboards, desktop/mobile apps and deployment. I am a 3rd-year Software Engineering Bachelor's student at IT Park University. Some projects are public, and the private/commercial ones are documented here as safe case studies with architecture, stack, reasoning and demo guidance.

### Русский

Я создаю законченные технические продукты: frontend, backend, AI workflows, automation, Telegram-ботов, dashboards, desktop/mobile приложения и deployment. Я учусь на 3 курсе бакалавриата Software Engineering в IT Park University. Часть проектов публичная, а приватные и коммерческие проекты оформлены здесь как безопасные case studies со стеком, архитектурой, причинами решений и demo guidance.

## Project Demo Scripts

| Project | Show first | What to say | Engineering signal |
|---|---|---|---|
| Forge / Learning OS | [Card](cards/forge-learning-os.md), [case study](case-studies/forge-learning-os.md) | "This is my product-first learning platform: projects, missions, evidence, portfolio and client offers." | Product architecture, domain modeling, founder-style execution |
| TTYL Platform | [Card](cards/ttyl-platform.md), [case study](case-studies/ttyl-platform.md) | "This is an on-prem collaboration platform with projects, chat, files, search, notifications and audit." | Enterprise full-stack architecture, realtime, permissions, storage |
| Klawis | [Card](cards/klawis.md), [live](https://klawis.uz), [case study](case-studies/klawis.md) | "This is a deployed legal AI product where the answer must be structured, source-backed and safer than a generic chatbot." | RAG, citations, deterministic routing, active roadmap, sensitive-domain UX |
| BelfProctor | [Card](cards/belfproctor.md), [case study](case-studies/belfproctor.md) | "This is a proctoring/monitoring system with Windows agent, backend ingestion and admin review panel." | Agent/backend/admin separation, telemetry, deployment thinking |
| VFS Killer Main | [Card](cards/vfs-killer-main.md), [case study](case-studies/vfs-killer-main.md) | "This is browser automation for an unstable external workflow controlled through Telegram." | Playwright/Camoufox automation, diagnostics, retries, external state |
| Sentinel Edge | [Card](cards/sentinel-edge.md), [public repo](https://github.com/SamandarMansurkhodjaev2713/sentinel-edge-smart-system) | "This is a local smart-system with C++ firmware, serial protocol, Node bridge and realtime React dashboard." | Embedded + full-stack breadth, protocol design, realtime UI |
| Task Manage Bot | [Card](cards/task-manage-bot.md), [case study](case-studies/task-manage-bot.md) | "This turns chat/voice messages into structured tasks with reminders and async processing." | Practical AI automation, queues, reminders, idempotency |
| med-exe | [Card](cards/med-exe.md), [case study](case-studies/med-exe.md) | "This is an offline desktop app where calculation logic and local privacy matter." | Rust/Tauri, typed IPC, deterministic domain logic |
| Marketbot | [Card](cards/marketbot.md), [case study](case-studies/marketbot.md) | "This is commerce automation with ingestion, subscriptions, affiliate links and notifications." | Event-driven backend, RabbitMQ/gRPC, service boundaries |
| CoupleOS / Softly | [Card](cards/coupleos.md), [live](https://softlylove.uz), [case study](case-studies/coupleos.md) | "This is my founder-led mobile-first consumer product for couples with emotional UX, privacy and retention mechanics." | Founder ownership, consumer product thinking, mobile UX, privacy-aware data boundaries |
| 3d-landing | [Card](cards/3d-landing.md), [public repo](https://github.com/SamandarMansurkhodjaev2713/3d-landing) | "This shows visual frontend: Three.js/WebGL, motion and polished product presentation." | Creative frontend, visual polish, performance-aware rendering |

## Скрипты демонстрации проектов

| Проект | Что открыть | Что сказать | Инженерный сигнал |
|---|---|---|---|
| Forge / Learning OS | [Card](cards/forge-learning-os.md), [case study](case-studies/forge-learning-os.md) | "Это мой product-first Learning OS: projects, missions, evidence, portfolio и client offers." | Product architecture, domain modeling, founder-style execution |
| TTYL Platform | [Card](cards/ttyl-platform.md), [case study](case-studies/ttyl-platform.md) | "Это on-prem collaboration platform с projects, chat, files, search, notifications и audit." | Enterprise full-stack architecture, realtime, permissions, storage |
| Klawis | [Card](cards/klawis.md), [live](https://klawis.uz), [case study](case-studies/klawis.md) | "Это задеплоенный legal AI продукт, где ответ должен быть structured, source-backed и безопаснее обычного chatbot." | RAG, citations, deterministic routing, active roadmap, sensitive-domain UX |
| BelfProctor | [Card](cards/belfproctor.md), [case study](case-studies/belfproctor.md) | "Это proctoring/monitoring система: Windows agent, backend ingestion и admin review panel." | Agent/backend/admin separation, telemetry, deployment thinking |
| VFS Killer Main | [Card](cards/vfs-killer-main.md), [case study](case-studies/vfs-killer-main.md) | "Это browser automation для нестабильного внешнего workflow с управлением через Telegram." | Playwright/Camoufox automation, diagnostics, retries, external state |
| Sentinel Edge | [Card](cards/sentinel-edge.md), [public repo](https://github.com/SamandarMansurkhodjaev2713/sentinel-edge-smart-system) | "Это локальная smart-system: C++ firmware, serial protocol, Node bridge и realtime React dashboard." | Embedded + full-stack breadth, protocol design, realtime UI |
| Task Manage Bot | [Card](cards/task-manage-bot.md), [case study](case-studies/task-manage-bot.md) | "Проект превращает chat/voice messages в structured tasks с reminders и async processing." | Practical AI automation, queues, reminders, idempotency |
| med-exe | [Card](cards/med-exe.md), [case study](case-studies/med-exe.md) | "Это offline desktop app, где важны calculation logic и local privacy." | Rust/Tauri, typed IPC, deterministic domain logic |
| Marketbot | [Card](cards/marketbot.md), [case study](case-studies/marketbot.md) | "Это commerce automation с ingestion, subscriptions, affiliate links и notifications." | Event-driven backend, RabbitMQ/gRPC, service boundaries |
| CoupleOS / Softly | [Card](cards/coupleos.md), [live](https://softlylove.uz), [case study](case-studies/coupleos.md) | "Это мой founder-led mobile-first consumer product для пар с emotional UX, privacy и retention mechanics." | Founder ownership, consumer product thinking, mobile UX, privacy-aware data boundaries |
| 3d-landing | [Card](cards/3d-landing.md), [public repo](https://github.com/SamandarMansurkhodjaev2713/3d-landing) | "Это visual frontend: Three.js/WebGL, motion и polished product presentation." | Creative frontend, visual polish, performance-aware rendering |

## Deep Dive Prompts

Use these when a technical person asks for more depth.

### Forge / Learning OS

- Architecture: Next.js App Router, React, TypeScript, Prisma, Auth.js, Zod, services, Server Actions, evidence engine and portfolio/client-offer flows.
- Why it is designed this way: learning, evidence, portfolio and sales workflow are different domains, so they should not live as one UI blob.
- What to emphasize: product thinking, validation, domain modeling, tests, growth path from MVP to product.
- Safe demo assets: product flow, sanitized screens, README, case study, database model overview.

### TTYL Platform

- Architecture: identity, workspace/projects, messaging, files, search, notifications, audit, realtime gateway, workers and storage.
- Why it is designed this way: collaboration products fail in different places, so permissions, realtime, files, audit and storage need clear boundaries.
- What to emphasize: enterprise/on-prem thinking, data control, typed contracts, realtime and operational concerns.
- Safe demo assets: architecture map, anonymized screens, deployment story, case study.

### Klawis

- Live product: [klawis.uz](https://klawis.uz).
- Status: deployed and in active development.
- Architecture: deterministic legal routing, retrieval/citations, AI explanation layer, validation/evaluation mindset.
- Why it is designed this way: legal-tech cannot rely on a plain chatbot because source traceability and jurisdiction matter.
- What to emphasize: applied AI, RAG, citation discipline, live deployment, roadmap and safe UX for sensitive domains.
- Safe demo assets: anonymized sample questions, architecture diagram, citation behavior.

### BelfProctor

- Architecture: Windows service/client-agent, telemetry/upload pipeline, backend ingestion API, PostgreSQL/Prisma, React admin panel and deployment scripts.
- Why it is designed this way: client-agent, backend, admin panel and deployment fail for different reasons and must be observable separately.
- What to emphasize: beyond-web engineering, secure telemetry, operational UX, Windows deployment.
- Safe demo assets: agent/admin flow, anonymized architecture, deployment model. Do not show monitoring data or customer infrastructure.

### VFS Killer Main

- Architecture: Python workflow engine, Playwright/Camoufox browser layer, Telegram bot interface, Docker runtime, diagnostics and local state boundaries.
- Why it is designed this way: real browser automation fails because of sessions, timing, network/proxy issues and external state.
- What to emphasize: automation under real constraints, diagnostics-first mindset, retries and operator control.
- Safe demo assets: sanitized workflow diagram, Telegram control flow, logs without secrets.

### Sentinel Edge

- Architecture: Arduino-style C++ firmware, compact serial protocol, Node WebSocket bridge and React/Vite dashboard.
- Why it is designed this way: firmware must stay deterministic, the bridge owns hardware access, and dashboard handles visualization.
- What to emphasize: embedded + full-stack breadth, protocol design, realtime UI and documentation quality.
- Safe demo assets: public repo, docs, architecture, dashboard screenshot/video.

### Task Manage Bot

- Architecture: bot interface, transcription, structured parsing, domain logic, persistence, reminders, outbox/retry patterns.
- Why it is designed this way: bots are easy to prototype but hard to make reliable for real operations.
- What to emphasize: practical AI automation, structured workflow from messy input, reminders, queues and idempotency.
- Safe demo assets: anonymized chat flow, task lifecycle, architecture card.

### med-exe

- Architecture: Tauri desktop shell, React/TypeScript UI, Rust calculation/domain engine, typed IPC and SQLite persistence.
- Why it is designed this way: medical-style calculation logic must be deterministic, testable and separated from UI changes.
- What to emphasize: desktop architecture, local-first privacy, Rust domain modeling.
- Safe demo assets: anonymized screens and calculation workflow without patient data.

### Marketbot

- Architecture: ingestion, subscriptions, notifications, affiliate service, Telegram bot, admin BFF, gRPC and RabbitMQ.
- Why it is designed this way: ingestion, subscription logic and notification delivery change independently and fail differently.
- What to emphasize: event-driven backend, service contracts, reliability around notification workflows.
- Safe demo assets: service map, anonymized notifications, admin flow.

### CoupleOS / Softly

- Architecture: Next.js/React mobile-first app, Supabase auth/database/storage, feature modules, PWA direction and notification flow.
- Why it is designed this way: consumer products need fast iteration, but relationship data needs clear privacy boundaries.
- What to emphasize: founder ownership, emotional UX, product taste, mobile-first execution, retention mechanics and live product positioning.
- Safe demo assets: sanitized screens, UX flow, case study. Avoid private personal data.

### 3d-landing

- Architecture: Vite frontend, Three.js scene, animation loop, responsive layout and performance-aware rendering.
- Why it is designed this way: separating scene logic from UI/page composition makes a visual landing easier to tune across devices.
- What to emphasize: visual frontend, motion, presentation polish and performance awareness.
- Safe demo assets: public repo, live demo/video if available, screenshots.

## Private Code Explanation

### English

Some of my strongest work is private because it belongs to commercial, client or unreleased product contexts. I do not publish source code, secrets, datasets or internal workflows from those projects. Instead, I provide code-safe case studies: what the project does, the stack, my role, architecture, key decisions, quality signals and safe demo notes. For technical interviews, I can discuss design tradeoffs, module boundaries, data flow and testing strategy without exposing private implementation.

### Русский

Часть моих самых сильных работ приватная, потому что это коммерческие, клиентские или ещё не выпущенные продукты. Я не публикую source code, secrets, datasets и internal workflows таких проектов. Вместо этого я показываю code-safe case studies: что делает проект, стек, мою роль, архитектуру, ключевые решения, quality signals и safe demo notes. На техническом интервью я могу обсудить tradeoffs, module boundaries, data flow и testing strategy без раскрытия приватной реализации.

## Screenshot And Video Checklist

Before adding any screenshot or video:

1. Remove customer names, emails, phone numbers, IDs, tokens, URLs and internal company names.
2. Replace real data with demo data.
3. Hide private dashboards, logs, databases, `.env`, CI secrets and admin credentials.
4. Prefer cropped UI states that show product quality without exposing data.
5. Add a short caption: what the screen proves technically.

Перед добавлением скриншота или видео:

1. Убрать имена клиентов, emails, телефоны, IDs, tokens, URLs и внутренние названия компаний.
2. Заменить реальные данные на demo data.
3. Скрыть private dashboards, logs, databases, `.env`, CI secrets и admin credentials.
4. Лучше показывать обрезанные UI states, которые доказывают качество продукта без раскрытия данных.
5. Добавлять короткую подпись: что именно этот экран доказывает технически.

## Best Next Demo Assets To Prepare

| Project | Best asset | Why |
|---|---|---|
| Forge / Learning OS | 60-90 sec product walkthrough | Strongest product/founder proof |
| Sentinel Edge | Short dashboard + hardware/protocol demo | Shows breadth beyond normal web apps |
| TTYL Platform | Architecture diagram + anonymized UI flow | Strong for tech leads and enterprise roles |
| Klawis | Live product link + sample question -> cited answer video | Best deployed AI proof |
| CoupleOS / Softly | Mobile UI flow video + live product link | Shows founder ownership, product taste and design |
| VFS Killer Main | Sanitized workflow diagram | Shows automation complexity safely |
| BelfProctor | Agent/backend/admin architecture diagram | Shows system design without exposing telemetry |

## Final Interview Close

### English

The main thing I want this portfolio to show is that I can build across layers and still think like a product person. I can write code, but I also care about architecture, UX, business value, privacy and whether the project is actually understandable and usable.

### Русский

Главное, что я хочу показать этим портфолио: я могу строить продукт на разных уровнях и при этом думать как product-minded engineer. Я умею писать код, но также думаю об архитектуре, UX, бизнес-ценности, приватности и о том, чтобы проект был понятным и реально usable.
