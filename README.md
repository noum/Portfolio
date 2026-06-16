<div align="center">

# NOMENTSOA Andrianjatovo (Noom)

### Software Engineer &middot; Full-Stack Web, Performance & Content Platforms

10+ years building fast, accessible, mobile-first web products in PHP, JavaScript and CSS.

<br>

[![Email](https://img.shields.io/badge/Email-noum77%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:noum77@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-noum-181717?style=flat&logo=github&logoColor=white)](https://github.com/noum)
![Location](https://img.shields.io/badge/Location-Madagascar%20(Remote)-2ea44f?style=flat&logo=googlemaps&logoColor=white)

<br>

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Livewire](https://img.shields.io/badge/Livewire-FB70A9?style=flat&logo=livewire&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)

</div>

---

## Table of Contents

- [About](#about)
- [What I Bring](#what-i-bring)
- [Featured Projects](#featured-projects)
- [Technical Focus Areas](#technical-focus-areas)
- [Open Source Contributions](#open-source-contributions)
- [Experience Snapshot](#experience-snapshot)
- [Education](#education)
- [Languages](#languages)
- [Contact](#contact)

---

## About

Full-stack web engineer with **10+ years** building responsive, mobile-first product experiences in **PHP, JavaScript and CSS**. I turn design mockups into pixel-perfect, accessible components, obsess over page-load performance, and validate everything across browsers and devices.

I have worked across content management systems (WordPress, WooCommerce, PrestaShop, proprietary CMS) and rich-text editors, built reusable APIs that serve multiple surfaces, and shipped AI-powered features. I work autonomously in distributed, remote teams, treat **testing and observability as core**, and care deeply about well-documented, readable code.

> **Note on private repositories:** Most of my code lives in private repositories due to client and commercial work. This portfolio summarizes the architecture, decisions and stack behind key projects I have delivered. I am glad to walk through code samples and system design in detail on request.

---

## What I Bring

- **Performance first.** I measure and tune Core Web Vitals with PageSpeed Insights, Vite code-splitting, Redis/Memcached caching, CDN delivery, image optimization and query tuning.
- **Tested everywhere.** Cross-browser and cross-device validation with BrowserStack, CrossBrowserTesting and Playwright, backed by PHPUnit unit and feature tests.
- **Design to code.** 200+ mockups (Photoshop, XD, Figma, Envato themes) turned into pixel-perfect, accessible, responsive front-ends.
- **Content & editing platforms.** Deep experience with CMS, rich-text editors and HTML-to-Markdown workflows.
- **Pragmatic AI.** RAG pipelines, chatbots, AI vision and webhook-driven automation shipped into real products.
- **Remote-native.** 12+ years delivering autonomously for Swiss and European clients with clear async communication.

---

## Featured Projects

### Lemur / SiteCopilot | Multi-tenant Laravel CMS & Website Builder

> A visual, drag-and-drop website builder for agencies and SaaS platforms needing white-label site creation.

- **Visual editing:** GrapesJS page builder with real-time responsive preview across devices
- **Multi-tenant architecture:** Isolated tenant databases and asset separation via `stancl/tenancy`
- **Content workflow:** Draft / publish states, content versioning and point-in-time restoration
- **API-first:** Versioned RESTful APIs with token-based and session auth, reused across multiple front-end surfaces
- **Real-time:** WebSocket-driven features via Laravel Reverb / Broadcasting
- **Internationalization:** Multi-language page management (i18n)
- **Performance:** Redis/Memcached caching, CDN-integrated asset delivery, image optimization pipeline

`Laravel` `Livewire` `GrapesJS` `MySQL` `Redis` `WebSockets` `stancl/tenancy`

---

### Groupe-E Energy Kiosk Experience | Interactive Multi-Touch SPA

> An embedded, webview-style single-page experience deployed on energy-kiosk hardware across Switzerland, including an interactive ping-pong game.

- **Touch-first:** Multi-touch event handling and gesture-optimized UI
- **Embedded / webview:** Runs inside kiosk hardware as a wrapped web experience
- **Performance-tuned:** Lazy-loaded assets, optimized rendering for kiosk-grade hardware
- **Responsive design:** Adapts to varying kiosk screen sizes and orientations

`PHP` `JavaScript (vanilla)` `jQuery` `HTML5/CSS3` `Touch APIs`

---

### AI-Powered Content & Knowledge Platform | RAG, Chatbots & Automation

> A suite of AI-driven features integrated into existing content platforms.

- **RAG pipelines:** Global and page-level knowledge retrieval using Retrieval-Augmented Generation
- **Conversational AI:** Typebot-powered chatbots with context-aware responses
- **AI vision:** Image description and analysis pipeline for automated content tagging
- **Automation:** n8n / Make webhook-driven workflows connecting external APIs and services

`Laravel` `Typebot` `OpenAI / Vision APIs` `n8n` `Vector DBs` `REST APIs`

---

### E-Commerce Platform Network | PrestaShop & WooCommerce Multi-Site

> Delivered and maintained multiple Swiss e-commerce storefronts with shared infrastructure and centralized tooling.

- **Sites:** bodybest.ch, lescheminsdubio.ch, shop.cbconseils.ch, la-fee-coquette.com
- **Performance:** PageSpeed-optimized themes, CDN delivery, image optimization, query tuning
- **Cross-device validation:** BrowserStack and Playwright cross-browser E2E coverage
- **CMS integrations:** Custom PrestaShop modules and WooCommerce extensions

`PrestaShop` `WooCommerce` `WordPress` `PHP` `MySQL` `Vite` `Tailwind CSS` `Playwright`

---

### Proprietary CMS (Floowedit) | Legacy PHP Modernization

> Long-term maintainer and modernizer of a proprietary PHP content management system used by enterprise clients.

- **Legacy refactoring:** Incremental PHP 5 to 7+ migration with a zero-downtime strategy
- **Package ecosystem:** Published reusable Laravel packages (assets, forms, gallery, news and pricing manager, AI-powered chatbot engine, Smarty integration layer)
- **Testing:** PHPUnit unit/feature tests and Playwright end-to-end coverage
- **Code review:** Established review workflows and documentation standards

`PHP` `Laravel` `PHPUnit` `Playwright` `Git` `Composer`

---

## Technical Focus Areas

| Area | Tools & Practices |
|------|-------------------|
| **Performance & Web Vitals** | Google PageSpeed Insights, Vite (bundling / code-splitting), Redis & Memcached, CDN, lazy loading, MySQL query/index tuning, Tailwind purging |
| **Cross-Browser & Device Testing** | BrowserStack, CrossBrowserTesting, Playwright (cross-browser E2E), Modernizr, responsive multi-device preview |
| **Responsive Front-End** | jQuery, Alpine.js, Tailwind CSS, Bootstrap, UIkit, Sass/SCSS, design-to-code, accessible UI, i18n |
| **Content Platforms** | WordPress, WooCommerce, PrestaShop, CKEditor, TinyMCE, GrapesJS, HTML-to-Markdown |
| **AI / ML Integration** | RAG pipelines, chatbots (Typebot), AI vision, prompt engineering, n8n / Make automation |
| **Frameworks & APIs** | Laravel ecosystem (Livewire, Eloquent, Blade, Queues, Broadcasting, Reverb, Sanctum), RESTful API versioning, multi-tenant SaaS (stancl/tenancy) |
| **Testing & Observability** | PHPUnit, Playwright, unit / feature / E2E testing, mocking, static analysis, logging, instrumentation (GTM, Plausible) |
| **Databases & Architecture** | MySQL, SQL optimization, Redis, event-driven architecture, message queues, WebSockets, microservices |
| **Security** | CSRF, XSS, SQL injection prevention, rate limiting |
| **Tooling** | Git, GitHub, Bitbucket, Bash, Composer, Docker, Plesk, Postman |

---

## Open Source Contributions

- Published and maintain multiple **Laravel packages** (assets, forms, gallery, news and pricing manager, AI-powered chatbot engine, Smarty integration layer) available via Packagist / Composer.
- Active in GitHub issues and discussions for Laravel ecosystem projects.

---

## Experience Snapshot

| Period | Role | Context |
|--------|------|---------|
| 2013 - Present | PHP / Laravel / Frontend Developer | Iridescence Solutions (Remote), Swiss & European clients |
| 2012 | PHP Developer | Farming and Technology for Africa (On-site, Madagascar) |

---

## Education

- **Bachelor's degree (Licence) in Computer Science (DESPI)** | École Supérieure Privée BIG Behoririka, 2011
- **Higher Technician Diploma (DTS) in Computer Science** | École Supérieure Privée BIG Behoririka, 2010

---

## Languages

- **English:** fluent
- **French:** fluent
- **Malagasy:** native / fluent

---

## Contact

- **Email:** noum77@gmail.com
- **Phone:** +261 33 25 343 55
- **Location:** Madagascar (Remote)
- **GitHub:** [github.com/noum](https://github.com/noum)

> I am open to remote opportunities with distributed, internationally-focused teams.
