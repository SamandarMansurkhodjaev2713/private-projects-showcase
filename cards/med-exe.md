# med-exe

<p>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-Core-000000?style=flat-square">
  <img alt="Tauri" src="https://img.shields.io/badge/Tauri-Desktop-24c8db?style=flat-square">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-Offline-003b57?style=flat-square">
  <img alt="Health" src="https://img.shields.io/badge/Signal-Sensitive%20Domain-991b1b?style=flat-square">
</p>

## Русский

> **Главный сигнал:** offline desktop app для чувствительного домена, где важны Rust core, typed boundaries и точность.

| Быстрый взгляд | Деталь |
|---|---|
| Продукт | Health-tech/research desktop application |
| Сложность | Rust calculations, Tauri shell, typed IPC, SQLite, offline privacy |
| Эффект | Показывает аккуратность в домене, где ошибки и данные критичны |

**Что это:** med-exe - приватное offline desktop приложение для медицинских/исследовательских расчетов, patient profiles и локальной работы с чувствительной расчетной логикой.

**Какую проблему решает:** в health-tech и research-инструментах нельзя полагаться на “примерно работает”. Важны deterministic calculations, воспроизводимость, приватность, offline mode и понятное разделение UI от доменной логики.

**Стек:** Rust, Tauri, React/TypeScript, SQLite, typed IPC, local persistence, calculation/domain modules.

**Архитектура:** Tauri shell дает desktop runtime, React UI отвечает за формы и сценарии, Rust core хранит расчетную логику и правила домена, SQLite обеспечивает локальное хранение, а typed IPC держит границу между UI и core.

**Почему именно так:** чувствительная расчетная логика должна быть отделена от интерфейса. Это упрощает тестирование, снижает риск случайных ошибок в UI и делает приложение пригодным для offline-first использования.

**Уникальность и сильные стороны:** desktop architecture, Rust domain modeling, offline-first privacy, аккуратные границы между слоями и работа с доменом, где точность важнее скорости “накидать UI”.

**Что доказывает работодателю:** способность проектировать приложения для чувствительных доменов: стабильность, воспроизводимость, локальное хранение, typed boundaries и clean architecture.

**Что можно показать:** code-safe case study, архитектуру, обезличенный walkthrough и screenshots без персональных данных.

## English

> **Main signal:** an offline desktop app for a sensitive domain where Rust core, typed boundaries and accuracy matter.

| Quick view | Detail |
|---|---|
| Product | Health-tech/research desktop application |
| Complexity | Rust calculations, Tauri shell, typed IPC, SQLite and offline privacy |
| Impact | Shows care in a domain where errors and data are critical |

**What it is:** med-exe is a private offline desktop application for medical/research calculations, patient profiles and local work with sensitive calculation logic.

**Problem it solves:** health-tech and research tools cannot rely on “it roughly works”. Deterministic calculations, reproducibility, privacy, offline mode and clear separation between UI and domain logic matter.

**Stack:** Rust, Tauri, React/TypeScript, SQLite, typed IPC, local persistence and calculation/domain modules.

**Architecture:** the Tauri shell provides the desktop runtime, React UI handles forms and workflows, the Rust core owns calculation logic and domain rules, SQLite provides local storage, and typed IPC keeps the boundary between UI and core clear.

**Why this architecture:** sensitive calculation logic should be separated from the interface. This improves testing, reduces accidental UI-driven errors and makes the app suitable for offline-first use.

**Unique strengths:** desktop architecture, Rust domain modeling, offline-first privacy, clean layer boundaries and work in a domain where accuracy matters more than quickly assembling a UI.

**Employer signal:** ability to design applications for sensitive domains: stability, reproducibility, local storage, typed boundaries and clean architecture.

**Safe proof:** code-safe case study, architecture, anonymized walkthrough and screenshots without personal data.

---

[Назад к галерее](README.md) | [Case study](../case-studies/med-exe.md) | [Главная витрина](../README.md)
