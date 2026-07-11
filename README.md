<!--
  laurentaf — GitHub Profile README
  README.md  |  github.com/laurentaf/laurentaf
  Brand: AI Engineer · Data Architect · System Builder
  Tone: Professional, personal, impactful.
  Iteration: 2026-07-11 (v4) — toggle CSS EN/PT, about me,
    quote destacada abaixo do header.
-->

<input type="radio" name="lang" id="lang-en" class="lang-toggle-input" checked>
<input type="radio" name="lang" id="lang-pt" class="lang-toggle-input">

<style>
  .lang-toggle-input { display: none; position: absolute; left: -9999px; }
  .lang-content { display: none; }
  #lang-en:checked ~ .lang-content.lang-en { display: block; }
  #lang-pt:checked ~ .lang-content.lang-pt { display: block; }

  .lang-bar { text-align: center; margin: 16px 0 8px; }
  .lang-btn {
    display: inline-block; padding: 5px 18px; margin: 0 3px;
    border-radius: 20px; cursor: pointer; font-size: 0.85em; font-weight: 600;
    border: 1.5px solid #6c5ce7; color: #6c5ce7; background: transparent;
    transition: all 0.2s; user-select: none;
  }
  #lang-en:checked ~ .lang-bar .lang-btn-en,
  #lang-pt:checked ~ .lang-bar .lang-btn-pt {
    background: #6c5ce7; color: #fff; box-shadow: 0 2px 8px rgba(108,92,231,0.3);
  }
  .lang-btn:hover { opacity: 0.8; }

  .quote-box {
    margin: 28px auto; max-width: 600px;
    border-left: 3px solid #6c5ce7; padding: 12px 20px;
    background: rgba(108,92,231,0.04); border-radius: 0 8px 8px 0;
  }
  .quote-box p { margin: 0; font-style: italic; font-size: 1.05em; color: #2d3436; }
  .quote-box cite { display: block; margin-top: 6px; font-size: 0.8em; color: #636e72; font-style: normal; }
</style>

<!-- ==================== TOGGLE BAR ==================== -->
<div class="lang-bar">
  <label for="lang-en" class="lang-btn lang-btn-en">🇺🇸 EN</label>
  <label for="lang-pt" class="lang-btn lang-btn-pt">🇧🇷 PT</label>
</div>

<!-- ================================================================ -->
<!-- ==================== ENGLISH CONTENT =========================== -->
<!-- ================================================================ -->
<div class="lang-content lang-en">

<div align="center" style="margin-top:36px;margin-bottom:20px;">

<!-- Emblem -->
<svg width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" style="margin-bottom:2px;">
  <rect x="4" y="4" width="56" height="56" rx="12" stroke="#6c5ce7" stroke-width="1.5" fill="none" opacity="0.3"/>
  <path d="M18 14 L18 48 L38 48" stroke="#6c5ce7" stroke-width="3" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M40 48 L46 24 L52 48" stroke="#6c5ce7" stroke-width="2.5" fill="none" stroke-linecap="round" stroke-linejoin="round" opacity="0.6"/>
  <line x1="44" y1="38" x2="50" y2="38" stroke="#6c5ce7" stroke-width="1.5" opacity="0.4"/>
  <circle cx="14" cy="14" r="2.5" fill="#6c5ce7" opacity="0.4"/>
  <circle cx="50" cy="14" r="2.5" fill="#6c5ce7" opacity="0.4"/>
  <circle cx="32" cy="56" r="2.5" fill="#6c5ce7" opacity="0.4"/>
  <line x1="14" y1="14" x2="50" y2="14" stroke="#6c5ce7" stroke-width="0.8" opacity="0.2"/>
  <line x1="14" y1="14" x2="32" y2="56" stroke="#6c5ce7" stroke-width="0.8" opacity="0.2"/>
  <line x1="50" y1="14" x2="32" y2="56" stroke="#6c5ce7" stroke-width="0.8" opacity="0.2"/>
</svg>

<br/>

# Hi, I'm Laurent

### AI Engineer · Data Analyst · Data Engineer

<p style="margin:10px 0;font-size:0.9em;color:#636e72;">
  <span style="background:#6c5ce7;color:#fff;padding:2px 12px;border-radius:4px;font-size:0.85em;">📍 Campinas/SP</span>
  &nbsp;
  <span style="background:#636e72;color:#fff;padding:2px 12px;border-radius:4px;font-size:0.85em;">🌍 Remote-first</span>
</p>

<p style="margin:14px 0;">
  <a href="https://linkedin.com/in/lauferreira"><img src="https://img.shields.io/badge/LinkedIn-lauferreira-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  &nbsp;
  <a href="mailto:laurentalp@hotmail.com"><img src="https://img.shields.io/badge/Email-laurentalp@hotmail.com-0078D4?style=flat&logo=microsoft-outlook&logoColor=white" alt="Email"/></a>
</p>

<p style="margin:2px 0 10px;font-size:0.82em;color:#b2bec3;">
  <code>linkedin.com/in/lauferreira</code>
  &nbsp;·&nbsp;
  <code>laurentalp@hotmail.com</code>
</p>

</div>

<!-- ==================== ABOUT ME ==================== -->
## 👤 About Me

I build **systems that build systems**.

My work sits at the intersection of **data engineering, AI orchestration, and governance** — from ETL pipelines and dimensional modeling to multi-agent architectures and interpretable ML (econometrics, SHAP, causal inference).

I created **LAOS**, a meta-operating system that composes AI capabilities through deterministic routing, MCP protocols, and a governance engine with mechanical enforcement — because *data architecture isn't about the tools, it's about whether decisions are trustworthy at scale.*

**What drives me:** Turning complex, messy data into architectures that people — and other AIs — can trust and build upon.

**Currently:** Building composable AI systems · Diving deeper into econometrics & causal inference · Open-sourcing everything I can.

<!-- ==================== QUOTE ==================== -->
<div class="quote-box">
  <p>"Technology is the way to materialize your dreams. AI is the shortcut."</p>
  <cite>— Laurent Ferreira</cite>
</div>

---

## 🛠️ Stack

### Languages

<a href="https://github.com/laurentaf?tab=repositories&q=python"><img src="https://img.shields.io/badge/Python-%E2%89%A53.11-3776AB?style=flat&logo=python&logoColor=fff" alt="Python"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=typescript"><img src="https://img.shields.io/badge/TypeScript-44.7%25-3178C6?style=flat&logo=typescript&logoColor=fff" alt="TypeScript"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=sql"><img src="https://img.shields.io/badge/SQL-%E2%89%A52%20dials-CC2927?style=flat&logo=oracle&logoColor=fff" alt="SQL"/></a>

### Libraries & Frameworks

<a href="https://github.com/laurentaf?tab=repositories&q=scikit"><img src="https://img.shields.io/badge/scikit--learn-ML-F7931E?style=flat&logo=scikit-learn&logoColor=fff" alt="scikit-learn"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=xgboost"><img src="https://img.shields.io/badge/xgboost-Boost-FF6600?style=flat" alt="xgboost"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=lightgbm"><img src="https://img.shields.io/badge/LightGBM-Gradient-7A1FA2?style=flat" alt="LightGBM"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=catboost"><img src="https://img.shields.io/badge/CatBoost-Open--Source-FFD700?style=flat" alt="CatBoost"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=statsmodels"><img src="https://img.shields.io/badge/statsmodels-Econometrics-1C3D5A?style=flat" alt="statsmodels"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=shap"><img src="https://img.shields.io/badge/SHAP-Explainability-00B4D8?style=flat" alt="SHAP"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=lime"><img src="https://img.shields.io/badge/LIME-Interpretability-FF6B6B?style=flat" alt="LIME"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=optuna"><img src="https://img.shields.io/badge/Optuna-HPO-3E8E41?style=flat" alt="Optuna"/></a>

<a href="https://github.com/laurentaf?tab=repositories&q=crewai"><img src="https://img.shields.io/badge/CrewAI-Multi--Agent-FF6B35?style=flat" alt="CrewAI"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=langgraph"><img src="https://img.shields.io/badge/LangGraph-Agent%20Graph-00b894?style=flat" alt="LangGraph"/></a>

### Tools & Platforms

<a href="https://github.com/laurentaf?tab=repositories&q=docker"><img src="https://img.shields.io/badge/Docker-Containerized-2496ED?style=flat&logo=docker&logoColor=fff" alt="Docker"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=airflow"><img src="https://img.shields.io/badge/Airflow-Pipelines-017CEE?style=flat&logo=apacheairflow&logoColor=fff" alt="Airflow"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=dbt"><img src="https://img.shields.io/badge/dbt-Data%20Build%20Tool-FF694B?style=flat&logo=dbt&logoColor=fff" alt="dbt"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=duckdb"><img src="https://img.shields.io/badge/DuckDB-OLAP-FFF000?style=flat&logo=duckdb&logoColor=000" alt="DuckDB"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=postgresql"><img src="https://img.shields.io/badge/PostgreSQL-DB-4169E1?style=flat&logo=postgresql&logoColor=fff" alt="PostgreSQL"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=n8n"><img src="https://img.shields.io/badge/n8n-Workflows-FF6B6B?style=flat&logo=n8n&logoColor=fff" alt="n8n"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=fabric"><img src="https://img.shields.io/badge/MS%20Fabric-Analytics-0078D4?style=flat&logo=microsoftfabric&logoColor=fff" alt="MS Fabric"/></a>

### Data Visualization

<a href="https://github.com/laurentaf?tab=repositories&q=power+bi"><img src="https://img.shields.io/badge/Power%20BI-BI-F2C811?style=flat&logo=powerbi&logoColor=000" alt="Power BI"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=html"><img src="https://img.shields.io/badge/HTML5-Markup-E34F26?style=flat&logo=html5&logoColor=fff" alt="HTML5"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=css"><img src="https://img.shields.io/badge/CSS3-Styles-1572B6?style=flat&logo=css3&logoColor=fff" alt="CSS3"/></a>

### Cloud Providers

<a href="https://github.com/laurentaf?tab=repositories&q=azure"><img src="https://img.shields.io/badge/Azure-Cloud-0078D4?style=flat&logo=microsoftazure&logoColor=fff" alt="Azure"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=render"><img src="https://img.shields.io/badge/Render-Deploy-46E3B7?style=flat&logo=render&logoColor=000" alt="Render"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=supabase"><img src="https://img.shields.io/badge/Supabase-Backend-3FCF8E?style=flat&logo=supabase&logoColor=fff" alt="Supabase"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=databricks"><img src="https://img.shields.io/badge/Databricks-Lakehouse-FF3621?style=flat&logo=databricks&logoColor=fff" alt="Databricks"/></a>

### AI Providers

<a href="https://github.com/laurentaf?tab=repositories&q=openai"><img src="https://img.shields.io/badge/OpenAI-GPT-412991?style=flat&logo=openai&logoColor=fff" alt="OpenAI"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=google+ai"><img src="https://img.shields.io/badge/Google%20Gemini-AI-8E75B2?style=flat&logo=googlegemini&logoColor=fff" alt="Google Gemini"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=anthropic"><img src="https://img.shields.io/badge/Anthropic-Claude-191919?style=flat&logo=anthropic&logoColor=fff" alt="Anthropic Claude"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=nvidia+nim"><img src="https://img.shields.io/badge/NVIDIA%20NIM-Inference-76B900?style=flat&logo=nvidia&logoColor=fff" alt="NVIDIA NIM"/></a>

### Standards

<a href="https://github.com/laurentaf?tab=repositories&q=mcp"><img src="https://img.shields.io/badge/MCP-Protocol-6c5ce7?style=flat" alt="MCP Protocol"/></a>

### Featured

<a href="https://github.com/laurentaf/laos"><img src="https://img.shields.io/badge/%F0%9F%94%A5%20LAOS-Ecosystem-6c5ce7?style=flat&logo=github&logoColor=fff" alt="LAOS Ecosystem"/></a>

---

## 🚀 Flagship: LAOS

I built **LAOS**, a meta-operating system for composable AI. It orchestrates **7 modules** — 5 independent domain MCP capabilities, the **LACOUNCIL governance engine** (14+ approved proposals, 3 voting strategies, DuckDB audit trail), and an orchestrator core with deterministic routing and mechanical enforcement.

<div align="center" style="margin:20px 0;">

| Capability | Domain | Status |
|:----------:|--------|:------:|
| 🗄️ **LATADE** | Data engineering (SQL, DuckDB, BI, DQ) | ✅ Stable |
| 🎨 **LADESIGN** | Design (dashboards, decks, wireframes) | ✅ Stable |
| ⚙️ **LAN8N** | Automation (n8n workflows, integrations) | ✅ Stable |
| 📊 **LAECON** | Econometrics (regression, GLM, causal, SHAP) | ✅ Stable |
| 🎮 **LAENGINE** | Game dev (match engine, league simulation) | 🟡 Basic |

</div>

<div align="center" style="margin:8px 0 16px;">
  <strong>115+ commits</strong> · <strong>11 agent types</strong> · <strong>13 TypeScript plugins</strong> · 17 knowledge files · 17 scripts · 3 dispatch modes
</div>

**[Explore LAOS →](https://github.com/laurentaf/laos)**
&nbsp;·&nbsp;
**[Full Portfolio →](https://github.com/laurentaf?tab=repositories)**

---

## 📦 Featured Projects

| Project | Description | Highlights |
|---------|-------------|:----------:|
| [**LAOS**](https://github.com/laurentaf/laos) | Meta-OS for composable AI · 7 modules · governance engine | 115 commits · 13 plugins · 11 agents |
| [**abandono-academico**](https://github.com/laurentaf/abandono-academico-casa-grande) | ML dropout prediction · OULAD dataset | 87.5% acc · 93.7% recall · 32,593 students |
| [**giovanna-rupture-monitor**](https://github.com/laurentaf/giovanna-rupture-monitor) | Retail stock-out analytics · fully Dockerized | 4,150 regions · 33% rupture detection |
| [**hospital-viana-claims**](https://github.com/laurentaf/hospital-viana-claims) | IFRS17 medical claims ETL pipeline | 10TB+ scale · Medallion Architecture |

---

## 📊 Impact

<table style="border-collapse:separate;border-spacing:0;">
  <tr>
    <td align="center" style="padding:10px 16px;width:33%;border:1px solid #6c5ce7;border-radius:8px 0 0 8px;border-right:none;">
      <div style="font-weight:700;font-size:1em;color:#6c5ce7;">ML &amp; Prediction</div>
      <div style="font-size:0.8em;opacity:0.6;"><strong>87.5%</strong> accuracy · <strong>93.7%</strong> recall<br/>32,593 students · dropout pipeline</div>
    </td>
    <td align="center" style="padding:10px 16px;width:33%;border:1px solid #6c5ce7;border-right:none;">
      <div style="font-weight:700;font-size:1em;color:#6c5ce7;">Pipeline Scale</div>
      <div style="font-size:0.8em;opacity:0.6;"><strong>10TB+</strong> data · 5 sources<br/>Medallion Architecture · IFRS17</div>
    </td>
    <td align="center" style="padding:10px 16px;width:33%;border:1px solid #6c5ce7;border-radius:0 8px 8px 0;">
      <div style="font-weight:700;font-size:1em;color:#6c5ce7;">Governance Engine</div>
      <div style="font-size:0.8em;opacity:0.6;"><strong>14+</strong> proposals · <strong>13</strong> plugins<br/>11 agents · DuckDB audit trail</div>
    </td>
  </tr>
</table>

| Area | Result |
|------|--------|
| LAOS velocity | 115+ commits · MIT licensed · active development |
| Retail coverage | 4,150 regions analyzed · single `docker run` deliverable |
| Exam modeling | 1,236 questions · 27 contests · Bayesian (no LLM hallucination) |
| Logistics | 50%+ cost reduction via process optimization (10-store chain) |

---

## 🌐 Find Me

<p>
  <a href="https://linkedin.com/in/lauferreira">
    <img src="https://img.shields.io/badge/LinkedIn-lauferreira-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="mailto:laurentalp@hotmail.com">
    <img src="https://img.shields.io/badge/Email-laurentalp@hotmail.com-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="Email"/>
  </a>
  &nbsp;
  <a href="https://github.com/laurentaf">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  &nbsp;
  <a href="https://github.com/laurentaf/laos">
    <img src="https://img.shields.io/badge/LAOS-Explore-6c5ce7?style=for-the-badge" alt="LAOS"/>
  </a>
</p>

<p style="margin:4px 0;font-size:0.85em;color:#b2bec3;">
  <code>linkedin.com/in/lauferreira</code>
  &nbsp;·&nbsp;
  <code>laurentalp@hotmail.com</code>
  &nbsp;·&nbsp;
  <code>github.com/laurentaf</code>
</p>

---

<div align="center" style="margin:36px 0;opacity:0.35;font-size:0.85em;">
  Built with <a href="https://github.com/laurentaf/laos" style="color:#6c5ce7;text-decoration:none;">LAOS</a> — the system that builds systems.
  <br/>
  <svg width="18" height="18" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" style="margin-top:6px;">
    <rect x="4" y="4" width="56" height="56" rx="12" stroke="#6c5ce7" stroke-width="1.5" fill="none" opacity="0.15"/>
    <path d="M20 16 L20 48 L38 48" stroke="#6c5ce7" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round" opacity="0.4"/>
    <path d="M40 48 L46 26 L52 48" stroke="#6c5ce7" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round" opacity="0.3"/>
    <line x1="44" y1="38" x2="49" y2="38" stroke="#6c5ce7" stroke-width="1" opacity="0.3"/>
  </svg>
</div>

</div><!-- /lang-en -->

<!-- ================================================================ -->
<!-- ==================== PORTUGUESE CONTENT ======================== -->
<!-- ================================================================ -->
<div class="lang-content lang-pt">

<div align="center" style="margin-top:36px;margin-bottom:20px;">

<!-- Emblem -->
<svg width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" style="margin-bottom:2px;">
  <rect x="4" y="4" width="56" height="56" rx="12" stroke="#6c5ce7" stroke-width="1.5" fill="none" opacity="0.3"/>
  <path d="M18 14 L18 48 L38 48" stroke="#6c5ce7" stroke-width="3" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M40 48 L46 24 L52 48" stroke="#6c5ce7" stroke-width="2.5" fill="none" stroke-linecap="round" stroke-linejoin="round" opacity="0.6"/>
  <line x1="44" y1="38" x2="50" y2="38" stroke="#6c5ce7" stroke-width="1.5" opacity="0.4"/>
  <circle cx="14" cy="14" r="2.5" fill="#6c5ce7" opacity="0.4"/>
  <circle cx="50" cy="14" r="2.5" fill="#6c5ce7" opacity="0.4"/>
  <circle cx="32" cy="56" r="2.5" fill="#6c5ce7" opacity="0.4"/>
  <line x1="14" y1="14" x2="50" y2="14" stroke="#6c5ce7" stroke-width="0.8" opacity="0.2"/>
  <line x1="14" y1="14" x2="32" y2="56" stroke="#6c5ce7" stroke-width="0.8" opacity="0.2"/>
  <line x1="50" y1="14" x2="32" y2="56" stroke="#6c5ce7" stroke-width="0.8" opacity="0.2"/>
</svg>

<br/>

# Olá, sou Laurent

### Engenheiro de IA · Analista de Dados · Engenheiro de Dados

<p style="margin:10px 0;font-size:0.9em;color:#636e72;">
  <span style="background:#6c5ce7;color:#fff;padding:2px 12px;border-radius:4px;font-size:0.85em;">📍 Campinas/SP</span>
  &nbsp;
  <span style="background:#636e72;color:#fff;padding:2px 12px;border-radius:4px;font-size:0.85em;">🌍 Remoto</span>
</p>

<p style="margin:14px 0;">
  <a href="https://linkedin.com/in/lauferreira"><img src="https://img.shields.io/badge/LinkedIn-lauferreira-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  &nbsp;
  <a href="mailto:laurentalp@hotmail.com"><img src="https://img.shields.io/badge/Email-laurentalp@hotmail.com-0078D4?style=flat&logo=microsoft-outlook&logoColor=white" alt="Email"/></a>
</p>

<p style="margin:2px 0 10px;font-size:0.82em;color:#b2bec3;">
  <code>linkedin.com/in/lauferreira</code>
  &nbsp;·&nbsp;
  <code>laurentalp@hotmail.com</code>
</p>

</div>

<!-- ==================== SOBRE MIM ==================== -->
## 👤 Sobre Mim

Eu construo **sistemas que constroem sistemas**.

Meu trabalho fica na interseção entre **engenharia de dados, orquestração de IA e governança** — desde pipelines ETL e modelagem dimensional até arquiteturas multi-agente e ML interpretável (econometria, SHAP, inferência causal).

Criei o **LAOS**, um meta-sistema operacional que compõe capacidades de IA através de roteamento determinístico, protocolos MCP e um motor de governança com aplicação mecânica — porque *arquitetura de dados não é sobre ferramentas, é sobre decisões serem confiáveis em escala.*

**O que me move:** Transformar dados complexos e bagunçados em arquiteturas que pessoas — e outras IAs — possam confiar e construir em cima.

**Atualmente:** Construindo sistemas de IA composáveis · Aprofundando em econometria & inferência causal · Open-sourcing tudo que posso.

<!-- ==================== QUOTE ==================== -->
<div class="quote-box">
  <p>"Tecnologia é o caminho para materializar seus sonhos. IA é o atalho."</p>
  <cite>— Laurent Ferreira</cite>
</div>

---

## 🛠️ Stack

### Linguagens

<a href="https://github.com/laurentaf?tab=repositories&q=python"><img src="https://img.shields.io/badge/Python-%E2%89%A53.11-3776AB?style=flat&logo=python&logoColor=fff" alt="Python"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=typescript"><img src="https://img.shields.io/badge/TypeScript-44.7%25-3178C6?style=flat&logo=typescript&logoColor=fff" alt="TypeScript"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=sql"><img src="https://img.shields.io/badge/SQL-%E2%89%A52%20dials-CC2927?style=flat&logo=oracle&logoColor=fff" alt="SQL"/></a>

### Bibliotecas & Frameworks

<a href="https://github.com/laurentaf?tab=repositories&q=scikit"><img src="https://img.shields.io/badge/scikit--learn-ML-F7931E?style=flat&logo=scikit-learn&logoColor=fff" alt="scikit-learn"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=xgboost"><img src="https://img.shields.io/badge/xgboost-Boost-FF6600?style=flat" alt="xgboost"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=lightgbm"><img src="https://img.shields.io/badge/LightGBM-Gradient-7A1FA2?style=flat" alt="LightGBM"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=catboost"><img src="https://img.shields.io/badge/CatBoost-Open--Source-FFD700?style=flat" alt="CatBoost"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=statsmodels"><img src="https://img.shields.io/badge/statsmodels-Econometrics-1C3D5A?style=flat" alt="statsmodels"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=shap"><img src="https://img.shields.io/badge/SHAP-Explainability-00B4D8?style=flat" alt="SHAP"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=lime"><img src="https://img.shields.io/badge/LIME-Interpretability-FF6B6B?style=flat" alt="LIME"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=optuna"><img src="https://img.shields.io/badge/Optuna-HPO-3E8E41?style=flat" alt="Optuna"/></a>

<a href="https://github.com/laurentaf?tab=repositories&q=crewai"><img src="https://img.shields.io/badge/CrewAI-Multi--Agent-FF6B35?style=flat" alt="CrewAI"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=langgraph"><img src="https://img.shields.io/badge/LangGraph-Agent%20Graph-00b894?style=flat" alt="LangGraph"/></a>

### Ferramentas & Plataformas

<a href="https://github.com/laurentaf?tab=repositories&q=docker"><img src="https://img.shields.io/badge/Docker-Containerized-2496ED?style=flat&logo=docker&logoColor=fff" alt="Docker"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=airflow"><img src="https://img.shields.io/badge/Airflow-Pipelines-017CEE?style=flat&logo=apacheairflow&logoColor=fff" alt="Airflow"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=dbt"><img src="https://img.shields.io/badge/dbt-Data%20Build%20Tool-FF694B?style=flat&logo=dbt&logoColor=fff" alt="dbt"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=duckdb"><img src="https://img.shields.io/badge/DuckDB-OLAP-FFF000?style=flat&logo=duckdb&logoColor=000" alt="DuckDB"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=postgresql"><img src="https://img.shields.io/badge/PostgreSQL-DB-4169E1?style=flat&logo=postgresql&logoColor=fff" alt="PostgreSQL"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=n8n"><img src="https://img.shields.io/badge/n8n-Workflows-FF6B6B?style=flat&logo=n8n&logoColor=fff" alt="n8n"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=fabric"><img src="https://img.shields.io/badge/MS%20Fabric-Analytics-0078D4?style=flat&logo=microsoftfabric&logoColor=fff" alt="MS Fabric"/></a>

### Visualização de Dados

<a href="https://github.com/laurentaf?tab=repositories&q=power+bi"><img src="https://img.shields.io/badge/Power%20BI-BI-F2C811?style=flat&logo=powerbi&logoColor=000" alt="Power BI"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=html"><img src="https://img.shields.io/badge/HTML5-Markup-E34F26?style=flat&logo=html5&logoColor=fff" alt="HTML5"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=css"><img src="https://img.shields.io/badge/CSS3-Styles-1572B6?style=flat&logo=css3&logoColor=fff" alt="CSS3"/></a>

### Cloud

<a href="https://github.com/laurentaf?tab=repositories&q=azure"><img src="https://img.shields.io/badge/Azure-Cloud-0078D4?style=flat&logo=microsoftazure&logoColor=fff" alt="Azure"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=render"><img src="https://img.shields.io/badge/Render-Deploy-46E3B7?style=flat&logo=render&logoColor=000" alt="Render"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=supabase"><img src="https://img.shields.io/badge/Supabase-Backend-3FCF8E?style=flat&logo=supabase&logoColor=fff" alt="Supabase"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=databricks"><img src="https://img.shields.io/badge/Databricks-Lakehouse-FF3621?style=flat&logo=databricks&logoColor=fff" alt="Databricks"/></a>

### Provedores de IA

<a href="https://github.com/laurentaf?tab=repositories&q=openai"><img src="https://img.shields.io/badge/OpenAI-GPT-412991?style=flat&logo=openai&logoColor=fff" alt="OpenAI"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=google+ai"><img src="https://img.shields.io/badge/Google%20Gemini-AI-8E75B2?style=flat&logo=googlegemini&logoColor=fff" alt="Google Gemini"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=anthropic"><img src="https://img.shields.io/badge/Anthropic-Claude-191919?style=flat&logo=anthropic&logoColor=fff" alt="Anthropic Claude"/></a>
<a href="https://github.com/laurentaf?tab=repositories&q=nvidia+nim"><img src="https://img.shields.io/badge/NVIDIA%20NIM-Inference-76B900?style=flat&logo=nvidia&logoColor=fff" alt="NVIDIA NIM"/></a>

### Padrões

<a href="https://github.com/laurentaf?tab=repositories&q=mcp"><img src="https://img.shields.io/badge/MCP-Protocol-6c5ce7?style=flat" alt="MCP Protocol"/></a>

### Destaque

<a href="https://github.com/laurentaf/laos"><img src="https://img.shields.io/badge/%F0%9F%94%A5%20LAOS-Ecosystem-6c5ce7?style=flat&logo=github&logoColor=fff" alt="LAOS Ecosystem"/></a>

---

## 🚀 Flagship: LAOS

Sistema operacional meta para IA composável. 7 módulos — 5 capacidades MCP independentes, motor de governança LACOUNCIL (14+ propostas aprovadas, 3 estratégias de voto, DuckDB audit trail), e um orquestrador com roteamento determinístico e aplicação mecânica.

<div align="center" style="margin:20px 0;">

| Capacidade | Domínio | Status |
|:----------:|---------|:------:|
| 🗄️ **LATADE** | Engenharia de dados (SQL, DuckDB, BI, DQ) | ✅ Stable |
| 🎨 **LADESIGN** | Design (dashboards, decks, wireframes) | ✅ Stable |
| ⚙️ **LAN8N** | Automação (n8n workflows, integrações) | ✅ Stable |
| 📊 **LAECON** | Econometria (regressão, GLM, causal, SHAP) | ✅ Stable |
| 🎮 **LAENGINE** | Game dev (match engine, simulação de liga) | 🟡 Basic |

</div>

<div align="center" style="margin:8px 0 16px;">
  <strong>115+ commits</strong> · <strong>11 tipos de agente</strong> · <strong>13 plugins TypeScript</strong> · 17 knowledge files · 17 scripts · 3 modos de dispatch
</div>

**[Explore o LAOS →](https://github.com/laurentaf/laos)**

---

## 📦 Projetos em Destaque

| Projeto | Descrição | Destaques |
|---------|-----------|:---------:|
| [**LAOS**](https://github.com/laurentaf/laos) | Meta-OS para IA composável · 7 módulos | 115 commits · 13 plugins · 11 agentes |
| [**abandono-academico**](https://github.com/laurentaf/abandono-academico-casa-grande) | ML para evasão escolar · Dataset OULAD | 87.5% acurácia · 93.7% recall · 32.593 alunos |
| [**giovanna-rupture-monitor**](https://github.com/laurentaf/giovanna-rupture-monitor) | Análise de ruptura em varejo · Dockerizado | 4.150 regiões · 33% detecção |
| [**hospital-viana-claims**](https://github.com/laurentaf/hospital-viana-claims) | Pipeline ETL IFRS17 de sinistros médicos | 10TB+ escala · Medallion Architecture |

---

## 📊 Impacto

<table style="border-collapse:separate;border-spacing:0;">
  <tr>
    <td align="center" style="padding:10px 16px;width:33%;border:1px solid #6c5ce7;border-radius:8px 0 0 8px;border-right:none;">
      <div style="font-weight:700;font-size:1em;color:#6c5ce7;">ML &amp; Predição</div>
      <div style="font-size:0.8em;opacity:0.6;"><strong>87.5%</strong> acurácia · <strong>93.7%</strong> recall<br/>32.593 alunos · pipeline de evasão</div>
    </td>
    <td align="center" style="padding:10px 16px;width:33%;border:1px solid #6c5ce7;border-right:none;">
      <div style="font-weight:700;font-size:1em;color:#6c5ce7;">Escala de Pipeline</div>
      <div style="font-size:0.8em;opacity:0.6;"><strong>10TB+</strong> dados · 5 fontes<br/>Medallion Architecture · IFRS17</div>
    </td>
    <td align="center" style="padding:10px 16px;width:33%;border:1px solid #6c5ce7;border-radius:0 8px 8px 0;">
      <div style="font-weight:700;font-size:1em;color:#6c5ce7;">Governança</div>
      <div style="font-size:0.8em;opacity:0.6;"><strong>14+</strong> propostas · <strong>13</strong> plugins<br/>11 agentes · DuckDB audit trail</div>
    </td>
  </tr>
</table>

| Área | Resultado |
|------|-----------|
| Velocidade LAOS | 115+ commits · MIT · desenvolvimento ativo |
| Cobertura varejo | 4.150 regiões analisadas · `docker run` único |
| Modelagem concursos | 1.236 questões · 27 concursos · Bayesiano (sem LLM) |
| Logística | 50%+ redução de custo (10 lojas) |

---

## 🌐 Contatos

<p>
  <a href="https://linkedin.com/in/lauferreira">
    <img src="https://img.shields.io/badge/LinkedIn-lauferreira-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="mailto:laurentalp@hotmail.com">
    <img src="https://img.shields.io/badge/Email-laurentalp@hotmail.com-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="Email"/>
  </a>
  &nbsp;
  <a href="https://github.com/laurentaf">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  &nbsp;
  <a href="https://github.com/laurentaf/laos">
    <img src="https://img.shields.io/badge/LAOS-Explore-6c5ce7?style=for-the-badge" alt="LAOS"/>
  </a>
</p>

<p style="margin:4px 0;font-size:0.85em;color:#b2bec3;">
  <code>linkedin.com/in/lauferreira</code>
  &nbsp;·&nbsp;
  <code>laurentalp@hotmail.com</code>
  &nbsp;·&nbsp;
  <code>github.com/laurentaf</code>
</p>

---

<div align="center" style="margin:36px 0;opacity:0.35;font-size:0.85em;">
  Construído com <a href="https://github.com/laurentaf/laos" style="color:#6c5ce7;text-decoration:none;">LAOS</a> — o sistema que constrói sistemas.
  <br/>
  <svg width="18" height="18" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" style="margin-top:6px;">
    <rect x="4" y="4" width="56" height="56" rx="12" stroke="#6c5ce7" stroke-width="1.5" fill="none" opacity="0.15"/>
    <path d="M20 16 L20 48 L38 48" stroke="#6c5ce7" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round" opacity="0.4"/>
    <path d="M40 48 L46 26 L52 48" stroke="#6c5ce7" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round" opacity="0.3"/>
    <line x1="44" y1="38" x2="49" y2="38" stroke="#6c5ce7" stroke-width="1" opacity="0.3"/>
  </svg>
</div>

</div><!-- /lang-pt -->
