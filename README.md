<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0f0f,50:1a1a2e,100:16213e&height=200&section=header&text=RAJSHEKHAR%20ROY&fontSize=52&fontColor=e2e8f0&fontAlignY=38&desc=Full%20Stack%20Engineer%20%E2%80%A2%20Backend%20Systems%20%E2%80%A2%20AI&descAlignY=60&descSize=16&descColor=94a3b8&animation=fadeIn" width="100%" />

</div>

<div align="center">

![Typing SVG](<https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=4000&pause=1000&color=38BDF8&center=true&vCenter=true&repeat=true&width=800&height=50&lines=Full%20Stack%20Engineer%20(Backend%20%26%20AI%20Infrastructure).;Building%20scalable%20backends%20and%20AI-powered%20platforms.;Focusing%20on%20robust%20architecture%20and%20real-world%20engineering.>)

</div>

---

<br/>

<table width="100%">
<tr>
<td width="100%" valign="top">

## `> whoami`

```typescript
const me: Engineer = {
  role: "Full Stack Engineer",
  focus: [
    "Backend Architecture",
    "AI Infrastructure",
    "Distributed Systems",
    "RAG Pipelines",
  ],
  background: "B.Sc Mathematics (Hons) → Systems Architecture",
  currently: "Building a multi-tenant RAG backend platform",
  philosophy: "Understand deeply. Build deliberately. Scale cleanly.",
};
```

<br/>

I design data-intensive, highly scalable backend systems. My work spans production ETL pipelines, multi-tenant SaaS platforms, AI-powered backends, and infrastructure automation. I care deeply about architecture, system constraints, and understanding how things work beneath the surface.

Currently focused on **RAG system design** — ingestion pipelines, chunking strategies, embedding trade-offs, vector retrieval, and LLM orchestration. Building it API-first, multi-tenant, and BYOK-ready.

</td>
</tr>
</table>

---

## `> tech --stack --production`

<br/>

**[ FRONTEND & FRAMEWORKS ]**

