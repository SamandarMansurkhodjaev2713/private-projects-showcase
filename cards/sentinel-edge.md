# Sentinel Edge / smart-system

<p>
  <img alt="Arduino" src="https://img.shields.io/badge/Arduino-Firmware-00878f?style=flat-square">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-Serial%20Bridge-339933?style=flat-square">
  <img alt="React" src="https://img.shields.io/badge/React-Realtime%20Dashboard-149eca?style=flat-square">
  <img alt="Public" src="https://img.shields.io/badge/Repo-Public-15803d?style=flat-square">
</p>

## Русский

> **Главный сигнал:** публичный proof, где видно весь путь от firmware и serial protocol до realtime dashboard.

| Быстрый взгляд | Деталь |
|---|---|
| Продукт | Embedded + full-stack smart environment system |
| Статус | Публичный проект · dashboard demo |
| Моя роль | System architecture, firmware/bridge/dashboard integration и QA planning |
| Сложность | C++ firmware, protocol, Node bridge, WebSocket, React dashboard |
| Эффект | Показывает широту: hardware-adjacent logic, backend bridge и UI |

**Что это:** Sentinel Edge / smart-system - публичный embedded + full-stack проект: firmware на Arduino-style C++, serial protocol, Node.js bridge и React/Vite realtime dashboard для локальной smart environment системы.

**Какую проблему решает:** многие embedded демо заканчиваются выводом данных с датчика. Здесь проект показывает полный контур: сбор телеметрии, baseline learning, anomaly scoring, события, serial communication, bridge и операторский dashboard.

**Стек:** Arduino-style C++, Node.js, serial protocol, WebSocket, React, Vite, realtime charts, local dashboard architecture.

**Архитектура:** firmware отвечает за датчики, baseline и события; serial protocol передает `TEL`, `EVT` и `CMD`; Node bridge превращает serial поток в WebSocket/API; React dashboard показывает состояние, графики, события и operator controls.

**Почему именно так:** embedded-система должна быть локальной, понятной и устойчивой. Разделение firmware, bridge и dashboard позволяет независимо тестировать железо, протокол и интерфейс, а также объяснять систему техлиду без физического доступа к устройству.

**Уникальность и сильные стороны:** это не только web: здесь есть C++/firmware, протокол, realtime поток, edge logic, dashboard и публичный репозиторий с чистой структурой.

**Что доказывает работодателю:** широту инженерного мышления: от low-level sensor logic до frontend dashboard, документации, CI/live demo и аккуратной архитектуры.

**Что можно показать:** [публичный репозиторий](https://github.com/SamandarMansurkhodjaev2713/sentinel-edge-smart-system), [dashboard demo](https://samandarmansurkhodjaev2713.github.io/sentinel-edge-smart-system/), карточку и документацию.

## Как обеспечивалось качество

**QA-фокус и следующий слой:** критичные риски — границы сенсоров, поврежденный serial frame, reconnect, дубли телеметрии и рассинхронизация dashboard. Публичный automated suite не заявляется; следующий проверяемый слой — protocol fixtures, bridge integration tests и hardware-in-the-loop smoke.

[Полная матрица QA-доказательств](https://github.com/SamandarMansurkhodjaev2713/qa-engineering-portfolio/blob/main/docs/project-quality-matrix.md)

## English

> **Main signal:** public proof that shows the full path from firmware and serial protocol to realtime dashboard.

| Quick view | Detail |
|---|---|
| Product | Embedded + full-stack smart environment system |
| Status | Public project · dashboard demo |
| My role | System architecture, firmware/bridge/dashboard integration and QA planning |
| Complexity | C++ firmware, protocol, Node bridge, WebSocket and React dashboard |
| Impact | Shows breadth: hardware-adjacent logic, backend bridge and UI |

**What it is:** Sentinel Edge / smart-system is a public embedded + full-stack project: Arduino-style C++ firmware, serial protocol, Node.js bridge and React/Vite realtime dashboard for a local smart environment system.

**Problem it solves:** many embedded demos stop at printing sensor values. This project shows the full loop: telemetry, baseline learning, anomaly scoring, events, serial communication, bridge and operator dashboard.

**Stack:** Arduino-style C++, Node.js, serial protocol, WebSocket, React, Vite, realtime charts and local dashboard architecture.

**Architecture:** firmware handles sensors, baseline and events; the serial protocol sends `TEL`, `EVT` and `CMD`; the Node bridge turns the serial stream into WebSocket/API; the React dashboard shows state, charts, events and operator controls.

**Why this architecture:** an embedded system should be local, understandable and resilient. Separating firmware, bridge and dashboard makes hardware logic, protocol and UI testable independently and easy to explain without physical device access.

**Unique strengths:** this is more than web: C++/firmware, protocol design, realtime stream, edge logic, dashboard and a public repository with clean structure.

**Employer signal:** broad engineering thinking: from low-level sensor logic to frontend dashboard, documentation, CI/live demo and clear architecture.

**Safe proof:** [public repository](https://github.com/SamandarMansurkhodjaev2713/sentinel-edge-smart-system), [dashboard demo](https://samandarmansurkhodjaev2713.github.io/sentinel-edge-smart-system/), project card and documentation.

## Quality engineering

**Quality focus and next layer:** critical risks include sensor boundaries, malformed serial frames, reconnects, duplicate telemetry and dashboard desynchronization. No public automated suite is claimed; the next evidence layer is protocol fixtures, bridge integration tests and hardware-in-the-loop smoke.

[Full QA evidence matrix](https://github.com/SamandarMansurkhodjaev2713/qa-engineering-portfolio/blob/main/docs/project-quality-matrix.md)

---

[Назад к галерее](README.md) | [Case study](../case-studies/sentinel-edge.md) | [Главная витрина](../README.md)
