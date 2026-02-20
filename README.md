# Илья Щукин

Frontend / Full Stack Developer, Москва.

[Резюме в PDF](resume_Ilya_Shchukin.pdf)

## Основные технологии:

- Frontend: `TypeScript`, `JavaScript (ES6+, ES2024)`, `React`, `React Router`, `Redux`, `Redux Toolkit`, `RTK Query`, `Webpack`, `SCSS (SASS)`, `CSS3`, `HTML5`, `Vue 3`, `Nuxt 3 (SSR)`, `Vue Router`, `Vuex`, `Pinia`, `Vite`, `Axios`, `Storybook.js`, `Module Federation`, `Apache ECharts`, `Jest`, `Cypress`
- Backend: `.NET Core`, `C#`, `ASP.NET`, `Entity Framework (EF, EF Core)`, `Java`, `Spring Framework`, `Spring Boot`, `Node.js`, `Express.js`
- DB: `Microsoft SQL Server`, `PostgreSQL`, `SQL`
- Infra: `Git`, `Figma`, `GitLab CI/CD`, `NPM`, `Apache Kafka`, `Docker`

Умею работать с AI, LLM, пользоваться AI в IDE (`GitHub Copilot`, `Cursor`). Также  умею в `C++20`, `Rust`, `WebAssembly (WASM)`, `OpenCV`, `PowerShell 7`, `Linux`.

## Опыт

### Апрель 2024 - июль 2025: Компания Лоция

Разработка клиентских и менеджерских (Front-office, Back-office) SPA сервисов и микрофронтендов (Module Federation) на Vue 3 для крупной российской компании с сетью партнёров по всей России. Работа в команде из 8 человек по Scrum.

Достижения:
- Разработал раздел аналитических отчётов с таблицами и визуализацией, проведя исследование и внедрив в проект Apache ECharts, что позволило контролировать выполнение KPI партнёрами компании-Заказчика. За счёт высокоуровневого декларативного интерфейса раздела минимизировано количество работы для добавления новых отчётов, сохраняя возможность кастомизации при необходимости.
- Был ответственным за поддержку и расширение UI Kit и других npm-пакетов, реализующих единую дизайн-систему, общие сервисы и контракты между 5+ приложениями.  Миграция компонентов на Vue 3 Composition API.
- Участвовал в построении системы аутентификации и авторизации для Micro Frontend сервисов на портале.
- Разработал с нуля Micro Frontend Front-office/Back-office сервис для создания заявок на заключение контракта клиентами и менеджерами с автодополнением, интеграцией с личным кабинетом залогиненных пользователей, интеграцией с DaData.
- Провёл редизайн, рефакторинг и решил баги в разделах, работающих с Yandex Maps API.
- Разрабатывал и интегрировал микрофронтенды в клиентский Портал, обеспечивая бесшовный пользовательский путь, что позволило упростить и ускорить получение пользователями услуг и сервисов.
- Провёл рефакторинг и модернизировал архитектуру роутинга (Vue Router), что ускорило работу пользователей за счёт интуитивной навигации  вперёд-назад, ссылок между сущностями и сохранения фильтров и параметров на нескольких уровнях вложенных таблиц.
- Внедрил в проекты инструменты контроля качества кода (ESLint, Prettier, Husky), улучшил типизацию TypeScript, участвовал в разработке и внедрении flow работы с git, проводил Code Review.

Стек:
- `Vue 3`, `TypeScript`, `JavaScript (ES6+`, `ES2024)`, `Pinia`, `Nuxt.js 3 (SSR)`, `Vue Router`, `Axios`, `SCSS`, `CSS3`, `HTML5`, `Figma`, `Storybook.js`, `Vite-Module-Federation`, `Git`, `NPM`, `Node.js`, `Apache ECharts`, `Jest`, `Cypress`, `Scrum`, `BEM`, `FSD`, `ESLint`, `Prettier`, `Husky`, `Day.js`, `TanStack Query`, `Bootstrap 5`, `Swagger`

### Октябрь 2021 - апрель 2024: Компания BTLab

Работал над проектами разработки, расширения и поддержки систем электронного документооборота (СЭД) и других Back-office-сервисов для Компаний-заказчиков в составе кросс-функциональных Agile-команд на разных стеках в роли Full Stack разработчика. Ведущий разработчик на двух проектах.

Достижения:
- В сжатые сроки интегрировал СЭД с системой юридически значимого электронного документооборота Контур.Диадок по протоколу REST, что позволило в 2 раза сократить объем работы для подготовки документов и обеспечить бесшовный сценарий работы для пользователей, включая работу с криптографией (электронные подписи документов). Реализация в виде набора UI компонентов позволила использовать интеграцию во встроенных инструментах low-code платформы.
- С нуля до релиза разработал десктопное приложение-компаньон для СЭД, повысив оперативность работы сотрудников организации-клиента.
- Интегрировал в SPA СЭД аналитические отчёты SQL Server Reporting Services, что избавило пользователей от необходимости посещения другой платформы и ручного ввода параметров, повысило безопасность и упростило управление правами доступа в Организации, позволило "запустить" пользовательскую обратную связь и расширение ассортимента отчётов. Впоследствии в рамках другого проекта на другом стеке использовал опыт для реализации и внедрения системы аналитических отчётов Jasper Reports.
- Во взаимодействии с командой 1С разработки Заказчика запустил интеграцию и обмен метаданными документов между системами по протоколу SOAP, исключив необходимость двойного учёта.
- Запустил процесс Progressive Enhancement на Vue веб-интерфейса СЭД, реализованного на основе шаблонизатора, что позволило уменьшать количество технического долга и модернизировать систему в контролируемом темпе, избегая регрессий и нарушения работы пользователей.
- Внедрил TypeScript и провёл модернизацию React + Redux проекта, перейдя на React hooks, Redux Toolkit вместо Redux, что в совокупности снизило вероятность багов, уменьшило количество бойлерплейта и улучшило developer experience, позволив быстрее и качественнее доставлять фичи в production.
- Исследовал проблемы с производительностью, используя инструменты .Net (PerfView), Java (VisualVM), MS SQL Server и PostgreSQL для поиска причин и их решения, проводил оптимизацию и рефакторинг.
- Участвовал в онбординге новых разработчиков, проводил Code Review.
- Внедрил инструменты контроля качества кода (ESLint, Prettier, Husky) и unit/интеграционного-тестирования, работал с GitLab CI/CD, участвовал в обсуждении и принятии flow работы с git, правил наименования коммитов, интеграции GitLab с кастомным таск-трекером на базе Redmine.

