# BelfProctor

## Русский

**Кратко:** приватная proctoring/monitoring система с Windows agent, backend ingestion API и admin panel для проверки событий и статусов.

**Проблема:** мониторинг рабочих станций требует не только UI, но и установленного агента, heartbeat, защищенной передачи данных, retry behavior, admin visibility и deployment packaging.

**Стек:** C# Windows agent, Node.js/Express, Prisma, PostgreSQL, React/Vite admin panel, deployment scripts, protected telemetry/uploads.

**Архитектура:** агент собирает события и отправляет telemetry/uploads; backend валидирует и сохраняет данные; admin panel показывает статусы, события и материалы проверки; deployment layer помогает устанавливать и обновлять клиентскую часть.

**Почему так:** proctoring находится между desktop, backend и операционным контролем. Разделение agent, ingestion API и admin panel делает систему устойчивее и безопаснее.

**Что доказывает:** умение работать за пределами обычного web: Windows client-agent, sensitive telemetry, deployment, admin workflows и privacy/security thinking.

## English

**Summary:** a private proctoring/monitoring system with a Windows agent, backend ingestion API and admin panel for reviewing events and statuses.

**Problem:** workstation monitoring requires more than UI: installed agent, heartbeat, protected data transfer, retry behavior, admin visibility and deployment packaging.

**Stack:** C# Windows agent, Node.js/Express, Prisma, PostgreSQL, React/Vite admin panel, deployment scripts and protected telemetry/uploads.

**Architecture:** the agent collects events and sends telemetry/uploads; the backend validates and stores data; the admin panel shows statuses, events and review material; the deployment layer supports installation and updates.

**Why this architecture:** proctoring sits between desktop, backend and operational control. Separating agent, ingestion API and admin panel makes the system more reliable and safer.

**What it proves:** ability to work beyond typical web apps: Windows client-agent, sensitive telemetry, deployment, admin workflows and privacy/security thinking.

---

[Карточка проекта](../cards/belfproctor.md) | [Назад к case studies](README.md)