![React / Next.js (App Router)](https://img.shields.io/badge/-React%20%2F%20Next.js%20%28App%20Router%29-24283b?style=flat&logo=nextdotjs&logoColor=e2e8f0&labelColor=1a1b26) ![TypeScript / JavaScript](https://img.shields.io/badge/-TypeScript%20%2F%20JavaScript-24283b?style=flat&labelColor=1a1b26) ![HTML / CSS / Tailwind](https://img.shields.io/badge/-HTML%20%2F%20CSS%20%2F%20Tailwind-24283b?style=flat&logo=tailwindcss&logoColor=38bdf8&labelColor=1a1b26) 

**[ BACKEND & APIS ]**

![Node.js / Express.js](https://img.shields.io/badge/-Node.js%20%2F%20Express.js-24283b?style=flat&logo=nodedotjs&logoColor=4ade80&labelColor=1a1b26) ![REST API Design](https://img.shields.io/badge/-REST%20API%20Design-24283b?style=flat&logo=postman&logoColor=a78bfa&labelColor=1a1b26) ![Middleware Architecture](https://img.shields.io/badge/⚙️-Middleware%20Architecture-24283b?style=flat&labelColor=1a1b26) ![Auth Systems (JWT, Better Auth)](https://img.shields.io/badge/-Auth%20Systems%20%28JWT%2C%20Better%20Auth%29-24283b?style=flat&logo=jsonwebtokens&logoColor=f59e0b&labelColor=1a1b26) 

**[ DATABASES & DATA ]**

![PostgreSQL (Prisma](https://img.shields.io/badge/-PostgreSQL%20%28Prisma-24283b?style=flat&labelColor=1a1b26) ![Drizzle)](https://img.shields.io/badge/-Drizzle%29-24283b?style=flat&labelColor=1a1b26) ![MongoDB (Mongoose)](https://img.shields.io/badge/-MongoDB%20%28Mongoose%29-24283b?style=flat&logo=mongodb&logoColor=4ade80&labelColor=1a1b26) ![ClickHouse](https://img.shields.io/badge/-ClickHouse-24283b?style=flat&logo=clickhouse&logoColor=f59e0b&labelColor=1a1b26) ![MySQL](https://img.shields.io/badge/-MySQL-24283b?style=flat&logo=mysql&logoColor=f59e0b&labelColor=1a1b26) ![Redis](https://img.shields.io/badge/-Redis-24283b?style=flat&logo=redis&logoColor=ef4444&labelColor=1a1b26) ![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-24283b?style=flat&logo=rabbitmq&logoColor=f59e0b&labelColor=1a1b26) 

**[ INFRASTRUCTURE ]**

![Docker / Nginx](https://img.shields.io/badge/-Docker%20%2F%20Nginx-24283b?style=flat&logo=docker&logoColor=38bdf8&labelColor=1a1b26) ![AWS (EC2, S3, Lambda)](https://img.shields.io/badge/☁️-AWS%20%28EC2%2C%20S3%2C%20Lambda%29-24283b?style=flat&labelColor=1a1b26) ![Terraform](https://img.shields.io/badge/-Terraform-24283b?style=flat&logo=terraform&logoColor=a78bfa&labelColor=1a1b26) ![Vercel / Netlify](https://img.shields.io/badge/-Vercel%20%2F%20Netlify-24283b?style=flat&logo=vercel&logoColor=e2e8f0&labelColor=1a1b26) 

---

## `> projects --notable`

<br/>

<table width="100%">

<tr>
<td width="50%" valign="top">

### Portlify

**SAAS PLATFORM**

A production-ready multi-tenant SaaS platform for portfolio building and personal branding with AI-powered features, dual payment gateways, and built-in analytics.

`Next.js 16` `React 19` `PostgreSQL` `Prisma` `Better Auth` `Vercel AI SDK`

</td>

<td width="50%" valign="top">

### AI Backend Platform

**AI PLATFORM**

Modular AI-powered backend service with RAG capabilities — data ingestion, embeddings, vector storage, and retrieval-based queries with multi-tenant isolation.

`Node.js` `Vector DB` `OpenAI` `Gemini` `PostgreSQL`

</td>
</tr>

</table>

---

## `> architecture --reference-blueprint`

<br/>

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                                                                             │
│   Proxy & Edge Layer              →   Nginx, SSL routing, custom domains    │
│          ↓                                                                  │
│   Auth & API Gateway              →   Identity, rate limiting, RBAC guards  │
│          ↓                                                                  │
│   Application & Core Services     →   Feature logic, request orchestration  │
│          ↓                                                                  │
│   Async & Worker Layer            →   AWS Lambda, S3 triggers, Playwright   │
│          ↓                                                                  │
│   Database & Caching Layer        →   PostgreSQL (Tx) + DynamoDB (NoSQL)    │
│          ↓                                                                  │
│   Data Pipeline & Analytics       →   Airflow + SQL Server → ClickHouse     │
│          ↓                                                                  │
│   AI & Vector Infrastructure      →   FastAPI + RAG · Document Chunking     │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## `> stats --activity`

<br/>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rajshekharroy/rajshekharroy/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/rajshekharroy/rajshekharroy/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/rajshekharroy/rajshekharroy/output/github-contribution-grid-snake-dark.svg" width="100%" />
</picture>

</div>

<br/>

<div align="center">

<img src="https://github-readme-stats.shion.dev/api/top-langs/?username=rajshekharroy&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=94a3b8&langs_count=8" />

</div>

---

## `> philosophy.log`

<br/>

<div align="center">

> _"Understand deeply. Build deliberately. Scale cleanly."_

</div>

<br/>

My engineering approach is rooted in my Mathematics background: I prefer to analyze systems from first principles. While modern tooling accelerates execution, I focus heavily on the underlying architecture—navigating backend trade-offs, optimizing complex data flows, and building infrastructure that is both resilient and adaptable.

---

## `> connect --open-to`

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/💼-LinkedIn-24283b?style=flat&labelColor=1a1b26)](https://linkedin.com/in/rajshekhar-roy)
[![Mail](https://img.shields.io/badge/-Email-24283b?style=flat&logo=gmail&logoColor=ef4444&labelColor=1a1b26)](mailto:hello@rajshekharroy.com)
[![GitHub](https://img.shields.io/badge/-GitHub-24283b?style=flat&logo=github&logoColor=e2e8f0&labelColor=1a1b26)](https://github.com/rajshekharroy)
[![Portfolio](https://img.shields.io/badge/-Portfolio-24283b?style=flat&logo=vercel&logoColor=4ade80&labelColor=1a1b26)](https://www.rajshekharroy.com)

<br/>

**Open to:** Backend & Full Stack Engineering roles · AI / Data Infrastructure · Systems Architecture

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0f0f0f&height=120&section=footer&text=&animation=fadeIn" width="100%" />

<sub>
  Built with deliberate intention — like every system should be. · Kolkata, India
</sub>

</div>
