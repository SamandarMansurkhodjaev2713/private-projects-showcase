# VFS Killer Main

## Русский

**Кратко:** приватная browser automation система для сложного внешнего workflow, управляемая через Telegram и поддержанная diagnostics-first инструментами.

**Проблема:** внешние browser workflows нестабильны: сессии, тайминги, network/proxy issues, состояние страниц, антиавтоматизация и неожиданные ошибки. Простого click-script недостаточно.

**Стек:** Python, Playwright/Camoufox, aiogram, Docker, Telegram bot, diagnostics, local state, retries.

**Архитектура:** workflow engine управляет сценариями; browser layer изолирует автоматизацию; Telegram bot дает операторский контроль; diagnostics собирает logs/screenshots/status; runtime слой делает запуск воспроизводимым.

**Почему так:** в автоматизации реальная ценность не в кликах, а в управляемости, наблюдаемости и восстановлении после сбоев. Поэтому важны retries, state boundaries, logs и operator feedback.

**Что доказывает:** real-world automation, debugging discipline, reliability thinking, Telegram control, Docker runtime и работа с нестабильными внешними системами.

## English

**Summary:** a private browser automation system for a complex external workflow, controlled through Telegram and supported by diagnostics-first tooling.

**Problem:** external browser workflows are unstable: sessions, timing, network/proxy issues, page state, anti-automation friction and unexpected errors. A simple click-script is not enough.

**Stack:** Python, Playwright/Camoufox, aiogram, Docker, Telegram bot, diagnostics, local state and retries.

**Architecture:** the workflow engine controls scenarios; the browser layer isolates automation; the Telegram bot provides operator control; diagnostics collects logs/screenshots/status; the runtime layer makes execution repeatable.

**Why this architecture:** the real value in automation is not clicking, but control, observability and recovery from failures. Retries, state boundaries, logs and operator feedback matter.

**What it proves:** real-world automation, debugging discipline, reliability thinking, Telegram control, Docker runtime and work with unstable external systems.

---

[Карточка проекта](../cards/vfs-killer-main.md) | [Назад к case studies](README.md)
