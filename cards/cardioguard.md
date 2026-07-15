# CardioGuard

<p>
  <img alt="React Native" src="https://img.shields.io/badge/React%20Native-Expo-149eca?style=flat-square">
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-Compose-7f52ff?style=flat-square">
  <img alt="Tests" src="https://img.shields.io/badge/Tests-206%20passing-15803d?style=flat-square">
  <img alt="Status" src="https://img.shields.io/badge/Status-Academic%20prototype-d97706?style=flat-square">
</p>

## Русский

> **Главный сигнал:** кросс-платформенный health-tech прототип с изолированной доменной логикой, локальной аналитикой и 206 тестами, при этом клинические ограничения заявлены честно.

| Быстрый взгляд | Деталь |
|---|---|
| Статус | Публичный академический прототип · web demo |
| Моя роль | Cross-platform architecture, domain implementation, mobile UX и QA |
| Продукт | Кардиометаболический мониторинг для пациента и врача/исследователя |
| Доказательства | 206 Jest tests, strict TypeScript, CI, React Native + Kotlin implementations |

**Что создано:** профили и медкарта, мониторинг показателей, SCORE2/Framingham demo-calculators, напоминания и приверженность, психоэмоциональный мониторинг, локальные тренды, ранние предупреждения, рекомендации, cohort analytics и PDF-отчёт.

**Архитектура:** активная версия построена на React Native/Expo, Zustand, AsyncStorage, Zod и Expo services; исходная Android-версия — Kotlin/Compose/MVVM. Чистые domain engines отделены от UI и I/O, поэтому расчёты детерминированы и тестируются без устройства.

**Качество и ответственность:** 206 тестов покрывают калькуляторы, risk/alert engines, данные, store, UI primitives и screens. Повреждённый persistence безопасно деградирует, Error Boundary защищает UI, a11y и ru/uz i18n проверяются отдельно. Проект прямо сообщает, что клинические алгоритмы демонстрационные и требуют экспертной валидации.

**Ссылки:** [репозиторий](https://github.com/SamandarMansurkhodjaev2713/cardioguard) · [web demo](https://samandarmansurkhodjaev2713.github.io/cardioguard/)

## English

> **Main signal:** a cross-platform health-tech prototype with isolated domain logic, on-device analytics and 206 tests, while clinical limitations remain explicit.

| Quick view | Detail |
|---|---|
| Status | Public academic prototype with live demo |
| My role | Cross-platform architecture, domain logic, UI, automated tests and technical documentation |

React Native/Expo and the original Kotlin/Compose implementation share a domain-first approach. Deterministic calculators and engines are separated from UI/I/O; Jest, strict TypeScript and CI cover calculations, persistence, store and screens. The project is presented as an academic prototype, not a clinically validated medical device.

---
[Назад к галерее](README.md) | [Главная витрина](../README.md)