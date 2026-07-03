# TTYL Platform

<p>
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-Backend-e0234e?style=flat-square">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-Frontend-111111?style=flat-square">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-Data-336791?style=flat-square">
  <img alt="Enterprise" src="https://img.shields.io/badge/Signal-Enterprise%20System%20Design-1d4ed8?style=flat-square">
</p>

## Русский

**Что это:** TTYL Platform - приватная on-prem collaboration платформа для команд: проекты, задачи, чаты, файлы, поиск, уведомления, роли, audit logs и рабочее пространство без передачи данных во внешний SaaS.

**Какую проблему решает:** некоторым командам нужны современные collaboration tools, но они не могут или не хотят отдавать внутренние данные сторонним сервисам. Платформа дает контролируемую среду, где коммуникация, файлы и управление проектами находятся внутри инфраструктуры.

**Стек:** NestJS, Next.js, PostgreSQL, Redis, MinIO/object storage, WebSocket/realtime, auth/RBAC, workers, Docker-style deployment.

**Архитектура:** система разделена по доменам: identity, workspaces, projects, tasks, messaging, files, search, notifications, audit, realtime gateway и background workers. Хранилище файлов отделено от базы, а права доступа проходят через отдельную модель ролей и workspace boundaries.

**Почему именно так:** enterprise collaboration быстро становится хаотичным, если смешать все в один модуль. Разделение доменов упрощает развитие, безопасность, аудит, тестирование и on-prem deployment.

**Уникальность и сильные стороны:** не просто CRUD-приложение, а платформа с реальными enterprise concerns: permissions, realtime, файлы, audit, storage, уведомления, self-hosted deployment и операционная надежность.

**Что доказывает работодателю:** сильный system design, backend depth, понимание enterprise-ограничений и способность строить продукт уровня внутренней платформы.

**Что можно показать:** code-safe архитектуру, карточку, диаграмму модулей и приватный walkthrough без исходного кода.

## English

**What it is:** TTYL Platform is a private on-prem collaboration platform for teams: projects, tasks, chat, files, search, notifications, roles, audit logs and workspace management without moving internal data into an external SaaS.

**Problem it solves:** some teams need modern collaboration tools but cannot or do not want to send internal data to third-party services. The platform provides a controlled environment for communication, files and project management inside the organization’s infrastructure.

**Stack:** NestJS, Next.js, PostgreSQL, Redis, MinIO/object storage, WebSocket/realtime, auth/RBAC, workers and Docker-style deployment.

**Architecture:** the system is split by domains: identity, workspaces, projects, tasks, messaging, files, search, notifications, audit, realtime gateway and background workers. File storage is separated from the database, while access control is handled through roles and workspace boundaries.

**Why this architecture:** enterprise collaboration becomes chaotic if everything is placed into one module. Domain separation improves evolution, security, auditability, testing and on-prem deployment.

**Unique strengths:** not a simple CRUD app, but a platform with real enterprise concerns: permissions, realtime, files, audit, storage, notifications, self-hosted deployment and operational reliability.

**Employer signal:** strong system design, backend depth, enterprise constraints and the ability to build internal-platform-grade products.

**Safe proof:** code-safe architecture, project card, module diagram and private walkthrough without source code.

---

[Назад к галерее](README.md) | [Case study](../case-studies/ttyl-platform.md) | [Главная витрина](../README.md)
