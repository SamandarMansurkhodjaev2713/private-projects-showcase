# Marketbot

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-Services-3776ab?style=flat-square">
  <img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-Events-ff6600?style=flat-square">
  <img alt="gRPC" src="https://img.shields.io/badge/gRPC-Contracts-244c5a?style=flat-square">
  <img alt="Commerce" src="https://img.shields.io/badge/Signal-Commerce%20Automation-7c2d12?style=flat-square">
</p>

## Русский

> **Главный сигнал:** commerce automation с event-driven backend, а не просто бот для уведомлений.

| Быстрый взгляд | Деталь |
|---|---|
| Продукт | Offers, subscriptions, affiliate links, Telegram delivery |
| Сложность | RabbitMQ, gRPC, service boundaries, admin visibility |
| Эффект | Показывает backend для бизнес-процессов и монетизации |

**Что это:** Marketbot - приватная e-commerce automation платформа для сбора офферов, подписок, affiliate links, Telegram notifications и операционной панели.

**Какую проблему решает:** commerce/offers продукту нужны ingestion, фильтрация, подписки, уведомления, генерация ссылок, админский контроль, обработка ошибок и доставка событий пользователю без ручной рутины.

**Стек:** Python services, gRPC, RabbitMQ, PostgreSQL, Telegram bot, React admin, service boundaries, event-driven workflows.

**Архитектура:** ingestion service собирает и нормализует офферы, subscription service хранит интересы пользователей, notification service доставляет события, affiliate/link service генерирует ссылки, Telegram bot выводит value пользователю, admin panel дает контроль и диагностику.

**Почему именно так:** commerce automation сильно зависит от событий и внешних источников. Event-driven подход через очереди делает систему устойчивее к задержкам, сбоям и росту количества сценариев.

**Уникальность и сильные стороны:** microservice-style thinking, event-driven backend, Telegram delivery, affiliate workflow, admin visibility и продуктовая логика вокруг коммерческого результата.

**Что доказывает работодателю:** умение строить backend automation для бизнеса: события, очереди, сервисные контракты, delivery, retries, админка и монетизационная логика.

**Что можно показать:** case study, архитектуру сервисов, безопасные screenshots и demo flow без коммерческих данных.

## English

> **Main signal:** commerce automation with an event-driven backend, not just a notification bot.

| Quick view | Detail |
|---|---|
| Product | Offers, subscriptions, affiliate links and Telegram delivery |
| Complexity | RabbitMQ, gRPC, service boundaries and admin visibility |
| Impact | Shows backend work for business workflows and monetization |

**What it is:** Marketbot is a private e-commerce automation platform for offer collection, subscriptions, affiliate links, Telegram notifications and an operational admin panel.

**Problem it solves:** a commerce/offers product needs ingestion, filtering, subscriptions, notifications, link generation, admin control, error handling and event delivery to users without manual routine.

**Stack:** Python services, gRPC, RabbitMQ, PostgreSQL, Telegram bot, React admin, service boundaries and event-driven workflows.

**Architecture:** the ingestion service collects and normalizes offers, the subscription service stores user interests, the notification service delivers events, the affiliate/link service generates links, the Telegram bot brings value to users, and the admin panel provides control and diagnostics.

**Why this architecture:** commerce automation depends heavily on events and external sources. An event-driven approach with queues makes the system more resilient to delays, failures and growth in scenario complexity.

**Unique strengths:** microservice-style thinking, event-driven backend, Telegram delivery, affiliate workflow, admin visibility and product logic around commercial outcomes.

**Employer signal:** ability to build business backend automation: events, queues, service contracts, delivery, retries, admin tooling and monetization logic.

**Safe proof:** case study, service architecture, safe screenshots and demo flow without commercial data.

---

[Назад к галерее](README.md) | [Case study](../case-studies/marketbot.md) | [Главная витрина](../README.md)
