# Klawis

## Русский

**Кратко:** задеплоенный legal AI продукт, который помогает пользователю разобраться в юридической ситуации через структурирование, retrieval, источники и аккуратное объяснение.

**Проблема:** юридический AI должен быть проверяемым. Важно не только сгенерировать текст, но и показать источники, учитывать контекст, не создавать ложной уверенности и поддерживать понятный UX для чувствительного домена.

**Стек:** FastAPI, Next.js, Supabase, PostgreSQL, RAG, structured outputs, auth, source/document handling.

**Архитектура:** frontend собирает ситуацию и показывает понятный legal UX; backend отвечает за routing, retrieval, AI pipeline и валидацию; Supabase хранит данные и auth; RAG слой связывает ответ с источниками.

**Почему так:** legal AI нельзя строить как один prompt. Отдельные слои для intake, routing, retrieval, generation и validation дают контроль качества и снижают риск некорректной выдачи.

**Что доказывает:** applied AI, RAG, sensitive-domain UX, product thinking, live deployment и roadmap-driven развитие.

**Live:** <https://klawis.uz>

## English

**Summary:** a deployed legal AI product that helps users understand a legal situation through structuring, retrieval, sources and careful explanation.

**Problem:** legal AI must be traceable. It is not enough to generate text; the product must show sources, respect context, avoid false certainty and support careful UX in a sensitive domain.

**Stack:** FastAPI, Next.js, Supabase, PostgreSQL, RAG, structured outputs, auth and source/document handling.

**Architecture:** the frontend collects the situation and presents legal UX; the backend handles routing, retrieval, AI pipeline and validation; Supabase stores data and auth; the RAG layer connects answers to sources.

**Why this architecture:** legal AI should not be a single prompt. Separate layers for intake, routing, retrieval, generation and validation provide quality control and reduce the risk of incorrect output.

**What it proves:** applied AI, RAG, sensitive-domain UX, product thinking, live deployment and roadmap-driven product development.

**Live:** <https://klawis.uz>

---

[Карточка проекта](../cards/klawis.md) | [Назад к case studies](README.md)
