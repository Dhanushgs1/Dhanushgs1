<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6366F1,50:8B5CF6,100:06B6D4&height=200&section=header&text=Dhanush%20G&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20Agentic%20AI%20%C2%B7%20RAG%20%C2%B7%20MCP&descAlignY=56&descSize=18" alt="Dhanush G — AI Engineer" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&pause=1200&color=8B5CF6&center=true&vCenter=true&width=760&lines=Junior+AI+Engineer+%40+StratAI;Agentic+AI+%C2%B7+RAG+%C2%B7+MCP+%C2%B7+LLM+Automation;Building+AI+systems+that+turn+data+into+action." alt="Typing intro" />

<br/>

I build agentic AI, RAG and automation systems that run against **real marketplace data** —<br/>
not demos, not prototypes. Systems that end in an **action**, not a chart.

<br/>

<a href="https://www.linkedin.com/in/dhanush-gs/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:dhanushgovindhang@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://stratai.io"><img src="https://img.shields.io/badge/StratAI-6366F1?style=for-the-badge&logoColor=white" alt="StratAI" /></a>
<a href="https://github.com/Dhanushgs1?tab=followers"><img src="https://img.shields.io/github/followers/Dhanushgs1?style=for-the-badge&color=8B5CF6&labelColor=1F2937&logo=github&logoColor=white" alt="Followers" /></a>
<img src="https://komarev.com/ghpvc/?username=Dhanushgs1&label=Profile+views&color=06B6D4&style=for-the-badge" alt="Profile views" />

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:8B5CF6,100:06B6D4&height=3&section=header" alt="" />

## <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="28"> &nbsp;About Me

```yaml
name:        Dhanush G
role:        Junior AI Engineer @ StratAI
experience:  10 months across 3 AI roles
location:    Coimbatore, India
education:   B.E. Artificial Intelligence & Data Science — CGPA 8.6
focus:       [Generative AI, LLMs, RAG, AI Agents, MCP, Automation]
mission:     Build intelligent systems that solve real-world problems.
```

<table>
<tr>
<td width="50%" valign="top">

**🤖 What I build**

- Multi-agent workflows with **LangChain + LangGraph**
- **RAG pipelines** over catalogues, policy docs and knowledge bases
- **MCP servers** that wire models to live business systems
- **LLM automation** with n8n, FastAPI and Supabase

</td>
<td width="50%" valign="top">

**🎯 How I work**

- Grounded answers, or **none at all** — no confident guessing
- Every phase **verified** before the next one starts
- Ship **real systems**, not prototypes
- Analysis has to end in a **recommended action**

</td>
</tr>
</table>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:8B5CF6,100:06B6D4&height=3&section=header" alt="" />

## 🏗️ &nbsp;How I Build AI Systems

The request path behind everything I ship:

```mermaid
flowchart LR
    U["👤 User<br/>question or trigger"] --> A["🖥️ Application<br/>dashboard / assistant"]
    A --> API["⚡ API Layer<br/>FastAPI · route handlers"]
    API --> O["🧠 AI Orchestration<br/>context + tool selection"]
    O --> R["📚 RAG / MCP Tools<br/>retrieval · live systems"]
    R --> L["✨ LLM<br/>grounded reasoning"]
    L --> RES["✅ Response<br/>answer or action"]

    style U fill:#6366f1,stroke:#4338ca,stroke-width:2px,color:#fff
    style A fill:#7c3aed,stroke:#6d28d9,stroke-width:2px,color:#fff
    style API fill:#8b5cf6,stroke:#7c3aed,stroke-width:2px,color:#fff
    style O fill:#a855f7,stroke:#9333ea,stroke-width:2px,color:#fff
    style R fill:#06b6d4,stroke:#0891b2,stroke-width:2px,color:#fff
    style L fill:#ec4899,stroke:#db2777,stroke-width:2px,color:#fff
    style RES fill:#10b981,stroke:#059669,stroke-width:2px,color:#fff
```

### 🛒 &nbsp;Flagship — Marketplace Management Agent

An agentic system that manages seller accounts **end to end** across three marketplaces:

```mermaid
flowchart LR
    subgraph SRC["🏬 Marketplace Sources"]
        A1["Amazon"]
        A2["Flipkart"]
        A3["Shopify"]
    end
    SRC --> ING["🔄 Ingestion and<br/>Normalisation"]
    ING --> AN["📊 Analytics Layer<br/>ads · pricing · inventory · reviews"]
    AN --> AG["🕸️ Multi-Agent Workflows<br/>LangGraph"]
    AG --> T["🔌 RAG + MCP Tools"]
    T --> INS["💡 AI Insights"]
    INS --> AC["🎯 Action Center<br/>Problem → Reason → Risk → Action"]

    style A1 fill:#f59e0b,stroke:#d97706,stroke-width:2px,color:#fff
    style A2 fill:#f59e0b,stroke:#d97706,stroke-width:2px,color:#fff
    style A3 fill:#f59e0b,stroke:#d97706,stroke-width:2px,color:#fff
    style ING fill:#6366f1,stroke:#4338ca,stroke-width:2px,color:#fff
    style AN fill:#8b5cf6,stroke:#7c3aed,stroke-width:2px,color:#fff
    style AG fill:#a855f7,stroke:#9333ea,stroke-width:2px,color:#fff
    style T fill:#06b6d4,stroke:#0891b2,stroke-width:2px,color:#fff
    style INS fill:#ec4899,stroke:#db2777,stroke-width:2px,color:#fff
    style AC fill:#10b981,stroke:#059669,stroke-width:2px,color:#fff
```

