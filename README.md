<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,35:0072ff,70:7b2ff7,100:9b30ff&height=220&section=header&text=MANAS%20SANJAY%20MISHRA&fontSize=38&fontColor=ffffff&fontAlignY=38&desc=Data%20Engineering%20Enthusiast%20%E2%80%A2%20AI%20Builder%20%E2%80%A2%20Problem%20Solver&descAlignY=60&descColor=e6f2ff&animation=fadeIn" width="100%" />

<a href="https://github.com/manassanjaymishra24">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3000&pause=1200&color=7B2FF7&center=true&vCenter=true&width=600&lines=Turning+messy+data+into+decisions;Building+auditable%2C+dry-run+ML+systems;Hybrid+search+%2B+RAG+%2B+forecasting;Open+to+data+%2B+AI+collaborations" alt="Typing SVG" />
</a>

</div>

---

<div align="center">

[![Profile Views](https://komarev.com/ghpvc/?username=manassanjaymishra24&color=0072ff&style=flat-square&label=PROFILE+VIEWS)](https://github.com/manassanjaymishra24)&nbsp;
![Joined](https://img.shields.io/badge/JOINED-SEP%202025-0072ff?style=flat-square)&nbsp;
![Location](https://img.shields.io/badge/📍-India-0072ff?style=flat-square)

</div>

---

## 💫 About Me

Hey, I'm Manas — I build systems that turn raw, messy data into something you can act on.

Recent work spans behavioral analytics ([Sentinel](https://github.com/manassanjaymishra24/Sentinel) — detects multi-week attack patterns and outputs auditable dry-run response plans), market analysis ([Market-Oracle](https://github.com/manassanjaymishra24/Market-Oracle) — uncertainty-aware signal interpretation across timeframes), and retrieval-augmented generation ([Hybrid-RAG-Pipeline](https://github.com/manassanjaymishra24/hybrid-rag-pipeline) — hybrid dense + BM25 search with reranking and verified citations, running fully local with no API keys). On the data side, I've shipped Streamlit dashboards like [Retail-analytics-pro](https://github.com/manassanjaymishra24/Retail-analytics-pro) that ingest raw sales data, auto-normalize schemas, and surface forecasts.

I work mainly in **Python** for data/ML pipelines and **TypeScript** when a project needs a real frontend or backend-for-frontend layer — happy to go full-stack when the problem calls for it.

- 🌱 Active open-source contributor — merged PRs across community projects
- 🔭 Currently exploring: applied ML for decision systems (forecasting, anomaly detection, signal interpretation)
- 💬 Open to collaborating on data + AI tooling, especially anything analytics-adjacent

<img src="https://raw.githubusercontent.com/manassanjaymishra24/manassanjaymishra24/main/assets/terminal.svg" alt="terminal" width="100%" />

---


## 🎯 What I'm Currently Building

- 📊 **Data Engineering & Analytics** — schema normalization, ETL pipelines, forecasting dashboards (Retail-analytics-pro, ecommerce-sales-eda)
- 🛡️ **Behavioral Security Systems** — multi-week attack-pattern detection with auditable, dry-run response plans (Sentinel)
- 📈 **Market Signal Interpretation** — uncertainty-aware analysis across multiple timeframes (Market-Oracle)
- 🔎 **Retrieval-Augmented Generation** — local hybrid dense + BM25 search with reranking and empirically-verified citations, no API keys (Hybrid-RAG-Pipeline)
- 🤖 **Applied ML for Decision Systems** — forecasting and anomaly detection as a general toolkit, not just one-off notebooks
- 🌐 **Full-stack tooling** — TypeScript backend-for-frontend layers when a project needs a real UI on top of the data work

---

## 🌟 Featured Projects

| Project | What it does |
|---|---|
| 🛡️ [**Sentinel**](https://github.com/manassanjaymishra24/Sentinel) | Detects multi-week behavioral attack patterns and outputs auditable, dry-run incident response plans |
| 📈 [**Market-Oracle**](https://github.com/manassanjaymishra24/Market-Oracle) | Uncertainty-aware market signal interpretation across multiple timeframes |
| 🔎 [**Hybrid-RAG-Pipeline**](https://github.com/manassanjaymishra24/hybrid-rag-pipeline) | Local hybrid-search RAG system with dense + BM25 retrieval, reranking, and empirically-verified citations — no API keys, runs entirely on-device |
| 🛒 [**Retail-analytics-pro**](https://github.com/manassanjaymishra24/Retail-analytics-pro) | Streamlit dashboard that ingests raw sales data, auto-normalizes schemas, and surfaces forecasts |

<details>
<summary>View Hybrid-RAG-Pipeline architecture</summary>

```
Documents (PDF, docx, md)
        │
        ▼
Parse → Chunk → Embed (dense + sparse) → Qdrant
                                              │
Question ──────────────────────────────────┐ │
        │                                  ▼ ▼
        ├─── Dense search (Qdrant) ───┐
        └─── Sparse search (Qdrant) ──┴─→ RRF fusion → Rerank (top-5)
                                                              │
                                                              ▼
                                              Ollama LLM generates cited answer
                                                              │
                                                              ▼
                                    Structural + faithfulness verification
                                                              │
                                                              ▼
                                                    Answer + citations + verification status
```

Fully local stack: FastAPI + Qdrant (dense & sparse in one collection) + `BAAI/bge-reranker-base` + `qwen2.5:7b-instruct` via Ollama. No API keys anywhere.

</details>

---

## 💻 Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/python-0072FF?style=for-the-badge&logo=python&logoColor=ffdd54)
![C](https://img.shields.io/badge/c-%2300C6FF.svg?style=for-the-badge&logo=c&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%237B2FF7.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%230072FF.svg?style=for-the-badge&logo=javascript&logoColor=%23E6F2FF)

**Data & AI**

![Pandas](https://img.shields.io/badge/pandas-%230072FF.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%2300C6FF.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=0072FF)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%237B2FF7.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-%2300C6FF.svg?style=for-the-badge&logo=jupyter&logoColor=white)

**Tools & Cloud**

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FF4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/git-%230072FF.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## 🛠️ Top Languages

```
Python         ██████████████████░░░░░░░░░░░░░░░░░░░░░░  45%
TypeScript     ██████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  25%
Jupyter NB     ████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  20%
JavaScript     ████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  10%
```

<!--
These percentages are a manual estimate based on Manas's own-authored projects
(Sentinel, Market-Oracle, Retail-analytics-pro, hybrid-rag-pipeline, autotune-ai,
Netflix-Data-Analysis, Resonance-Tunin-In), weighted toward Python since it's the
primary language across most of his original data/ML/backend work. It intentionally
excludes forked repos from open-source contributions, which would otherwise skew
the numbers toward whatever language those upstream projects use.

Want an exact, auto-computed version instead? Use github-readme-stats.vercel.app's
Top Languages Card, which pulls live byte-counts from the GitHub API:
https://github-readme-stats.vercel.app/api/top-langs/?username=manassanjaymishra24
It's a shared public instance and can return a broken image once it hits GitHub's
API rate limit. Fix: self-host your own instance (free, ~5 min):
https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own-vercel-instance
Then swap the image URL's domain for your own deployment's domain.
-->

---

## 🐍 Contribution Graph

<div align="center">

<img src="https://raw.githubusercontent.com/manassanjaymishra24/manassanjaymishra24/output/snake.svg" alt="Snake animation" />

</div>

---

## 🌐 Socials

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/manas-mishra-09436a37a)&nbsp;
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:manassanjaymishra24@gmail.com)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/manassanjaymishra24)&nbsp;
![Discord](https://img.shields.io/badge/Discord-msm24__-5865F2?style=for-the-badge&logo=discord&logoColor=white)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9b30ff,30:7b2ff7,65:0072ff,100:00c6ff&height=120&section=footer&text=Building+systems+that+think&fontSize=16&fontColor=e6f2ff&fontAlignY=65&animation=fadeIn" width="100%" />

*"Beyond simple alerts. Beyond simple code."*

</div>
