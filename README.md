<img src="banner.png" alt="Elvis R. Pino — Senior Full-Stack Engineer, Applied AI" width="100%">

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-my--porfolio--next-E8A33D?style=flat-square&labelColor=0E1116)](https://my-porfolio-next-v1.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-elvis--pino-E8A33D?style=flat-square&labelColor=0E1116)](https://www.linkedin.com/in/elvis-pino-b358b2127/)
[![Email](https://img.shields.io/badge/Email-elvisreyxd%40gmail.com-E8A33D?style=flat-square&labelColor=0E1116)](mailto:elvisreyxd@gmail.com)

</div>

## About

Full-stack engineer with **10 years of experience**, founder of [Nesty C.A.](https://www.linkedin.com/in/elvis-pino-b358b2127/) — a technical consultancy focused on automation, web/mobile development and API integration.

I build systems where **AI is a production component, not a demo**: LLM integration over REST APIs, prompts with empirically validated constraints, and statistical predictive models with out-of-sample validation.

My design principle: **the model explains, deterministic code decides.**

```
Focus       Applied AI · Full-stack architecture · Process automation
Currently   Building an algorithmic trading platform and a sports
            prediction system, both with LLM and predictive layers
Location    Orlando, Florida · Open to relocation & remote
```

## Stack

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend**
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)

**Data**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

**AI & Automation**
![Gemini API](https://img.shields.io/badge/Google_Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![UiPath](https://img.shields.io/badge/UiPath_RPA-FA4616?style=flat-square&logo=uipath&logoColor=white)

**Cloud & Tooling**
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0072C6?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=flat-square&logo=docker&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=flat-square&logo=firebase&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)

## Selected work

### Algorithmic Trading Platform — Applied AI

Independently built and operated research and execution system. My most complete work in applied AI, data engineering and real-time systems. *(Private repository — happy to walk through the architecture.)*

| | |
|---|---|
| **~283k** | lines of TypeScript across 380 files |
| **5** | independent signal engines, ~46 symbols in parallel |
| **+1.29%** | model edge, validated out-of-sample |
| **59.4%** | directional accuracy against a 50.1% base rate |

- **Production LLM integration** — custom Google Gemini client over REST with timeout control, temperature tuning and token budgeting. Five specialized prompts across three services, designed with **graceful degradation**: when the model fails, the product keeps operating without the AI layer.
- **Data-driven prompt engineering** — wrote backtest scripts measuring whether *each criterion sent in the prompt* carries real predictive information, then removed the ones that did not. After measuring ~25 technical signals, established the core architecture: the LLM does not predict, it explains numbers already computed in code.
- **Custom predictive model** — weighted voting ensemble over 5 features with a net consensus threshold and a 72-hour horizon. Validated with permutation testing, Bonferroni correction and out-of-sample splits.
- **Quantitative rigor** — reverted my own best-performing signal (+1.76% edge) after auditing it against a 9,478-sample bull regime where it produced negative edge.
- **AI observability** — the system persists every model reading and verifies its accuracy against real price data every 10 minutes.

`Next.js 15` `React 19` `TypeScript` `PostgreSQL (Neon)` `Redis (Upstash)` `Railway` `Google Gemini API` `Telegram Bot API`

---

### GO190 Store — Mobile commerce, published on the App Store

<a href="https://apps.apple.com/kz/app/go190-store/id6748661767"><img src="foto-app-ios.png" width="260" align="right" alt="GO190 Store"></a>

Full-stack mobile commerce application built with React Native and Expo, backed by a NestJS API and a Next.js admin dashboard. Shipped to the Apple App Store.

- Native iOS application, live on the App Store
- Google Sign-In authentication via Firebase
- Real-time data synchronization with Supabase
- Product browsing, cart and order flow
- Admin dashboard for inventory and orders

`React Native` `Expo` `NestJS` `TypeScript` `Firebase` `Supabase`

**[→ View on the App Store](https://apps.apple.com/kz/app/go190-store/id6748661767)**

<br clear="right">

---

### Mi Tienda Online — E-commerce platform

<div align="center">
  <img src="sneakers-test-05-15-2025_03_37_PM.png" width="31%" alt="Storefront">
  <img src="Mi-Tienda-Online-Ecommerce-moderno-con-Next-js-05-15-2025_03_39_PM.png" width="31%" alt="Product catalog">
  <img src="Mi-Tienda-Online-Ecommerce-moderno-con-Next-js-05-15-2025_03_41_PM.png" width="31%" alt="Admin dashboard">
</div>

Complete e-commerce platform with product catalog and filtering, persistent cart, checkout, order tracking and an admin panel. Image optimization through Vercel Blob, responsive and SEO-oriented.

`Next.js 15` `TypeScript` `Tailwind CSS` `Supabase` `Vercel Blob`

**[→ Live demo](https://my-ecommerce-app-delta.vercel.app/)**

---

### FinancePro — Personal finance management

<img src="financepro-protected-page.png" width="420" align="right" alt="FinancePro">

Financial management platform for tracking income, expenses and investments, with interactive charts and reporting. Categorized transactions, real-time insights and secure authentication.

`Next.js` `React` `PostgreSQL` `Tailwind CSS` `Vercel`

**[→ Live demo](https://financepro-iota.vercel.app/)**

<br clear="right">

---

### Calot — Real estate platform

<img src="www.calot.com.ar_.png" width="420" align="right" alt="Calot">

Property rental and sales portal with listing management, advanced search filters and an admin dashboard. In production since 2019.

`PHP (Laravel)` `MySQL` `Bootstrap` `CSS`

**[→ Visit calot.com.ar](https://www.calot.com.ar)**

<br clear="right">

---

### Smaller projects

| Project | Description | Stack | Links |
|---|---|---|---|
| **Personal Portfolio** | Responsive portfolio with i18n, dark mode and project showcase | `Next.js` `TypeScript` `Tailwind` | [demo](https://my-porfolio-next-v1.vercel.app/) · [code](https://github.com/elvisxd/my-porfolio-next) |
| **NestJS REST API** | Scalable API with CRUD, auth, validation and Swagger docs | `NestJS` `PostgreSQL` `Railway` | [demo](https://restapi-production-ac90.up.railway.app/) |
| **Chat UI** | Chat interface with rooms, authentication and theming | `Next.js` `React` `Tailwind` | [demo](https://gemini-chat-app-three.vercel.app/) |
| **QR Generator** | Custom QR code generator built from scratch | `HTML` `CSS` `JavaScript` | [demo](https://qr-generator-pp31.vercel.app/) · [code](https://github.com/elvisxd/qr-generator) |
| **Weather App** | Real-time weather with dynamic condition-based backgrounds | `React` `Tailwind` `Weather API` | [demo](https://elvisxd.github.io/weather-app/) · [code](https://github.com/elvisxd/weather-app) |

## Certifications

`Vibe Coding: Responsible AI-Assisted Development` — DevTalles, 2026
`.NET Backend: .NET Core, SQL Server & JWT` — DevTalles, 2025
`NestJS: Backend with PostgreSQL & WebSockets` — DevTalles, 2025
`React Native Expo: iOS & Android Apps` — DevTalles, 2025
`Meta Advanced React` · `React Basics` · `Back-End Development` — Coursera, 2022
`UiPath RPA Developer` · `JS Algorithms & Data Structures` — freeCodeCamp

**B.Sc. Systems Engineering** — Universidad de Margarita (Unimar), Venezuela

## GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=elvisxd&show_icons=true&hide_border=true&bg_color=0E1116&title_color=E8A33D&icon_color=E8A33D&text_color=B3BBC8" alt="GitHub stats" width="48%">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=elvisxd&layout=compact&hide_border=true&bg_color=0E1116&title_color=E8A33D&text_color=B3BBC8" alt="Top languages" width="48%">
</div>

---

<div align="center">

**Open to senior full-stack and applied AI roles** — Orlando, FL, relocation or remote.

[elvisreyxd@gmail.com](mailto:elvisreyxd@gmail.com) · [LinkedIn](https://www.linkedin.com/in/elvis-pino-b358b2127/) · [Portfolio](https://my-porfolio-next-v1.vercel.app/)

</div>
