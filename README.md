<h1 align="center">Matheus Kirsch</h1>

<p align="center">
  Full-stack developer building commerce products with TypeScript, React, Next.js and Node.js.<br />
  Founder-engineer at <a href="https://github.com/Truth-Commerce">Truth Commerce</a> — e-commerce intelligence, automation and storefronts for Brazilian sellers.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-0f172a?style=for-the-badge&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-0f172a?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-0f172a?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Node.js-0f172a?style=for-the-badge&logo=nodedotjs&logoColor=5FA04E" alt="Node.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-0f172a?style=for-the-badge&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Tailwind-0f172a?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8" alt="Tailwind CSS" />
</p>

---

## About

I am a full-stack developer from Porto Alegre, Brazil. I build the products behind Truth Commerce: SaaS tools that turn marketplace data into decisions, AI pipelines that produce ready-to-publish product listings, and storefronts that real clients operate every day.

My work covers the whole loop — product thinking, architecture, implementation, testing and production operation — with a strong bias for typed contracts, automated tests and systems that survive real clients and real deadlines.

## Flagship Projects

### [Truth Analytics](https://github.com/Truth-Commerce/truth-analytics) — AI marketplace intelligence SaaS

Multi-tenant SaaS that unifies a seller's sales across Mercado Livre, Shopee, Amazon and their own store (via Bling API v3), benchmarks the market and generates AI-written reports with metrics, a proprietary Truth Score and action plans — the engine behind Truth Commerce's consulting operation.

- Yearly performance dashboards, Mercado Livre Ads module and annual goal tracking
- AI analysis pipeline (Claude with structured outputs) with anti-hallucination safeguards
- Multi-tenant by design: every query is org-scoped, with static guards enforced by tests
- **Stack:** Next.js (App Router), TypeScript strict, Drizzle + PostgreSQL (Neon), Auth.js v5, Recharts, react-pdf, Vitest + Playwright

### AUTOMATRUTH — AI listing factory <sub>(Truth Commerce internal product)</sub>

Platform that takes a raw product spreadsheet and turns it into publish-ready marketplace listings: matches each product on Mercado Livre, writes the copy with AI, generates four product images per item and exports the finished listing straight into the client's ERP (Bling or Olist/Tiny).

- Image pipeline combining OpenAI image models with a deterministic text compositor (Satori + resvg + sharp) for accent-perfect Portuguese cards
- Multi-team background worker with fair per-owner queueing and rate limiting
- Client account system with usage ledgers, margins report and role-based UI
- 1,000+ tests; in production, used daily by the Truth Commerce team and clients
- **Stack:** Next.js (App Router), React, TypeScript, Prisma + PostgreSQL (Supabase), Vitest
- **Ecosystem I also built:** an autonomous CLI pilot that runs the text queue end-to-end (generate → validate → approve, 111 tests) and a batch image-generation CLI for product photo sets

## More Truth Commerce Work

- **truth-2fa** — two-factor authentication service for the Truth Commerce operation, live in production (TypeScript, private)
- **Storefronts and themes** — premium reskins and custom themes for client stores on Nuvemshop, Shopify and Tray, delivered end-to-end (design system, CSS/JS, QA on live previews)

## Open Repositories

| Project | What it is | Stack |
| --- | --- | --- |
| [truthcommerce](https://github.com/Kirschmf/truthcommerce) · [Live](https://truthcommerce.vercel.app) | Institutional website for Truth Commerce with motion design, 3D sections and tests | React, Vite, Tailwind CSS, Three.js, GSAP, Vitest, Playwright |
| [kirschbrain](https://github.com/Kirschmf/kirschbrain) | Web reader for a markdown knowledge vault that reports the freshness and debt of each document | Node.js, JavaScript |
| [nuvemshop-skins](https://github.com/Kirschmf/nuvemshop-skins) | Reusable CSS/JS skins for Nuvemshop storefronts | JavaScript, CSS |
| [Property-Pulse](https://github.com/Kirschmf/Property-Pulse---Project) | Real estate platform with authentication and database modeling | Next.js, MongoDB, NextAuth, Tailwind CSS |
| [RID180910_Desafio05](https://github.com/Kirschmf/RID180910_Desafio05-) · [Live](https://v0-desafio05-frontmain.vercel.app) | Full-stack challenge with form handling, validation and API-oriented UI | Next.js, TypeScript, Radix UI, Zod |

## Core Stack

| Area | Tools |
| --- | --- |
| Frontend | React, Next.js, Vite, TypeScript, Tailwind CSS, Radix UI |
| Backend and Data | Node.js, PostgreSQL (Neon, Supabase), Drizzle, Prisma, Auth.js, REST APIs (Bling, Mercado Livre, Olist) |
| AI | Claude SDK (structured outputs), OpenAI image models, AI-assisted engineering workflows |
| Quality | Vitest, Playwright, Testing Library, TypeScript strict, TDD |
| Delivery | Vercel, GitHub Actions, Docker (EasyPanel), production operation and monitoring |

## Engineering Principles

- Ship products, not demos: every project above runs in production for real users.
- Keep architecture simple until complexity earns its place.
- Typed contracts at every boundary; tests before merge, evidence before "done".
- AI is a tool in the pipeline, with safeguards — never an excuse for wrong numbers.

## GitHub Snapshot

<p align="center">
  <img height="165" src="https://kirschmf-readme-stats.vercel.app/api?username=Kirschmf&show_icons=true&theme=transparent&hide_border=true&rank_icon=github&include_all_commits=true" alt="Matheus Kirsch GitHub stats" />
  <img height="165" src="https://kirschmf-readme-stats.vercel.app/api/top-langs/?username=Kirschmf&layout=compact&theme=transparent&hide_border=true&langs_count=8" alt="Most used languages" />
</p>

---

<p align="center">
  Porto Alegre, Brazil · <a href="mailto:makfonseca@gmail.com">makfonseca@gmail.com</a>
</p>
