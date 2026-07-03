# Sentinel Edge / smart-system

## Русский

**Кратко:** публичный embedded/full-stack проект: Arduino-style C++ firmware, serial protocol, Node.js bridge и React/Vite realtime dashboard.

**Проблема:** embedded демо часто ограничиваются показом sensor values. Здесь важен полный контур: сбор данных, baseline learning, anomaly/events, serial protocol, bridge и dashboard для оператора.

**Стек:** Arduino-style C++, Node.js, serial protocol, WebSocket, React, Vite, realtime charts.

**Архитектура:** firmware формирует telemetry/events; serial protocol передает `TEL`, `EVT`, `CMD`; Node bridge переводит serial stream в WebSocket/API; React dashboard отображает состояние, графики, события и control surface.

**Почему так:** физическое устройство, протокол и UI должны быть разделены, чтобы их можно было независимо тестировать, объяснять и развивать.

**Что доказывает:** широту beyond web: firmware, protocol design, realtime data, dashboard UX, public repo, live dashboard и clean documentation.

**Proof:** <https://github.com/SamandarMansurkhodjaev2713/sentinel-edge-smart-system><br>
**Demo:** <https://samandarmansurkhodjaev2713.github.io/sentinel-edge-smart-system/>

## English

**Summary:** a public embedded/full-stack project: Arduino-style C++ firmware, serial protocol, Node.js bridge and React/Vite realtime dashboard.

**Problem:** embedded demos often stop at sensor values. This project covers the full loop: data collection, baseline learning, anomaly/events, serial protocol, bridge and operator dashboard.

**Stack:** Arduino-style C++, Node.js, serial protocol, WebSocket, React, Vite and realtime charts.

**Architecture:** firmware produces telemetry/events; the serial protocol sends `TEL`, `EVT`, `CMD`; the Node bridge converts the serial stream into WebSocket/API; the React dashboard shows state, charts, events and control surface.

**Why this architecture:** physical device logic, protocol and UI should be separated so they can be tested, explained and evolved independently.

**What it proves:** breadth beyond web: firmware, protocol design, realtime data, dashboard UX, public repo, live dashboard and clean documentation.

**Proof:** <https://github.com/SamandarMansurkhodjaev2713/sentinel-edge-smart-system><br>
**Demo:** <https://samandarmansurkhodjaev2713.github.io/sentinel-edge-smart-system/>

---

[Карточка проекта](../cards/sentinel-edge.md) | [Назад к case studies](README.md)
