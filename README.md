<!--
  Hardik Saini — GitHub profile README
  Visual direction: engineering monograph, editorial,
  warm paper / deep ink / oxblood-ember.
-->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/masthead-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/masthead-light.svg">
  <img alt="Hardik Saini — building AI, cloud, and product systems, end to end." src="assets/masthead-light.svg">
</picture>

</div>

&nbsp;

> **Building AI, cloud, and product systems — end to end.**
>
> I design and ship full systems: the API boundary, the data model, the auth story, the deploy pipeline, and the surface a real person actually uses. The work spans backend and platform, AI product workflows, and a polished user experience that holds up under inspection.

&nbsp;

---

## Featured Systems

### TaskTrail — role-aware task coordination for small teams

> A coordination system where managers create teams, generate join access, assign one-off or recurring work, and monitor execution; employees join, pick up assigned work, update progress, and complete tasks. Web and mobile share one API contract.

- **Stack** — Node.js, Express, Supabase Auth, Supabase Postgres, Zod, Docker, OCI VM, Caddy, Vercel, GitHub Actions, GHCR · Flutter, Dart, Dio, GoRouter, flutter_secure_storage
- **Signal** — cloud delivery, RBAC, backend architecture, shared API contract across web and mobile
- **Why it matters** — small teams need real coordination, not group chats; ownership and execution stay legible.
- **Links** — [web repo](https://github.com/blank-space-gsu/TaskTrail) · [mobile repo](https://github.com/Harry830/tasktrail-mobile) · [live](https://tasktrail.site) · [api health](https://api.tasktrail.site/api/v1/health)

### Stockd — AI for restaurant inventory operations

> An operator-facing product covering restaurant inventory workflows, forecasting, pricing, and operator dashboards, with an AI copilot, security monitoring, and a Supabase-backed product surface.

- **Stack** — vanilla JavaScript, HTML/CSS, Chart.js, Supabase, PostgreSQL functions / Supabase Edge Functions, OpenAI, Jest, GitHub Actions
- **Signal** — AI/product thinking, operational dashboards, Supabase-backed product surface, security monitoring
- **Why it matters** — inventory is where margin lives; the system puts forecasting, pricing, and visibility on one surface.
- **Links** — [repo](https://github.com/stockd-ai/Stockd) · [live](https://www.stockd.us)

### RoomieManager — household operations, properly modeled

> A household management platform covering groups, chores, finance, and contracts, with a Supabase auth boundary, RBAC, OpenAPI docs, structured logs, and tests.

- **Stack** — React 18, TypeScript, Vite, Tailwind, React Router · NestJS 10, Prisma 5, Supabase Postgres / Auth, jose / JWKS, Swagger / OpenAPI, Pino, Jest, e2e
- **Signal** — full-stack systems, domain modeling, auth boundary, verification pipeline
- **Why it matters** — shared-living rules are usually soft contracts; this makes them explicit, auditable, and fair.
- **Links** — [repo](https://github.com/GSU-BitByBit/RoomieManager) · [live](https://roomiemanager.site) · [api docs](https://api.roomiemanager.site/api/docs)

### SpeechMate — multimodal AI public speaking coach

> Speech outline generation, multimodal video and document analysis, detailed feedback, an improvement plan, curated YouTube recommendations, and ElevenLabs text-to-speech practice — fronted by Google OAuth.

- **Stack** — Java 21, Spring Boot 3.5.7, Spring Security OAuth2, Spring WebFlux / WebClient · React 19, TypeScript, Vite, React Router, Axios, Framer Motion · Gemini 2.5 Pro / 2.0 Flash, ElevenLabs
- **Signal** — multimodal AI, full-stack Java/React, OAuth, voice and audio workflow
- **Why it matters** — speaking well is high-leverage and hard to practice; the coach turns a vague skill into a tractable feedback loop.
- **Links** — [repo](https://github.com/TheGSUCoders/SpeechMate)

### Portfolio — the brand hub

> A personal portfolio and brand system: editorial, performant, written in a current React stack.

- **Stack** — Next.js 16, React 19, Tailwind CSS v4, Framer Motion 12, EmailJS / Nodemailer, Vercel Analytics
- **Signal** — frontend craft, product taste, personal brand system
- **Why it matters** — the front door to the rest of the work.
- **Links** — [repo](https://github.com/Harry830/portfolio) · [live](https://www.harry830.tech) · [about](https://www.harry830.tech/about)

---

## Field Kit

**Frontend** — React 18 / 19 · Next.js · TypeScript · Vite · Tailwind · Framer Motion · React Router · Chart.js

**Backend & API** — Node.js · Express · NestJS · Spring Boot · Spring WebFlux · Zod · OpenAPI / Swagger

**Data, Auth, Infra** — Supabase Postgres · Supabase Auth · Prisma · PostgreSQL functions / Supabase Edge Functions · jose / JWKS · Spring Security OAuth2 · Pino · Docker · OCI VM · Caddy · Vercel · GitHub Actions · GHCR

**AI & Product Intelligence** — OpenAI · Gemini 2.5 Pro / 2.0 Flash · ElevenLabs

**Mobile** — Flutter · Dart · Dio · GoRouter · flutter_secure_storage

**Delivery & Quality** — Jest · e2e · structured logging · GitHub Actions pipelines

---

## How I Build

- **Systems first.** Before writing code, I draw the boundary: who owns the data, where auth lives, what the API contract is, and how it deploys. The rest follows from that.
- **Product taste matters.** A correct system that feels clumsy is unfinished. I ship surfaces I would be willing to use myself.
- **Clean handoffs.** Documented APIs, structured logs, tests at the seams, and reproducible deploys — so the next person, including future me, is not guessing.

---

## Contact

- **Portfolio** — [harry830.tech](https://www.harry830.tech)
- **GitHub** — [@Harry830](https://github.com/Harry830)
