# TTYL Platform

## Русский

**Кратко:** приватная on-prem collaboration платформа для проектов, задач, чатов, файлов, поиска, уведомлений, ролей и audit logs.

**Проблема:** командам часто нужны современные collaboration tools, но с контролем над данными и инфраструктурой. Внешний SaaS не всегда подходит из-за приватности, регуляторики или внутренней политики.

**Стек:** NestJS, Next.js, PostgreSQL, Redis, MinIO/object storage, WebSocket/realtime, RBAC, workers, Docker-style deployment.

**Архитектура:** identity, workspaces, projects, tasks, messaging, files, search, notifications, audit и realtime gateway разделены как домены. Файлы вынесены в object storage, background jobs обрабатывают тяжелые операции, RBAC управляет доступом.

**Почему так:** enterprise collaboration быстро растет в сложность. Доменное разделение помогает удерживать безопасность, масштабируемость, тестируемость и возможность on-prem deployment.

**Что доказывает:** enterprise system design, backend depth, permissions, realtime, storage, audit, deployment и понимание внутренних платформ.

## English

**Summary:** a private on-prem collaboration platform for projects, tasks, chat, files, search, notifications, roles and audit logs.

**Problem:** teams often need modern collaboration tools while keeping control over data and infrastructure. External SaaS is not always acceptable because of privacy, regulation or internal policy.

**Stack:** NestJS, Next.js, PostgreSQL, Redis, MinIO/object storage, WebSocket/realtime, RBAC, workers and Docker-style deployment.

**Architecture:** identity, workspaces, projects, tasks, messaging, files, search, notifications, audit and realtime gateway are separated as domains. Files are stored in object storage, background jobs handle heavy operations and RBAC controls access.

**Why this architecture:** enterprise collaboration grows complex quickly. Domain separation helps maintain security, scalability, testability and on-prem deployment readiness.

**What it proves:** enterprise system design, backend depth, permissions, realtime, storage, audit, deployment and internal-platform thinking.

---

[Карточка проекта](../cards/ttyl-platform.md) | [Назад к case studies](README.md)
