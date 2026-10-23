<div align="center">
  <h1>Dhyey Vyas</h1>
  <p>Graduate Data Analyst &nbsp;·&nbsp; Melbourne, Australia &nbsp;·&nbsp; Full work rights</p>

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-dhyeyuvyas-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dhyeyuvyas)
  [![Email](https://img.shields.io/badge/Email-dhyeyvyas2003%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:dhyeyvyas2003@gmail.com)
  [![GitHub](https://img.shields.io/badge/GitHub-Dhyey2901-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Dhyey2901)
</div>

---

Master of Data Science (**Distinction**) @ RMIT, 2026. I turn messy data into clear answers: tested SQL and dbt pipelines, dashboards people actually read, and AI tools that say "I don't know" instead of making things up.

Latest: **[ShopPulse](https://github.com/Dhyey2901/ShopPulse)**, an Airflow → BigQuery → dbt pipeline with 66 data tests, a churn model and a dashboard on top.

**Experience:** Data Analytics Intern @ **Reliance Industries** (HR attrition analysis, SAP data, Power BI) · ML Capstone @ **Prodegee** (geospatial AI, satellite imagery) · Event Ops Supervisor @ **GEMA Group** (Australian Open, Formula 1 GP)

---

### What I work with

| | |
|---|---|
| **Analytics** | `SQL` `dbt` `BigQuery` `PostgreSQL` `Power BI` `Looker Studio` `Excel` `Pandas` `R` |
| **Data engineering** | `Airflow` `Docker` `GitHub Actions` `pytest` `SQLFluff` |
| **ML / AI** | `Python` `Scikit-Learn` `TensorFlow` `HuggingFace` `RAG` `LLMs` `pgvector` |
| **Apps** | `Next.js` `TypeScript` `FastAPI` `Flask` `Streamlit` `R Shiny` `Vercel` `Render` |

---

### Featured projects

**[ShopPulse](https://github.com/Dhyey2901/ShopPulse)** — E-commerce data pipeline & churn model
> Airflow (Docker) ingests a public-holiday REST API into BigQuery, **12 dbt models** turn ~125K raw orders into sales, funnel and customer marts, then a RandomForest churn model trains on the result and a Looker Studio dashboard reads the output. **66 data tests** (uniqueness, referential integrity, accepted values, ranges, row-count parity) caught a join fan-out that was double-counting daily sales. Caught label leakage behind a perfect 1.0 score and reported honest metrics instead: precision 0.945, recall 0.347, ROC-AUC 0.685. Runs on a daily schedule with CI (Ruff, SQLFluff, pytest).

**[Prism](https://github.com/Dhyey2901/prism)** — AI-powered data reporting platform · [Live ↗](https://prismanalytics.app)
> Upload a spreadsheet, get a streamed AI analysis with interactive charts, a PDF report and a follow-up chat grounded in your data. Raw data never leaves the browser; only summary statistics reach the model. Every AI response is schema-validated, saved analyses are searchable by meaning (pgvector), and rate limiting holds across serverless instances (Upstash Redis). 58 unit tests. Next.js 16, Gemini 2.5 Flash, Neon Postgres, Vercel.

**[Diabetes Clinical Q&A](https://github.com/Dhyey2901/diabetes-rag)** — RAG over ADA Standards of Care 2025 · [Live ↗](https://diabetes-rag.onrender.com)
> 358-page guideline → 912 chunks. Hybrid BM25 + dense retrieval with RRF fusion and MMR diversification. Abstention-first design: it refuses to answer when confidence is low rather than hallucinate. **86.7% accuracy** on an 84-question gold eval set.

**[JD Lens](https://github.com/Dhyey2901/jd-lens)** — NLP role-fit scorer · [Live demo ↗](https://jd-lens-ahnqxbthuw8t3tdr4mnuaw.streamlit.app/)
> Paste a job description and a resume, get a fit score, a skill-gap analysis and a four-quadrant verdict. Hybrid scoring: semantic 30% + TF-IDF 30% + skill match 40%, adapted across 6 role types. FastAPI + Docker Compose · 126 tests · eval harness · GitHub Actions CI (Python 3.11/3.12).

**[F1 Grid Analysis](https://github.com/Dhyey2901/f1_dashboard)** — Analytics dashboard · [Live demo ↗](https://dhyey2901.shinyapps.io/f1_dashboard)
> 9-tab dashboard across 70+ years of F1 data. Logistic regression shows a 15–18% drop in podium odds per grid position back (p < 0.001); K-Means groups drivers into four performance archetypes. Built for non-technical audiences in R Shiny + Plotly.

---

<div align="center">
  <i>Open to graduate and junior data analyst, BI and analytics engineering roles in Melbourne and across Australia. Full working rights, no sponsorship needed.</i>
</div>
