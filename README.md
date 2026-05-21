<h1 align="center">Sebastián Torregroza</h1>

<p align="center">
  <b>Full-Stack Developer</b> · Barranquilla, Colombia 🇨🇴
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sebastián-torregroza-b16579299/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:sebastorregroza6@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## About Me

I build backend systems and APIs. My focus is on architecture decisions that hold up under real load — not clever code that falls apart when requirements change.

Most of what I know came from working with actual users. I spent time in **Beca Talento** doing direct support for university applicants, which meant watching where people got stuck in broken processes. That's what led me to start building tools to fix those gaps rather than just document them.

Right now I'm working on an AI service that routes requests across multiple LLM providers and a CRM built from scratch with my brother.

---

## Experience

**Full-Stack Developer — AI Service** *(Jan 2026 – Present)*

The problem was simple: we needed to use multiple LLM providers without rewriting integrations every time one changed pricing or broke.

I built a unified API with **ElysiaJS + Vercel AI SDK** that exposes a single HTTP contract regardless of what's running underneath. On top of that, a strategy engine that picks between low-cost and low-latency models depending on what the request actually needs. When a provider goes down, it falls over to the next one automatically.

---

**Frontend Developer — Amelia** *(Feb – Jul 2025)*

During enrollment season at CUC, the support team got buried in the same questions over and over — scholarship requirements, program costs, enrollment steps. I built a chatbot prototype to handle the FAQ layer so the team could focus on cases that actually needed a person.

---

**Beca Talento — Universidad de la Costa** *(Feb 2025 – Present)*

Direct support work for students and applicants navigating administrative processes. The practical side: learning to figure out what someone actually needs, not just what they're asking for.

---

## Tech Stack

**Backend & Infrastructure**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,nodejs,postgres,sqlite,docker,python&perline=6" />
  </a>
</p>

<p align="left">
  <img src="https://img.shields.io/badge/ElysiaJS-000000?style=flat-square&logo=bun&logoColor=white" />
  <img src="https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logoColor=black" />
  <img src="https://img.shields.io/badge/Better_Auth-3B82F6?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel_AI_SDK-000000?style=flat-square&logo=vercel&logoColor=white" />
</p>

**Frontend & Tooling**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,astro,tailwind,git,github,vercel,vscode&perline=7" />
  </a>
</p>

---

## Projects

| Project | Description |
|---------|-------------|
| [AI Service](https://github.com/Sebas200702/ai-service) | Unified LLM API over ElysiaJS. Routes requests across providers with a cost/latency strategy engine and auto-fallback. |
| Kana CRM *(private)* | CRM built with my brother — I handle backend, auth (2FA, API keys, RBAC), and API design. Astro SSR + Drizzle + Better Auth. |
| Amelia *(prototype)* | FAQ chatbot for CUC built to reduce support load during enrollment. Built from watching the actual friction firsthand. |
| [AniDev v2](https://github.com/Sebas200702/anidev-v2) | Anime discovery platform. The interesting part was the scraping pipeline and keeping the data model sane at ~10k rows. |
| [notesku-backend](https://github.com/Sebas200702/notesku-backend) | REST API for notes with auth and PostgreSQL. Early project, still worth showing the structure. |

---

