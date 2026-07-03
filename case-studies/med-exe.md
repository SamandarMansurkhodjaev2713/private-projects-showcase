# med-exe

## Русский

**Кратко:** приватное offline desktop приложение для medical/research расчетов, patient profiles и локальной работы с чувствительной логикой.

**Проблема:** health-tech инструменты требуют deterministic calculations, воспроизводимости, privacy-aware storage и clean separation между UI и core logic.

**Стек:** Rust, Tauri, React/TypeScript, SQLite, typed IPC, local persistence, domain/calculation modules.

**Архитектура:** Tauri дает desktop runtime; React отвечает за UI и формы; Rust core содержит доменные правила и расчеты; SQLite хранит данные локально; typed IPC фиксирует границу между UI и core.

**Почему так:** чувствительная расчетная логика должна быть стабильной и тестируемой. Вынесение core logic в Rust снижает риск случайных UI-ошибок.

**Что доказывает:** desktop architecture, Rust domain modeling, offline-first privacy, sensitive-domain thinking и clean architecture.

## English

**Summary:** a private offline desktop application for medical/research calculations, patient profiles and local work with sensitive logic.

**Problem:** health-tech tools require deterministic calculations, reproducibility, privacy-aware storage and clean separation between UI and core logic.

**Stack:** Rust, Tauri, React/TypeScript, SQLite, typed IPC, local persistence and domain/calculation modules.

**Architecture:** Tauri provides the desktop runtime; React handles UI and forms; the Rust core contains domain rules and calculations; SQLite stores data locally; typed IPC keeps the UI/core boundary explicit.

**Why this architecture:** sensitive calculation logic must be stable and testable. Moving core logic into Rust reduces the risk of accidental UI-driven errors.

**What it proves:** desktop architecture, Rust domain modeling, offline-first privacy, sensitive-domain thinking and clean architecture.

---

[Карточка проекта](../cards/med-exe.md) | [Назад к case studies](README.md)
