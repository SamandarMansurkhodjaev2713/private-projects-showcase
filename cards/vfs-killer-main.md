# VFS Killer Main

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-Automation-3776ab?style=flat-square">
  <img alt="Playwright" src="https://img.shields.io/badge/Playwright-Browser%20Control-2f855a?style=flat-square">
  <img alt="Telegram" src="https://img.shields.io/badge/Telegram-Bot-229ed9?style=flat-square">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-Runtime-2496ed?style=flat-square">
</p>

## Русский

> **Главный сигнал:** automation не для happy path, а для нестабильного внешнего workflow с диагностикой и операторским контролем.

| Быстрый взгляд | Деталь |
|---|---|
| Продукт | Browser automation система с Telegram control |
| Сложность | Sessions, timing, retries, diagnostics, Docker runtime |
| Эффект | Показывает надежную автоматизацию в реальных, ломких условиях |

**Что это:** VFS Killer Main - приватная browser automation система для сложного внешнего workflow, управляемая через Telegram bot и поддержанная diagnostics-first инструментами.

**Какую проблему решает:** реальные browser workflows ломаются из-за таймингов, сессий, внешнего состояния, сетевых ошибок, прокси, нестабильных страниц и anti-automation friction. В таких задачах недостаточно написать “скрипт, который кликает кнопки”.

**Стек:** Python, Playwright/Camoufox, aiogram, Docker, Telegram bot interface, diagnostics, local state handling, retry/error flow.

**Архитектура:** workflow engine управляет шагами сценария, browser layer изолирует автоматизацию, Telegram bot дает оператору контроль и статусы, diagnostics помогает быстро понять сбой, а Docker/runtime слой делает запуск повторяемым.

**Почему именно так:** автоматизация внешней системы должна быть наблюдаемой и управляемой. Если сделать только headless script, при первом нестабильном кейсе он станет черным ящиком. Поэтому здесь важны retries, logs, screenshots, operator control и clear state boundaries.

**Уникальность и сильные стороны:** проект демонстрирует практическую автоматизацию в реальном мире: нестабильные внешние системы, диагностика, Telegram control, container runtime и умение проектировать не только happy path.

**Что доказывает работодателю:** способность решать сложные automation-задачи, где важны reliability, debugging, observability, security boundaries и productized operator experience.

**Что можно показать:** code-safe architecture, demo script, обезличенный workflow, screenshots diagnostics и описание без приватных данных.

## Как обеспечивалось качество

**Code-safe QA-кейс:** pytest и async integration flow проверяли конфигурацию, worker-сценарий, обнаружение сигнала и его передачу через Redis в следующий этап. Внешний сайт отделен от детерминированной логики, потому что нестабильную третью сторону нельзя делать единственной основой regression suite.

[Полная матрица QA-доказательств](https://github.com/SamandarMansurkhodjaev2713/qa-engineering-portfolio/blob/main/docs/project-quality-matrix.md)

## English

> **Main signal:** automation built for unstable external workflows, not happy-path scripting.

| Quick view | Detail |
|---|---|
| Product | Browser automation system with Telegram control |
| Complexity | Sessions, timing, retries, diagnostics and Docker runtime |
| Impact | Shows reliable automation under fragile real-world conditions |

**What it is:** VFS Killer Main is a private browser automation system for a complex external workflow, controlled through a Telegram bot and supported by diagnostics-first tooling.

**Problem it solves:** real browser workflows fail because of timing, sessions, external state, network issues, proxies, unstable pages and anti-automation friction. In this domain, “a script that clicks buttons” is not enough.

**Stack:** Python, Playwright/Camoufox, aiogram, Docker, Telegram bot interface, diagnostics, local state handling and retry/error flow.

**Architecture:** the workflow engine controls scenario steps, the browser layer isolates automation, the Telegram bot gives operators control and status, diagnostics helps understand failures quickly, and the Docker/runtime layer makes execution repeatable.

**Why this architecture:** automation against external systems must be observable and controllable. A simple headless script becomes a black box at the first unstable case, so retries, logs, screenshots, operator control and state boundaries are essential.

**Unique strengths:** the project demonstrates practical real-world automation: unstable external systems, diagnostics, Telegram control, container runtime and thinking beyond the happy path.

**Employer signal:** ability to solve hard automation problems where reliability, debugging, observability, security boundaries and productized operator experience matter.

**Safe proof:** code-safe architecture, demo script, anonymized workflow, diagnostic screenshots and description without private data.

## Quality engineering

**Code-safe QA case:** pytest and an asynchronous integration flow covered configuration, worker behavior, signal detection and Redis delivery into the next stage. External-site behavior is separated from deterministic logic because an unstable third party should not be the only regression oracle.

[Full QA evidence matrix](https://github.com/SamandarMansurkhodjaev2713/qa-engineering-portfolio/blob/main/docs/project-quality-matrix.md)

---

[Назад к галерее](README.md) | [Case study](../case-studies/vfs-killer-main.md) | [Главная витрина](../README.md)
