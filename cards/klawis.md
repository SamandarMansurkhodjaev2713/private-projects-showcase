# Klawis

<p>
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-API-009688?style=flat-square">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-Frontend-111111?style=flat-square">
  <img alt="RAG" src="https://img.shields.io/badge/RAG-Citations-6d28d9?style=flat-square">
  <img alt="Live" src="https://img.shields.io/badge/Live-klawis.uz-15803d?style=flat-square">
</p>

## Русский

> **Главный сигнал:** это не prompt-demo, а live legal AI продукт с источниками, доменной логикой и roadmap.

| Быстрый взгляд | Деталь |
|---|---|
| Продукт | Legal AI assistant, доступный на [klawis.uz](https://klawis.uz) |
| Сложность | RAG, legal routing, citations, sensitive-domain UX |
| Эффект | Показывает applied AI, где важны доверие, доказательность и продуктовая ответственность |

**Что это:** Klawis - задеплоенный legal AI продукт, который помогает пользователю разобраться в юридической ситуации: структурирует проблему, определяет направление, подбирает релевантные источники, объясняет возможные шаги и делает ответ проверяемым.

**Какую проблему решает:** обычный chatbot в юридическом домене недостаточен: важны источники, юрисдикция, аккуратность формулировок, ограничения ответственности и доверие к ответу. Klawis строится как продукт, где AI не просто “отвечает красиво”, а работает через контекст, документы, routing и проверяемую выдачу.

**Стек:** FastAPI, Next.js, Supabase, PostgreSQL, RAG, AI provider integrations, structured outputs, authentication, document/source handling.

**Архитектура:** frontend отвечает за понятный legal UX, backend управляет доменной логикой, retrieval и AI-пайплайном, Supabase используется для данных, auth и storage, а слой RAG отделяет генерацию ответа от источников и доказательной базы.

**Почему именно так:** legal AI нельзя строить как один prompt. Нужны отдельные слои: intake пользовательской ситуации, legal routing, retrieval, цитирование, генерация, validation и UX, который не создает ложной уверенности. Такая архитектура дает больше контроля, качества и доверия.

**Уникальность и сильные стороны:** live product, чувствительный домен, roadmap развития, работа с источниками, продуктовая упаковка, UX для сложного сценария, сочетание AI engineering и legal-tech мышления.

**Что доказывает работодателю:** умение строить AI-продукты не на уровне демо, а как реальную систему: с архитектурой, источниками, ограничениями домена, product thinking и понятным пользовательским сценарием.

**Что можно показать:** [live product](https://klawis.uz), архитектурную карточку и безопасное описание без приватной логики.

## Как обеспечивалось качество

**Реализованное QA-покрытие:** pytest для REST API, retrieval, classifier, citations и citation guards; evaluation-наборы качества ответов; Vitest и Playwright для frontend/full-stack сценариев. В Legal AI проверяется не только доступность ответа, но и опора на источники, корректная маршрутизация и защита от уверенного неподтвержденного вывода.

[Полная матрица QA-доказательств](https://github.com/SamandarMansurkhodjaev2713/qa-engineering-portfolio/blob/main/docs/project-quality-matrix.md)

## English

> **Main signal:** this is not a prompt demo, but a live legal AI product with sources, domain logic and a roadmap.

| Quick view | Detail |
|---|---|
| Product | Legal AI assistant live at [klawis.uz](https://klawis.uz) |
| Complexity | RAG, legal routing, citations and sensitive-domain UX |
| Impact | Shows applied AI where trust, evidence and product responsibility matter |

**What it is:** Klawis is a deployed legal AI product that helps users understand a legal situation: it structures the problem, identifies the direction, retrieves relevant sources, explains possible next steps and makes the answer traceable.

**Problem it solves:** a generic chatbot is not enough in a legal domain. Sources, jurisdiction, careful wording, liability boundaries and trust matter. Klawis is designed as a product where AI works through context, documents, routing and verifiable output.

**Stack:** FastAPI, Next.js, Supabase, PostgreSQL, RAG, AI provider integrations, structured outputs, authentication and document/source handling.

**Architecture:** the frontend owns the legal UX, the backend manages domain logic, retrieval and the AI pipeline, Supabase handles data, auth and storage, and the RAG layer separates answer generation from sources and evidence.

**Why this architecture:** legal AI should not be built as one prompt. It needs separate layers for intake, legal routing, retrieval, citations, generation, validation and careful UX. This gives more control, quality and trust.

**Unique strengths:** live product, sensitive domain, active roadmap, source-backed answers, product packaging, complex UX and a blend of AI engineering with legal-tech thinking.

**Employer signal:** shows the ability to build AI products as real systems, not prompt demos: architecture, sources, domain constraints, product thinking and a clear user journey.

**Safe proof:** [live product](https://klawis.uz), architecture card and code-safe product description.

## Quality engineering

**Implemented quality coverage:** pytest for REST APIs, retrieval, classification, citations and citation guards; answer-evaluation datasets; Vitest and Playwright for frontend/full-stack flows. Legal AI quality means validating sources and routing, not merely checking that a response exists.

[Full QA evidence matrix](https://github.com/SamandarMansurkhodjaev2713/qa-engineering-portfolio/blob/main/docs/project-quality-matrix.md)

---

[Назад к галерее](README.md) | [Case study](../case-studies/klawis.md) | [Главная витрина](../README.md)
