# Platform Core

<p>
  <img alt="Go" src="https://img.shields.io/badge/Go-AI%20Gateway-00add8?style=flat-square">
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-Omnichannel%20Hub-e0234e?style=flat-square">
  <img alt="Python" src="https://img.shields.io/badge/Python-Eval%20Harness-3776ab?style=flat-square">
  <img alt="Status" src="https://img.shields.io/badge/Status-Active%20scaffolding-d97706?style=flat-square">
</p>

## Русский

> **Главный сигнал:** AI-проекты получают общий эксплуатационный контур вместо копирования provider logic, каналов и eval-кода в каждый продукт.

| Быстрый взгляд | Деталь |
|---|---|
| Статус | Приватный проект · активный scaffolding |
| Моя роль | System architecture, service boundaries, contracts и foundation implementation |
| Продукт | Shared core для портфеля AI-решений |
| Компоненты | AI Gateway, Omnichannel Hub, Eval Harness |

**Проблема и ценность:** когда каждый AI-продукт напрямую интегрируется с провайдерами и каналами, быстро появляются разные форматы, непредсказуемые расходы, слабый fallback, дублирование и невозможность централизованно тестировать поведение моделей.

**Архитектура:** Go gateway маршрутизирует запросы между LLM-провайдерами, применяет fallback, cache, rate limits и cost accounting. NestJS hub нормализует Telegram, WhatsApp, Instagram и web-события и поддерживает human takeover через Chatwoot. Python eval harness хранит наборы диалогов и превращает регрессию AI-поведения в CI gate. Общие contracts/adapters/presets уменьшают расхождения между продуктами.

**Почему именно так:** Go подходит для компактного конкурентного gateway, NestJS — для событийного омниканального orchestration, Python — для evaluation и работы с AI tooling. Разделение не ради микросервисов, а по разным эксплуатационным профилям и ответственности.

**Качество:** ключевая проверка — не только HTTP 200, а routing/fallback, ограничения стоимости, schema contracts, идемпотентность каналов, takeover flow и регрессия качества ответов. Проект честно отмечен как scaffolding: архитектура и границы готовы, production-нагрузка не заявляется.

## English

> **Main signal:** AI products share one operational core instead of duplicating provider, channel and evaluation logic.

| Quick view | Detail |
|---|---|
| Status | Private active scaffolding |
| My role | Platform architecture, service boundaries, AI routing design and evaluation strategy |

Go powers provider routing, fallback, cache, rate limits and cost accounting. NestJS normalizes omnichannel events and human takeover. Python owns dialogue datasets and AI regression gates. Shared contracts reduce drift between products. The project is explicitly presented as active scaffolding, not as production-proven infrastructure.

---
[Назад к галерее](README.md) | [Главная витрина](../README.md)