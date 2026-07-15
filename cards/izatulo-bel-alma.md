# IZATULO / BEL ALMA

<p>
  <img alt="Frontend" src="https://img.shields.io/badge/Frontend-HTML%20CSS%20JS-c64b36?style=flat-square">
  <img alt="Languages" src="https://img.shields.io/badge/i18n-RU%20UZ%20EN-0f766e?style=flat-square">
  <img alt="SEO" src="https://img.shields.io/badge/SEO-hreflang%20%2B%20schema-334155?style=flat-square">
  <img alt="QA" src="https://img.shields.io/badge/QA-Playwright-15803d?style=flat-square">
</p>

## Русский

> **Главный сигнал:** коммерческий сайт поставщика построен как быстрый мультиязычный sales-инструмент с проверяемым контентом, SEO и мобильным conversion flow.

| Быстрый взгляд | Деталь |
|---|---|
| Статус | Публичный коммерческий frontend-проект |
| Моя роль | Product/UX direction, frontend implementation, content architecture, SEO и QA |
| Продукт | Сайт официального дилера угля BEL ALMA в Узбекистане |
| Доказательства | Public repo, RU/UZ/EN, runtime validation, Playwright E2E |

**Проблема и ценность:** B2B-покупателю нужно быстро сравнить фракции, характеристики и назначение угля, увидеть доказательства поставки и перейти в привычный Telegram-канал. Контент структурирован вокруг выбора продукта и доверия, а не вокруг абстрактного имиджа.

**Архитектура:** статические HTML/CSS/JavaScript modules без обязательной сборки; данные и переводы вынесены в отдельный content layer; runtime validators проверяют контакты, товары и ассеты. Canonical, hreflang, Open Graph, FAQ schema и sitemap поддерживают поисковую видимость.

**Почему именно так:** для небольшого каталога статическая архитектура быстрее, дешевле и надёжнее фреймворка. Форма не отправляет персональные данные на случайный backend: она валидирует ввод и открывает Telegram с подготовленным черновиком, оставляя отправку под контролем пользователя.

**Качество:** Playwright проверяет языки, форму, мобильное меню, изображения и отсутствие горизонтального overflow; отдельные проверки валидируют контент и файлы. Layout адаптирован для desktop/tablet/mobile, а мобильная CTA-панель появляется после первого экрана и не дублирует hero.

**Ссылки:** [публичный репозиторий](https://github.com/SamandarMansurkhodjaev2713/izatullo-komir-) · [живой сайт](https://samandarmansurkhodjaev2713.github.io/izatullo-komir-/)

## English

> **Main signal:** a commercial supplier website built as a fast multilingual sales tool with validated content, SEO and a mobile conversion flow.

| Quick view | Detail |
|---|---|
| Status | Public commercial frontend project with live demo |
| My role | Product and UX direction, frontend implementation, content architecture, SEO and QA |

Static HTML/CSS/JavaScript keeps deployment simple and fast. Content and RU/UZ/EN translations are separated from rendering; runtime validation protects product/contact data; canonical, hreflang, structured data and sitemap support SEO. Playwright covers language switching, forms, mobile navigation, images and horizontal overflow.

**Links:** [repository](https://github.com/SamandarMansurkhodjaev2713/izatullo-komir-) · [live website](https://samandarmansurkhodjaev2713.github.io/izatullo-komir-/)

---
[Назад к галерее](README.md) | [Главная витрина](../README.md)