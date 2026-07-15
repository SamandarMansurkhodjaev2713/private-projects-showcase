# Task-manager / Task Manage Bot

<p>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-Public%20Bot-000000?style=flat-square">
  <img alt="Python" src="https://img.shields.io/badge/Python-AI%20Workflow-3776ab?style=flat-square">
  <img alt="Telegram" src="https://img.shields.io/badge/Telegram-Automation-229ed9?style=flat-square">
  <img alt="CI" src="https://img.shields.io/badge/GitHub%20Actions-CI-2088ff?style=flat-square">
</p>

## Русский

> **Главный сигнал:** Telegram automation, где есть не только бот, но и workflow, reminders, async jobs, CI и reliability patterns.

| Быстрый взгляд | Деталь |
|---|---|
| Продукт | Public Rust bot + private AI task workflow |
| Статус | Публичный репозиторий + приватный production-вариант |
| Моя роль | Solo architecture, bot/backend implementation, deployment и QA |
| Сложность | State, reminders, outbox, retries, SQLx, Telegram UX |
| Эффект | Показывает backend discipline в практической автоматизации |

**Что это:** направление Telegram task automation: публичный Rust `Task-manager` и приватный `Task Manage Bot` case study с AI/voice-to-task логикой, напоминаниями, назначениями и операционными workflow.

**Какую проблему решает:** задачи в чатах, голосовых сообщениях и быстрых переписках легко теряются. Нужна система, которая превращает неструктурированную коммуникацию в задачи, сроки, напоминания, статусы и контроль выполнения.

**Стек:** Rust, Teloxide, SQLx, Docker, GitHub Actions, Python/aiogram для приватного AI workflow, PostgreSQL/SQLite, reminders, async jobs, structured logging.

**Архитектура:** bot layer принимает команды/сообщения, domain layer отвечает за задачи и статусы, storage layer держит данные, scheduler/outbox обрабатывает напоминания, а retry/idempotency patterns защищают workflow от сбоев.

**Почему именно так:** Telegram bot быстро превращается в хаос, если смешать команды, бизнес-логику и базу. Разделение слоев делает код понятнее, тестируемее и готовым к развитию.

**Уникальность и сильные стороны:** сочетание public Rust proof, CI, clean bot architecture и private AI automation показывает как reliability, так и способность делать реальные workflow-инструменты.

**Что доказывает работодателю:** умение строить операционную автоматизацию: async jobs, reminders, state, retries, Telegram UX и backend discipline.

**Что можно показать:** [публичный репозиторий](https://github.com/SamandarMansurkhodjaev2713/Task-manager), GitHub Actions CI, карточку и private case study.

## Как обеспечивалось качество

**Реализованное QA-покрытие:** Rust unit, regression и repository-integration тесты для RBAC, onboarding, deadlines, notifications, voice processing, prompt schemas и persistence. Автоматизированы именно повторяемые критичные правила, где дефект приводит к неверному назначению, статусу или уведомлению.

[Полная матрица QA-доказательств](https://github.com/SamandarMansurkhodjaev2713/qa-engineering-portfolio/blob/main/docs/project-quality-matrix.md)

## English

> **Main signal:** Telegram automation with workflow, reminders, async jobs, CI and reliability patterns.

| Quick view | Detail |
|---|---|
| Product | Public Rust bot + private AI task workflow |
| Status | Public repository + private production variant |
| My role | Solo architecture, bot/backend implementation, deployment and QA |
| Complexity | State, reminders, outbox, retries, SQLx and Telegram UX |
| Impact | Shows backend discipline in practical automation |

**What it is:** a Telegram task automation direction: the public Rust `Task-manager` and the private `Task Manage Bot` case study with AI/voice-to-task logic, reminders, assignments and operational workflows.

**Problem it solves:** tasks in chats, voice messages and fast conversations are easy to lose. A system is needed to turn unstructured communication into tasks, deadlines, reminders, statuses and execution control.

**Stack:** Rust, Teloxide, SQLx, Docker, GitHub Actions, Python/aiogram for the private AI workflow, PostgreSQL/SQLite, reminders, async jobs and structured logging.

**Architecture:** the bot layer handles commands/messages, the domain layer owns tasks and statuses, the storage layer persists data, the scheduler/outbox processes reminders, and retry/idempotency patterns protect the workflow from failures.

**Why this architecture:** a Telegram bot becomes messy quickly if commands, business logic and database access are mixed. Layer separation makes the code clearer, more testable and easier to evolve.

**Unique strengths:** the combination of public Rust proof, CI, clean bot architecture and private AI automation shows reliability plus the ability to build real workflow tools.

**Employer signal:** ability to build operational automation: async jobs, reminders, state, retries, Telegram UX and backend discipline.

**Safe proof:** [public repository](https://github.com/SamandarMansurkhodjaev2713/Task-manager), GitHub Actions CI, project card and private case study.

## Quality engineering

**Implemented quality coverage:** Rust unit, regression and repository-integration tests for RBAC, onboarding, deadlines, notifications, voice processing, prompt schemas and persistence. Automation focuses on repeatable critical rules where a defect can create a wrong assignee, status or notification.

[Full QA evidence matrix](https://github.com/SamandarMansurkhodjaev2713/qa-engineering-portfolio/blob/main/docs/project-quality-matrix.md)

---

[Назад к галерее](README.md) | [Case study](../case-studies/task-manage-bot.md) | [Главная витрина](../README.md)
