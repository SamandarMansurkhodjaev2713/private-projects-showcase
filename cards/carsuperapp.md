# CarSuperApp

<p>
  <img alt="Status" src="https://img.shields.io/badge/Status-Active%20foundation-c64b36?style=flat-square">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-Strict-3178c6?style=flat-square">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-RLS-336791?style=flat-square">
  <img alt="CI" src="https://img.shields.io/badge/CI-Quality%20gates-15803d?style=flat-square">
</p>

## Русский

> **Главный сигнал:** продукт проектируется как реальная multi-tenant платформа для автосервисов Узбекистана, а не как быстрый CRUD без эксплуатационной модели.

| Быстрый взгляд | Деталь |
|---|---|
| Статус | Активная разработка: foundation, CI, локальная инфраструктура и RLS data layer реализованы |
| Моя роль | Product/system architecture, engineering governance, backend foundation и quality engineering |
| Продукт | PWA для независимых, сетевых и дилерских автосервисов |
| Доказательства | Green CI, PWA и PostgreSQL RLS spikes, 199/199 тестов Phase 1C, Testcontainers integration |

**Проблема и ценность:** автосервису нужен единый рабочий контур для клиентов, автомобилей, заказ-нарядов, расписания, медиа, платежей, документов и филиалов. Главный риск такого продукта — не нехватка экранов, а потеря данных между арендаторами, гонки статусов, ненадёжные внешние интеграции и невозможность безопасно масштабировать процессы.

**Архитектура:** modular monolith с Next.js/React PWA, NestJS/Fastify API, PostgreSQL/Prisma, Redis/BullMQ и object storage. Домен разделён на IAM, организации и филиалы, расписание, медиа, платежи, аудит, idempotency и outbox. Tenant/branch isolation обеспечивается PostgreSQL RLS и проверяется на реальной БД.

**Почему именно так:** модульный монолит сохраняет скорость разработки и единые транзакции на ранней стадии, но задаёт границы для будущего выделения сервисов. RLS, append-only audit, idempotency и durable recovery закрывают риски, которые невозможно надёжно решить только проверками в UI.

**Качество:** CI запускает lint, typecheck, coverage, build, PWA behavior/offline checks и dependency audit. RLS проверяется через Testcontainers/PostgreSQL 18. В Phase 1C зафиксированы тест-планы, тест-кейсы и bug reports; найденные P1-дефекты в recovery и authorization были исправлены и повторно проверены. Открытые provider/device/compliance риски не скрываются и вынесены в release gates.

**Уникальность:** сочетает product discovery, UX/system design, security architecture, QA и исполнимую foundation-реализацию в одном проекте.

## English

> **Main signal:** a real multi-tenant platform for Uzbekistan auto-service workshops, designed around operational and data-isolation risks rather than a quick CRUD demo.

| Quick view | Detail |
|---|---|
| Status | Active foundation: monorepo, CI, local infrastructure and RLS data layer implemented |
| My role | Product/system architecture, engineering governance, backend foundation and quality engineering |
| Product | PWA for independent, network and dealer workshops |
| Evidence | Green CI, PWA/RLS spikes, 199/199 Phase 1C tests and Testcontainers integration |

The architecture uses a modular monolith with Next.js/React, NestJS/Fastify, PostgreSQL/Prisma, Redis/BullMQ and object storage. Tenant and branch isolation are enforced by PostgreSQL RLS; audit, idempotency, outbox and recovery are explicit product concerns. Quality gates cover type safety, tests, coverage, builds, offline PWA behavior and dependency risk. Unverified providers, devices and compliance claims remain explicit release gates rather than hidden assumptions.

---
[Назад к галерее](README.md) | [Главная витрина](../README.md)