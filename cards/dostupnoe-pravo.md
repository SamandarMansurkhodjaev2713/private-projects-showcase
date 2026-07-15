# Доступное Право / Dostupnoe Pravo

<p>
  <img alt="Live" src="https://img.shields.io/badge/Live-Demo-15803d?style=flat-square">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-16-111111?style=flat-square">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-RLS-336791?style=flat-square">
  <img alt="Tests" src="https://img.shields.io/badge/Tests-192%20passing-c64b36?style=flat-square">
</p>

## Русский

> **Главный сигнал:** небольшая CRM реализована с инженерными гарантиями настоящего продукта: изоляцией данных, конкурентными обновлениями, устойчивыми интеграциями и 192 тестами.

| Быстрый взгляд | Деталь |
|---|---|
| Статус | Публичный репозиторий · live demo |
| Моя роль | Product architecture, UX, full-stack implementation, deployment и QA |
| Продукт | CRM для частной юридической практики |
| Доказательства | 192 Vitest tests, CI, architecture boundary test, live PostgreSQL invariant checks |

**Проблема и ценность:** юристу нужен не тяжёлый enterprise CRM, а быстрый рабочий экран для клиентов, хода дела и следующего действия. Продукт объединяет таблицу и kanban, карточку клиента, историю статусов, заметки, напоминания, поиск, фильтры, экспорт и Telegram/email-уведомления.

**Архитектура:** Next.js 16 / React 19 / strict TypeScript; Server Components и Server Actions; Supabase/PostgreSQL с RLS, triggers и RPC; Zod на границах; Telegram Bot API и Resend. Зависимости направлены внутрь: web → infrastructure → application → domain.

**Почему именно так:** domain слой защищает правила переходов статуса; compare-and-swap не позволяет тихо затереть изменение из другой вкладки; workspace RLS изолирует посетителей демо; circuit breaker и retries не дают сбою Telegram отменить сохранение клиента; CSV export защищён от formula injection.

**Качество:** 192 теста покрывают domain, use cases, устойчивость, i18n parity и архитектурные границы. Инварианты БД проверяются на живом PostgreSQL, CI запускает typecheck, lint, tests и build. Доступность, empty/loading/error states и mobile layout входят в критерии готовности.

**Ссылки:** [репозиторий](https://github.com/SamandarMansurkhodjaev2713/dostupnoe-pravo) · [живое демо](https://dostupnoe-pravo-alpha.vercel.app)

## English

> **Main signal:** a compact legal CRM with real product guarantees: data isolation, concurrency control, resilient integrations and 192 tests.

| Quick view | Detail |
|---|---|
| Status | Public repository and live demo |
| My role | Full-stack product architecture, domain logic, data isolation, integrations, testing and deployment |

Next.js 16, React 19, strict TypeScript and Supabase/PostgreSQL are organized as web → infrastructure → application → domain. RLS isolates workspaces, compare-and-swap protects status transitions, retries/circuit breaker isolate notification failures, and 192 tests cover domain rules, use cases, resilience, translations and architecture boundaries.

**Links:** [repository](https://github.com/SamandarMansurkhodjaev2713/dostupnoe-pravo) · [live demo](https://dostupnoe-pravo-alpha.vercel.app)

---
[Назад к галерее](README.md) | [Главная витрина](../README.md)