Стек:
- Frontend: `TypeScript`, `JavaScript (ES6+`, `ES2024)`, `React`, `React Router`, `Redux`, `Redux Toolkit`, `RTK Query`, `Webpack`, `Material UI`, `SCSS`, `CSS3`, `HTML5`, `SignalR`, `WebSocket`, `Vue`, `Nuxt 3`, `Vue Router`, `Vuex`, `Pinia`, `Vite`, `ESLint`, `Prettier`, `Husky`, `REST API`, `Tailwind CSS`, `Bootstrap 5`
- Backend: `.Net`, `C#`, `ASP.NET`, `Entity Framework (EF)`, `Java`, `Spring Framework`, `Spring Boot`, `Node.js`, `Express (Backend-For-Frontend)`, `REST API`, `SOAP`, `Swagger`
- DB: `Microsoft SQL Server`, `PostgreSQL`, `Solr`
- Infra: `Git`, `Figma`, `Jira`, `Redmine`, `GitLab CI/CD`, `Jenkins`, `Zabbix`, `Prometheus`, `NPM`, `Maven`, `NuGet`, `CentOS`, `Apache Kafka`, `Docker`

## Образование

### Санкт-Петербургский Государственный Университет

- 2021 г. - получил степень бакалавра по специальности "прикладная математика и информатика", факультет Прикладной Математики и Процессов Управления

## О себе

Software Developer и Frontend-разработчик с опытом Vue и React, Progressive Enhancement и модернизации legacy-кода, сильными скиллами в TypeScript, UI/UX и архитектуре за счёт опыта работы на позиции ведущего Full Stack разработчика.

Работал в кросс-функциональных командах по Scrum и Agile, оптимизировал и улучшал стабильность критичных для бизнеса высоконагруженных сервисов.

Имею опыт разработки и поддержки B2C и B2B Multi-Page, SPA и SSR-приложений.

Участвовал в архитектурных решениях, проводил Code Review, осуществлял модернизацию, Progressive Enhancement и рефакторинг; развивал и внедрял frontend-практики и Developer Experience инструментарий.

Слежу за актуальными технологиями и ландшафтом стеков.

Рассматриваю задачи системно, с учётом пользовательского пути, принципов UX, архитектуры системы, нагрузки и дальнейшей поддержки.

Хорошо знаю Git, умею решать проблемы и не допускать их возникновения.

Умею находить и решать проблемы с производительностью, оценивать асимптотическую сложность алгоритмов и подбирать эффективные структуры данных.

Люблю, внедряю, использую и развиваю статическую типизацию и паттерны функционального программирования.

Подтверждённый уровень владения английским языком - B2. Ежедневно взаимодействую с техническим и художественным контентом на английском.

## Контактные данные

- [GitHub: ishchukin](https://github.com/ishchukin)
- [Telegram: @Xowl17](https://t.me/Xowl17)
- Почта: ishchukin () outlook () com

## Стек / Технологии

`TypeScript`, `JavaScript (ES6+`, `ES2024)`, `React`, `React Router`, `Redux`, `Redux Toolkit`, `RTK Query`, `Webpack`, `Material UI`, `SCSS (SASS)`, `CSS3`, `HTML5`, `SignalR`, `WebSocket`, `Vue 3`, `Nuxt 3 (SSR)`, `Vue Router`, `Vuex`, `Pinia`, `Vite`, `ESLint`, `Prettier`, `Husky`, `Axios`, `Storybook.js`, `Module Federation`, `Vite-Module-Federation`, `Apache ECharts`, `Jest`, `Cypress`, `Scrum`, `Agile`, `BEM`, `БЭМ`, `Feature Sliced Design (FSD)`, `Day.js`, `TanStack Query`, `TanStack Table`, `REST API`, `.Net`, `.NET Core`, `C#`, `ASP.NET`, `Entity Framework (EF`, `EF Core)`, `Java`, `Spring Framework`, `Spring Boot`, `Node.js`, `Express.js`, `BFF`, `CORS`, `Web Vitals`, `CSRF`, `SOAP`, `Microsoft SQL Server`, `PostgreSQL`, `Solr`, `Git`, `Figma`, `Jira`, `Redmine`, `GitLab CI/CD`, `Jenkins`, `Zabbix`, `Prometheus`, `NPM`, `Maven`, `NuGet`, `CentOS`, `Apache Kafka`, `Docker`, `DaData`, `KISS`, `DRY`, `SSOT`, `SOLID`, `TDD`, `WebAssembly (WASM)`, `SQL`, `OpenCV`, `AI`, `LLM`, `Cursor`, `Адаптивная верстка`, `Styled components`, `SCSS Modules / SASS Modules`
