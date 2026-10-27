<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=2F81F7&center=true&vCenter=true&width=700&lines=Hi%2C+I%27m+Gahan+Pradhan+%F0%9F%91%8B;Agentic+AI+Engineer+%40+Azentio;I+build+LLM+agents+that+do+real+engineering+work;RAG+%C2%B7+LangGraph+%C2%B7+Google+ADK+%C2%B7+FastAPI" alt="Agentic AI Engineer at Azentio, building LLM agents that do real engineering work" />

**I build agentic AI systems that turn scattered product knowledge into shipped engineering work —<br/>test suites, QA runs, load tests and reports that used to take days.**

<a href="https://www.linkedin.com/in/gahan-pradhan-7b9788252/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:gahan.pradhan@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://leetcode.com/u/Gahan_Pradhan_06/"><img src="https://img.shields.io/badge/LeetCode_1632-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode rating 1632" /></a>
<a href="https://www.instagram.com/gahanpradhan/"><img src="https://img.shields.io/badge/Instagram-FF0069?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>

</div>

---

## ⚡ Right now

- 🏢 **Agentic AI Engineer at [Azentio](https://www.azentio.com/)** (Aug 2026 →), after a 15-month internship on the same team — building LLM agents for test generation, QA and performance engineering.
- 🎓 **B.E. Computer Science, NIE Mysuru** — graduated 2026 with a **9.30 CGPA**.
- 🧪 **Thinking about:** agent evaluation, grounding and guardrails — making agents that refuse to make things up.
- 🤝 **Open to:** collaborating on agentic AI, RAG and evaluation tooling.

---

## 📊 Impact at work

| What I built | Outcome |
|---|---|
| **LLM test-generation pipeline** — unifies Jira, Confluence, Figma, product docs and code into a product knowledge graph, then uses RAG to write requirement-traceable test cases | ⏱️ Test design: **20 days → 2 days** |
| **Sales-sizing app** — turns client transaction volumes and user counts into infrastructure recommendations and PDF reports | ⏱️ Turnaround: **2–3 days → under 1 hour** |
| **LangGraph performance-testing agent** — orchestrates JMeter/k6 workloads with adaptive load scaling | 🎯 Finds SLA breakpoints, analyses app/DB performance, files Jira defects for regressions |
| **Multi-application QA agents** — pick and run the right automated test suites to validate bug fixes, using app knowledge, mapped tests and preflight checks | ✅ Bug-fix validation without hand-picking suites |
| **Cross-editor AI-usage analytics** for Claude Code, GitHub Copilot and Cursor — groups chats by task | 📈 Usage, cost, time and artifact metrics exported to Excel |
| **MERN expense-reimbursement platform** at Prixgen Tech Solutions (Jan–Apr 2025) | ⚙️ Automated **~90%** of internal expense workflows |

<details>
<summary><b>🔍 How the test-generation pipeline fits together</b></summary>
<br/>

```mermaid
flowchart LR
    J[Jira] --> P
    C[Confluence] --> P
    F[Figma] --> P
    D[Product docs] --> P
    R[Codebase] --> P
    P["Docling + spaCy<br/>parse and extract"] --> KG[("Product<br/>knowledge graph")]
    P --> E["bge-m3<br/>embeddings"] --> Q[("Qdrant")]
    KG --> L["LLM + RAG"]
    Q --> L
    L --> T["Requirement-traceable<br/>test cases"]
```

</details>

---

## 🚀 Featured projects

### 🌍 [SafeGround](https://github.com/gahanpradhan?tab=repositories&q=SafeGround) — AI hazard readiness & response planning

A geospatial disaster-readiness platform: give it any location and it profiles hazards, assesses local exposure and prioritises what to prepare. It pulls from **Google Earth Engine, USGS, GDACS and OpenStreetMap**, runs **Google ADK multi-agent workflows** for analysis, research and safety planning, and checks every plan against deterministic hazard zones, routes and official rulebooks — rejecting unsafe advice and unsupported facts.

> **Evaluated on 20 safety-plan cases**
> | Check | SafeGround | Gemini alone |
> |---|:---:|:---:|
> | Danger-level accuracy | **100%** | 30% |
> | Primary-action accuracy | **100%** | 70% |
> | Plans with invented distances/times | **0** | 3 |

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google_ADK-4285F4?style=flat-square&logo=google&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Earth Engine](https://img.shields.io/badge/Earth_Engine-34A853?style=flat-square&logo=google&logoColor=white)
![MapLibre](https://img.shields.io/badge/MapLibre-396CB2?style=flat-square&logo=maplibre&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloud Run](https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

### 💬 [Promptly](https://github.com/gahanpradhan?tab=repositories&q=Promptly) — community hub for reusable AI prompts

A place to publish, discover and share AI prompts, with **Elasticsearch full-text search** so good prompts are easy to find and reuse. Built for safe community sharing: **two-factor authentication, role-based access control and multi-level content moderation**.

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/Express-0A0A0A?style=flat-square&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)

<details>
<summary><b>📁 Earlier projects</b></summary>
<br/>

- **Nomadify** — AI trip planner that generates personalised itineraries from interests and budget, with Google Maps and weather forecasts. *React · Firebase · Gemini · Tailwind · shadcn/ui*
- **JobDash** — job-application tracker with reminders and a visual pipeline. *JavaScript · Flask · PostgreSQL · Docker · Jenkins · Tailwind*

</details>

---

## 🧰 Tech stack

| Area | Tools |
|---|---|
| **Languages** | <img src="https://skillicons.dev/icons?i=py,ts,js,cpp,bash" alt="Python, TypeScript, JavaScript, C++, Bash" /> &nbsp;+ SQL |
| **Agentic AI** | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![Google ADK](https://img.shields.io/badge/Google_ADK-4285F4?style=flat-square&logo=google&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini_(Vertex_AI)-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white) ![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)<br/>RAG · multi-agent orchestration · structured outputs · multimodal extraction |
| **Backend & web** | <img src="https://skillicons.dev/icons?i=fastapi,flask,nodejs,express,react,tailwind" alt="FastAPI, Flask, Node.js, Express, React, Tailwind" /> &nbsp;+ SQLAlchemy, REST, async |
| **Data & search** | <img src="https://skillicons.dev/icons?i=postgres,mongodb,elasticsearch" alt="PostgreSQL, MongoDB, Elasticsearch" /> &nbsp;+ Qdrant, Oracle |
| **Infra & CI** | <img src="https://skillicons.dev/icons?i=docker,jenkins,githubactions,linux,gcp,aws" alt="Docker, Jenkins, GitHub Actions, Linux, Google Cloud, AWS" /> |
| **Testing** | ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square) ![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white) ![JMeter](https://img.shields.io/badge/JMeter-D22128?style=flat-square&logo=apachejmeter&logoColor=white) |

---

## 🏆 Achievements

- 🌏 **Google AI Builder Cup 2026** — shortlisted participant in the JAPAC-region AI hackathon
- 🛒 **Flipkart GRiD 7.0** — National Semifinalist, **top 2%** of 160,000+ participants
- 🥈 **CODEMAZE Hackathon, IEEE NIE Mysuru** — 2nd place among 25+ teams
- 🧠 **LeetCode 1632** · **CodeChef 1416 (2★)**
- 🧑‍🏫 Trained **50+ students** at CHIGURU 2024 with Youth For Seva

---

## 📈 Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api?username=gahanpradhan&show_icons=true&include_all_commits=true&hide_border=true&theme=tokyonight" />
  <img src="https://github-stats-extended.vercel.app/api?username=gahanpradhan&show_icons=true&include_all_commits=true&hide_border=true&theme=default" height="165" alt="GitHub stats" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=gahanpradhan&layout=compact&langs_count=6&hide_border=true&theme=tokyonight" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=gahanpradhan&layout=compact&langs_count=6&hide_border=true&theme=default" height="165" alt="Top languages" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=gahanpradhan&hide_border=true&theme=tokyonight" />
  <img src="https://streak-stats.demolab.com?user=gahanpradhan&hide_border=true&theme=default" alt="GitHub contribution streak" />
</picture>

<img src="https://leetcard.jacoblin.cool/gahan_pradhan_06?theme=light,dark&font=Fira+Code&ext=contest" alt="LeetCode stats and contest rating" />

</div>

---

<p align="center"><i>Building agents that earn their trust. Let's talk ⚡</i></p>
