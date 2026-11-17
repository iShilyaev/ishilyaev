# ByggExp — admin dashboard and backend

**Status:** Draft; ownership, claims, and publication permission need Igor's confirmation.

## Source-reported overview

The FL.ru listing describes an office web panel for a construction SaaS used in Sweden/Scandinavia. Listed areas include companies, people, projects, shifts, tasks, tools, and invoices, with role-based access from super-admin to on-site worker. It also describes a shared API for the admin panel, app, and website.

- Source listing: [FL.ru work 8080766](https://www.fl.ru/user/monnarxx/portfolio/8080766/)
- Admin link shown by source: [admin.byggexp.se](https://admin.byggexp.se)
- Frontend stack reported by source: Next.js, React, Ant Design, Zustand, Axios, SCSS, Leaflet, Vitest
- Backend stack reported by source: NestJS, TypeScript, MongoDB/Mongoose, JWT, Stripe, PDFKit, Nodemailer, Expo Push
- Listing dates: published 2026-09-10; updated 2026-09-11 (as displayed on FL.ru)

## Описание, вклад и технологии

**Описание:** SaaS для строительных компаний в Швеции и Скандинавии. Админ-панель объединяет компании, сотрудников, проекты, смены, задачи, инструменты и счета; доступ разграничен по ролям от суперадминистратора до рабочего на объекте.

**Мой вклад по карточке FL.ru:** миграция фронтенда с Vite на Next.js и перестройка разделов; общие UI-компоненты; авторизация, календарь смен, проекты, задачи, инструменты, счета/предложения, отчёты об ошибках, дашборды и онлайн-статус сотрудников; настройка деплоя на VPS. На backend карточка также указывает онбординг компаний и приглашения, файлы и координаты проектов, историю/экспорт смен, push-уведомления, чаты, склад, счета/предложения, клиентов, геокодирование, API блога/SEO, CI/CD и CORS для мобильного клиента. Личное авторство и границы ответственности по каждому пункту нужно подтвердить.

**Технологии по карточке FL.ru:**

- Frontend: Next.js, React, Ant Design, Zustand, Axios, SCSS, Leaflet, Vitest.
- Backend: NestJS, TypeScript, MongoDB/Mongoose, JWT, Stripe, PDFKit, Nodemailer, Expo Push.
- Раздел «Инструменты и навыки» на FL.ru дополнительно указывает REST APIs; остальные теги входят в перечисленный стек.
- Это стек, указанный в листинге проекта; личное использование каждой технологии Игорем требует подтверждения.

**Результаты:** проверенные бизнес-метрики в карточке не приведены.

## Duplicate and relationship note

The FL.ru profile also lists [ByggExp Website](byggexp-website.md) and [ByggExp App](byggexp-app.md). The source calls this a shared SaaS/API ecosystem, so these entries are likely related components; whether to consolidate them into one case study or keep separate case studies is unconfirmed.

## Confirm with Igor

- Was this your work, and which listed contributions were yours personally?
- Are the technologies and feature list accurate and safe to disclose?
- What were your title, timeframe, team, architecture decisions, challenges, and results?
- Is the client/product name, admin link, and any screenshots or metrics cleared for publication?
