# Marketbot

## Русский

**Кратко:** приватная commerce automation платформа для офферов, подписок, affiliate links, Telegram notifications и операционной админки.

**Проблема:** offer-based продукты требуют ingestion, нормализации, фильтров, подписок, delivery, retries, админского контроля и обработки ошибок.

**Стек:** Python services, RabbitMQ, gRPC, PostgreSQL, Telegram bot, React admin, event-driven workflows.

**Архитектура:** ingestion service собирает офферы; subscription service хранит интересы; affiliate/link service генерирует ссылки; notification service доставляет события; Telegram bot выводит value пользователю; admin panel дает контроль.

**Почему так:** commerce automation зависит от событий и внешних источников. Очереди и сервисные границы позволяют переживать задержки, сбои и рост сценариев.

**Что доказывает:** event-driven backend, service contracts, commerce thinking, Telegram delivery, admin visibility и automation для бизнес-результата.

## English

**Summary:** a private commerce automation platform for offers, subscriptions, affiliate links, Telegram notifications and an operational admin panel.

**Problem:** offer-based products require ingestion, normalization, filtering, subscriptions, delivery, retries, admin control and error handling.

**Stack:** Python services, RabbitMQ, gRPC, PostgreSQL, Telegram bot, React admin and event-driven workflows.

**Architecture:** the ingestion service collects offers; the subscription service stores interests; the affiliate/link service generates links; the notification service delivers events; the Telegram bot brings value to users; the admin panel provides control.

**Why this architecture:** commerce automation depends on events and external sources. Queues and service boundaries help handle delays, failures and growth in scenarios.

**What it proves:** event-driven backend, service contracts, commerce thinking, Telegram delivery, admin visibility and automation for business outcomes.

---

[Карточка проекта](../cards/marketbot.md) | [Назад к case studies](README.md)
