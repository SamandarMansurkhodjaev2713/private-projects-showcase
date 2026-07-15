# AI Classroom Intelligence Platform

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-FastAPI-3776ab?style=flat-square">
  <img alt="AI" src="https://img.shields.io/badge/AI-Evidence%20first-7c3aed?style=flat-square">
  <img alt="Privacy" src="https://img.shields.io/badge/Privacy-Local%20first-0f766e?style=flat-square">
  <img alt="Tests" src="https://img.shields.io/badge/Quality-Golden%20reports-d97706?style=flat-square">
</p>

## Русский

> **Главный сигнал:** AI-аналитика строится вокруг проверяемых evidence events и human review, а не вокруг одного непрозрачного model score.

| Быстрый взгляд | Деталь |
|---|---|
| Статус | Приватный продукт · production foundation |
| Моя роль | Архитектура, доменная модель, AI/backend foundation, dashboard и QA |
| Продукт | Privacy-first аналитика учебной аудитории |
| Доказательства | Unit/integration suite, API smoke, golden reports, deterministic demo pipeline |

**Проблема и ценность:** обычная AI-оценка занятия легко становится недоказуемой и опасной: непонятно, откуда взялся вывод, насколько качественны данные и кто проверил результат. Платформа хранит каждое заключение как событие с временным диапазоном, источником, confidence, состоянием качества данных и human-review статусом.

**Архитектура:** FastAPI boundary, React/TypeScript dashboard, Python AI workers, общие contracts, очереди, локальное object storage и SQLite/PostgreSQL-совместимый persistence слой. Domain/application не зависят от infrastructure; модели и внешние инструменты подключаются через порты и adapters.

**Почему именно так:** локальная обработка защищает чувствительное видео и аудио; evidence-first модель делает выводы трассируемыми; human review снижает риск автоматических high-impact решений; детерминированные seed и golden reports позволяют демонстрировать и регрессионно проверять систему до установки камер.

**Качество:** строгая Pydantic-валидация, unit/integration/API tests, проверка job lifecycle, storage, media catalog, model adapters, golden reports, smoke demo pipeline и production audit. Низкая уверенность и плохое качество данных не маскируются, а переводят событие в review flow.

## English

> **Main signal:** classroom AI is built around traceable evidence events and human review, not a single opaque model score.

| Quick view | Detail |
|---|---|
| Status | Private product · production foundation |
| My role | Architecture, domain model, AI/backend foundation, dashboard and QA |
| Product | Privacy-first classroom analytics |
| Evidence | Unit/integration suite, API smoke, golden reports and deterministic demo pipeline |

The platform records timestamped evidence with source model, confidence, data-quality state and review state. FastAPI, React/TypeScript, Python workers, shared contracts, queues and local storage are separated through layered architecture and ports. Local-first processing protects sensitive media; deterministic demo data and golden reports make the system reviewable and regression-testable before real-room hardware is connected.

---
[Назад к галерее](README.md) | [Case study](../case-studies/ai-classroom.md) | [Главная витрина](../README.md)