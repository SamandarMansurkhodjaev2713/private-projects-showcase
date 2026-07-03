# Task Manage Bot

## Русский

**Кратко:** Telegram task automation направление: публичный Rust Task-manager и приватный AI/voice-to-task workflow для превращения сообщений в задачи, сроки, напоминания и статусы.

**Проблема:** задачи в чатах быстро теряются. Нужен bot workflow, который переводит неструктурированную коммуникацию в управляемый процесс с надежными напоминаниями.

**Стек:** Rust, Teloxide, SQLx, Docker, GitHub Actions, Python/aiogram, PostgreSQL/SQLite, async jobs, reminders.

**Архитектура:** bot layer принимает команды; domain layer управляет задачами и статусами; storage layer хранит данные; scheduler/outbox обрабатывает напоминания; retries/idempotency защищают workflow.

**Почему так:** боты быстро становятся неподдерживаемыми, если смешать команды, storage и бизнес-логику. Слои делают систему понятнее и надежнее.

**Что доказывает:** Telegram automation, async backend thinking, Rust public proof, CI, reminders, workflow design и operational reliability.

**Proof:** <https://github.com/SamandarMansurkhodjaev2713/Task-manager>

## English

**Summary:** a Telegram task automation direction: public Rust Task-manager and private AI/voice-to-task workflow for turning messages into tasks, deadlines, reminders and statuses.

**Problem:** tasks in chats are easy to lose. The bot workflow turns unstructured communication into a managed process with reliable reminders.

**Stack:** Rust, Teloxide, SQLx, Docker, GitHub Actions, Python/aiogram, PostgreSQL/SQLite, async jobs and reminders.

**Architecture:** the bot layer handles commands; the domain layer manages tasks and statuses; the storage layer persists data; the scheduler/outbox handles reminders; retries/idempotency protect the workflow.

**Why this architecture:** bots become hard to maintain if commands, storage and business logic are mixed. Layers make the system clearer and more reliable.

**What it proves:** Telegram automation, async backend thinking, Rust public proof, CI, reminders, workflow design and operational reliability.

**Proof:** <https://github.com/SamandarMansurkhodjaev2713/Task-manager>

---

[Карточка проекта](../cards/task-manage-bot.md) | [Назад к case studies](README.md)
