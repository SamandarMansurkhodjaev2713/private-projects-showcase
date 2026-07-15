# BioFlux Observer

<p>
  <img alt="React" src="https://img.shields.io/badge/React-TypeScript-149eca?style=flat-square">
  <img alt="Telemetry" src="https://img.shields.io/badge/Domain-Industrial%20telemetry-0f766e?style=flat-square">
  <img alt="Safety" src="https://img.shields.io/badge/Boundary-Read%20only-c64b36?style=flat-square">
  <img alt="Public" src="https://img.shields.io/badge/Repo-Public-15803d?style=flat-square">
</p>

## Русский

> **Главный сигнал:** промышленный dashboard проектируется вокруг решений оператора, качества данных и safety boundaries, а не вокруг декоративных графиков.

| Быстрый взгляд | Деталь |
|---|---|
| Статус | Публичный frontend/product prototype |
| Моя роль | Domain modeling, dashboard UX, frontend architecture и testing |
| Продукт | Read-only observer для биогазовой станции |
| Доказательства | Public React/TypeScript repo, simulated scenarios, passing build, базовый Vitest smoke |

**Проблема и ценность:** оператору нужно за секунды понять стабильность процесса, дрейф сигналов, приоритет аварий, доверие к данным и экономическое состояние станции. Dashboard объединяет telemetry, process map, alarms, data quality, reports и investor economics.

**Архитектура:** React/TypeScript, Vite, TanStack Query, Recharts и domain-specific components. Типы описывают stations, signals, severity, process areas, roles и capabilities; mock API повторяет будущий backend contract, позволяя проверить продуктовый сценарий до подключения PLC и реальной телеметрии.

**Почему именно так:** прототип сознательно read-only — он не отправляет управляющие команды оборудованию. Это уменьшает риск и отделяет наблюдаемость от control plane. Сценарии симуляции позволяют тестировать normal, drift, alarm и poor-data состояния без физической станции.

**Качество:** production build проходит; публичный Vitest-набор пока содержит один smoke-тест. Следующий обоснованный слой — тесты alarm/data-quality правил, contract tests с telemetry gateway и visual regression для плотных экранов.

## English

> **Main signal:** an industrial dashboard designed around operator decisions, data quality and safety boundaries rather than decorative charts.

| Quick view | Detail |
|---|---|
| Status | Public industrial telemetry prototype |
| My role | Product architecture, React/TypeScript implementation, data-quality scenarios and safety boundaries |

The React/TypeScript architecture separates domain models, mock API contracts and UI panels. A deliberate read-only boundary keeps the prototype away from equipment control, while simulated operational scenarios validate alarms, drift, poor-data and investor reporting flows before real telemetry integration.

---
[Назад к галерее](README.md) | [Главная витрина](../README.md)