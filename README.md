<h1 align="center">Hi, I'm Andrii 👋</h1>

<p align="center">
  <b>Senior Full-Stack &amp; AI Engineer</b><br/>
  Python backends, LLM features and React interfaces for HealthTech, e-commerce and B2B SaaS.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/andrii-bielov-dev/"><img src="https://img.shields.io/badge/LinkedIn-Connect-4f46e5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:YOUR_EMAIL@example.com"><img src="https://img.shields.io/badge/Email-Write%20me-7c3aed?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Remote-EU%20%2F%20US-0ea5e9?style=for-the-badge" alt="Remote EU/US" />
</p>

---

### 🧭 About

6+ years building web, mobile and AI-powered products for European clients. I started with **React Native**, moved into full-stack **TypeScript**, and since 2023 I focus on **Python backends and LLM features**: RAG pipelines, vector search, LLM-based reporting, async processing and the React interfaces on top of them.

I like owning a feature from architecture and API design to production deployment, and talking to product managers directly while doing it.

> 🔎 **Currently looking for:** Senior Full-Stack or AI Engineer roles, remote EU/US.

---

### 🛠️ Toolbox

<table>
  <tr>
    <td width="130"><b>🤖 AI</b></td>
    <td>
      <img src="https://img.shields.io/badge/RAG-111827?style=flat-square" />
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
      <img src="https://img.shields.io/badge/LlamaIndex-8B5CF6?style=flat-square" />
      <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" />
      <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" />
      <img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white" />
      <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>⚙️ Backend</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
      <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" />
      <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>🎨 Frontend</b></td>
    <td>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>☁️ Cloud &amp; quality</b></td>
    <td>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
      <img src="https://img.shields.io/badge/PyTest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
      <img src="https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white" />
      <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
    </td>
  </tr>
</table>

---

### 🚀 Selected work

Most of this work was done for clients, so the code is private. Here's what I built and how.

<details open>
<summary><b>🏥 Lifeness</b> · HealthTech, Norway</summary>
<br/>

AI features for care teams, built on top of health data and clinical guidelines.

- RAG pipelines with **LlamaIndex** and **LangChain** over health data and clinical guidelines
- Vector search with **Pinecone** and **Qdrant**, query times kept under 150 ms
- AI summarization for care teams

`Python` `FastAPI` `RAG` `Qdrant` `Pinecone` `React`
</details>

<details open>
<summary><b>🏨 Runwell</b> · Hospitality SaaS, Norway</summary>
<br/>

LLM-powered reporting for operations teams.

- Python backend services with async processing (**Celery**, **RabbitMQ**)
- Reporting and summarization with **OpenAI** and **Claude** APIs, saving operations teams 15+ hours a week
- API latency kept under 200 ms with **Redis** caching

`Python` `Django` `Celery` `RabbitMQ` `Redis` `OpenAI` `Claude`
</details>

<details>
<summary><b>📦 FairyLoot</b> · Subscription e-commerce, UK</summary>
<br/>

Storefront, backend and billing for a platform with sharp traffic spikes during limited-edition drops.

- SSR/SSG storefront in **Next.js**, handling 50,000+ daily active users during product drops
- Core Web Vitals work: PageSpeed score up by 25+ points, LCP under 1.8 s
- **Stripe** and **PayPal** recurring billing with webhook-driven subscription lifecycle
- Query refactoring and index tuning on **PostgreSQL** (Prisma), about 30% lower query latency

`Next.js` `TypeScript` `NestJS` `Prisma` `Stripe` `PayPal`
</details>

<details>
<summary><b>🤝 Pomagator</b> · Community help &amp; volunteering app</summary>
<br/>

My first production mobile project, built in an Agile/Scrum team.

- Reusable **React Native** components following the design system
- Offline-first data handling with local persistence and sync on reconnection
- Firebase push notifications, deep linking and analytics
- Releases on Google Play and the App Store

`React Native` `Firebase` `Node.js` `Express`
</details>

---

### 🧩 How I usually build RAG features

```mermaid
flowchart LR
    A[Source data<br/>docs, guidelines] --> B[Chunking &<br/>embeddings]
    B --> C[(Vector DB<br/>Pinecone / Qdrant)]
    D[User question<br/>React UI] --> E[FastAPI]
    E --> C
    C --> F[Top-k context]
    F --> G[LLM<br/>OpenAI / Claude]
    G --> E
    E --> D
```

---

### 📍 Career path

| Period | Role | Company | Focus |
|:--|:--|:--|:--|
| 2023 – 2026 | Senior Full-Stack Developer | **EL Passion** (now Monterail) | Python backends, RAG, LLM reporting, React |
| 2021 – 2023 | Middle Full-Stack Developer | **Syde GmbH** | Next.js storefronts, billing, performance |
| 2020 – 2021 | Junior Full-Stack Developer | **Dev and Deliver** | React Native, Node.js |

---

### 📫 Let's talk

If you're hiring for a Senior Full-Stack or AI Engineer role, or have an LLM feature that needs to get to production, I'd be glad to hear about it.

<p align="center">
  <a href="https://www.linkedin.com/in/andrii-bielov-dev/">LinkedIn</a> ·
  <a href="mailto:YOUR_EMAIL@example.com">Email</a>
</p>
