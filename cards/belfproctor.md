# BelfProctor

<p>
  <img alt="CSharp" src="https://img.shields.io/badge/C%23-Windows%20Agent-512bd4?style=flat-square">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-API-339933?style=flat-square">
  <img alt="React" src="https://img.shields.io/badge/React-Admin-149eca?style=flat-square">
  <img alt="Monitoring" src="https://img.shields.io/badge/Signal-Proctoring%20System-991b1b?style=flat-square">
</p>

## Русский

> **Главный сигнал:** системный проект за пределами web: Windows agent, protected telemetry и admin review workflow.

| Быстрый взгляд | Деталь |
|---|---|
| Продукт | Proctoring/monitoring система с desktop-agent |
| Сложность | Heartbeat, uploads, retries, policy, admin visibility |
| Эффект | Показывает работу с чувствительными данными, deployment и operational UX |

**Что это:** BelfProctor - приватная proctoring/monitoring система с Windows client-agent, backend ingestion API и admin panel для просмотра событий, статусов и материалов проверки.

**Какую проблему решает:** proctoring система не может быть просто веб-формой. Нужно устанавливаемое клиентское приложение, heartbeat, сбор событий, защищенная передача данных, retry logic, политика мониторинга, admin visibility и понятный workflow проверки.

**Стек:** C# Windows client/agent, Node.js/Express backend, Prisma, PostgreSQL, React/Vite admin panel, deployment scripts, protected uploads/telemetry.

**Архитектура:** Windows agent собирает события и отправляет telemetry/uploads в backend; API валидирует и сохраняет данные; admin panel дает операторам обзор статусов, нарушений и истории; deployment слой упрощает установку и обновление.

**Почему именно так:** proctoring живет на границе desktop, backend и операционного контроля. Разделение agent, ingestion API и admin panel делает систему устойчивее, наблюдаемее и безопаснее.

**Уникальность и сильные стороны:** проект показывает работу за пределами обычного web: client-agent behavior, Windows deployment, sensitive telemetry, retries, admin workflow и private/security-first мышление.

**Что доказывает работодателю:** умение строить системные продукты с desktop-частью, backend-пайплайном, безопасной передачей данных и административным интерфейсом.

**Что можно показать:** архитектуру, карточку, safe demo сценарий, обезличенные screenshots и описание без клиентских данных.

## Как обеспечивалось качество

**Code-safe QA-кейс:** xUnit/Moq integration checks проверяли сохранение и загрузку политик, генерацию отчета, изолированную работу с файлами и передачу результата в transmission service. Изоляция файловой системы и mocked transport выбраны, чтобы надежно тестировать observable behavior без реального сервера и пользовательских данных.

[Полная матрица QA-доказательств](https://github.com/SamandarMansurkhodjaev2713/qa-engineering-portfolio/blob/main/docs/project-quality-matrix.md)

## English

> **Main signal:** a system project beyond web: Windows agent, protected telemetry and admin review workflow.

| Quick view | Detail |
|---|---|
| Product | Proctoring/monitoring system with a desktop agent |
| Complexity | Heartbeat, uploads, retries, policy and admin visibility |
| Impact | Shows sensitive data handling, deployment and operational UX |

**What it is:** BelfProctor is a private proctoring/monitoring system with a Windows client-agent, backend ingestion API and admin panel for reviewing events, statuses and verification material.

**Problem it solves:** a proctoring system cannot be just a web form. It needs an installed client, heartbeat, event collection, protected data transfer, retry logic, monitoring policy, admin visibility and a clear review workflow.

**Stack:** C# Windows client/agent, Node.js/Express backend, Prisma, PostgreSQL, React/Vite admin panel, deployment scripts and protected uploads/telemetry.

**Architecture:** the Windows agent collects events and sends telemetry/uploads to the backend; the API validates and stores data; the admin panel gives operators visibility into statuses, violations and history; the deployment layer supports installation and updates.

**Why this architecture:** proctoring sits between desktop, backend and operational control. Separating agent, ingestion API and admin panel makes the system more reliable, observable and secure.

**Unique strengths:** the project shows work beyond typical web apps: client-agent behavior, Windows deployment, sensitive telemetry, retries, admin workflow and privacy/security-first thinking.

**Employer signal:** ability to build system products with a desktop component, backend pipeline, protected data flow and administrative UI.

**Safe proof:** architecture, project card, safe demo scenario, anonymized screenshots and description without customer data.

## Quality engineering

**Code-safe QA case:** xUnit/Moq integration checks covered policy persistence/loading, report generation, isolated filesystem behavior and handoff to the transmission service. Filesystem isolation and mocked transport validate observable behavior without a live server or user data.

[Full QA evidence matrix](https://github.com/SamandarMansurkhodjaev2713/qa-engineering-portfolio/blob/main/docs/project-quality-matrix.md)

---

[Назад к галерее](README.md) | [Case study](../case-studies/belfproctor.md) | [Главная витрина](../README.md)