> [!NOTE]
> Every marketplace publishes its own report shapes and grains. The hard part is not the model —
> it is reconciling the data so a metric means the same thing on all three platforms, and refusing
> to produce a confident-looking answer when the underlying data is missing.

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:8B5CF6,100:06B6D4&height=3&section=header" alt="" />

## 🧰 &nbsp;Tech Stack

<div align="center">

**🧠 AI & Generative AI**

<img src="https://img.shields.io/badge/LLMs-6366F1?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/RAG-8B5CF6?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/AI_Agents-A855F7?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/MCP-D97757?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" />
<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white" />
<img src="https://img.shields.io/badge/Vector_DBs-EC4899?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Prompt_Engineering-06B6D4?style=for-the-badge&logoColor=white" />

**💻 Languages & Backend**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge&logoColor=white" />

**🎨 Frontend**

<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />

**🗄️ Data & Automation**

<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" />
<img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/Webhooks-1F2937?style=for-the-badge&logoColor=white" />

**☁️ Cloud & Tooling**

<img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white" />

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:8B5CF6,100:06B6D4&height=3&section=header" alt="" />

## 🚀 &nbsp;Featured Work

<table>
<tr>
<td width="50%" valign="top">

### 🛒 AI Marketplace Management Agent
Agentic system managing listings, dynamic repricing and inventory sync across **Amazon, Flipkart & Shopify** — ending in an AI Action Center with priority and risk scoring.

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-8B5CF6?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

</td>
<td width="50%" valign="top">

### 🔎 Smart Verified RAG Assistant
FAISS semantic search over real documents plus **MCP tools**, so the assistant reaches live business systems instead of guessing.

![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-D97757?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 LAKSH Dashboard
Seller analytics dashboard over a **100+ table PostgreSQL schema**, with SKU-level performance views and AI-generated suggestions.

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

</td>
<td width="50%" valign="top">

### 🧬 Product Catalog Matching Engine
Fuzzy-matching pipeline unifying catalogs across Flipkart, Amazon, Shopify and offline shop data into one `product_master` schema.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ LLM Workflow Automation
Scheduled n8n workflows for price tracking, return-rate monitoring and AI news — LLM processing with structured writes to Supabase.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

</td>
<td width="50%" valign="top">

### 🧠 LifeOS &nbsp;`in progress`
A personal AI operating system, built phase by phase — each phase verified before the next one starts.

![LLMs](https://img.shields.io/badge/LLMs-6366F1?style=flat-square)
![AI Agents](https://img.shields.io/badge/AI_Agents-A855F7?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
</tr>
</table>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:8B5CF6,100:06B6D4&height=3&section=header" alt="" />

## 💼 &nbsp;Experience

```text
🟢 May 2026 → Present    Junior AI Engineer      StratAI          Coimbatore · Onsite
                         Agentic marketplace management · LangGraph multi-agent
                         workflows · LLM repricing engines · RAG · FastAPI

🔵 Feb 2026 → Apr 2026   AI Automation Intern    StratAI          Coimbatore · Onsite
                         n8n LLM automation · OpenAI & Telegram integrations
                         price tracking · Supabase pipelines

🟣 Nov 2025 → Jan 2026   AI Intern               Soul Creationz   Remote
                         LLM chatbots · RAG Q&A over business documents
                         FastAPI backends · prompt optimisation
```

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:8B5CF6,100:06B6D4&height=3&section=header" alt="" />

## 🌱 &nbsp;Currently Exploring

<div align="center">

<img src="https://img.shields.io/badge/Agentic_architecture_patterns-6366F1?style=for-the-badge" />
<img src="https://img.shields.io/badge/Advanced_MCP_server_design-8B5CF6?style=for-the-badge" />
<img src="https://img.shields.io/badge/Scaling_RAG_on_messy_data-06B6D4?style=for-the-badge" />
<img src="https://img.shields.io/badge/Claude_Certified_Architect-D97757?style=for-the-badge&logo=claude&logoColor=white" />

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:8B5CF6,100:06B6D4&height=3&section=header" alt="" />

## 📊 &nbsp;GitHub Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Dhanushgs1&hide_border=true&theme=tokyonight&ring=8B5CF6&fire=EC4899&currStreakLabel=06B6D4&sideNums=6366F1&sideLabels=8B5CF6&dates=64748B" />
  <img src="https://streak-stats.demolab.com?user=Dhanushgs1&hide_border=true&ring=8B5CF6&fire=EC4899&currStreakLabel=06B6D4&sideNums=6366F1&sideLabels=8B5CF6" alt="GitHub streak" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Dhanushgs1&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Dhanushgs1&theme=github" alt="Profile summary" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Dhanushgs1&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Dhanushgs1&theme=github" height="200" alt="Repos per language" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Dhanushgs1&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Dhanushgs1&theme=github" height="200" alt="Most used language" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Dhanushgs1&theme=github_dark&utcOffset=5.5" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Dhanushgs1&theme=github&utcOffset=5.5" height="200" alt="Productive time" />
</picture>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:8B5CF6,100:06B6D4&height=3&section=header" alt="" />

## 📫 &nbsp;Let Us Talk

<div align="center">

If you are building something with **agents, RAG or MCP** — I would like to hear about it.

<br/><br/>

<a href="mailto:dhanushgovindhang@gmail.com"><img src="https://img.shields.io/badge/dhanushgovindhang@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/dhanush-gs/"><img src="https://img.shields.io/badge/dhanush--gs-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://github.com/Dhanushgs1"><img src="https://img.shields.io/badge/Dhanushgs1-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,50:8B5CF6,100:6366F1&height=140&section=footer&text=Build%20intelligent%20systems%20that%20solve%20real-world%20problems.&fontSize=17&fontColor=ffffff&fontAlignY=72" alt="" />
