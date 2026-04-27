# Story Bank — Master STAR+R Stories

This file accumulates your best interview stories over time. Each evaluation (Block F) adds new stories here. Instead of memorizing 100 answers, maintain 5-10 deep stories that you can bend to answer almost any behavioral question.

## How it works

1. Every time `/career-ops oferta` generates Block F (Interview Plan), new STAR+R stories get appended here
2. Before your next interview, review this file — your stories are already organized by theme
3. The "Big Three" questions can be answered with stories from this bank:
   - "Tell me about yourself" → combine 2-3 stories into a narrative
   - "Tell me about your most impactful project" → pick your highest-impact story
   - "Tell me about a conflict you resolved" → find a story with a Reflection

## Stories

<!-- Format:
### [Theme] Story Title
**Source:** Report #NNN — Company — Role
**S (Situation):** ...
**T (Task):** ...
**A (Action):** ...
**R (Result):** ...
**Reflection:** What I learned / what I'd do differently
**Best for questions about:** [list of question types this story answers]
-->

### [Impact] Operational KPI Dashboard — 80% Reporting Automation
**Source:** Report #001 — Twitch (Amazon) — Data Scientist
**S:** Add On Support Services leadership lacked real-time visibility into daily operations, ticket flow, and team performance.
**T:** Build an executive dashboard that eliminated manual reporting and surfaced bottlenecks automatically.
**A:** Built a live Tableau dashboard powered by PostgreSQL, Salesforce, and Excel trackers; integrated Airflow ETL pipelines using Python (Pandas, SQLAlchemy) to fully automate data ingestion.
**R:** Reduced manual reporting by 80%; enabled leadership to identify bottlenecks and improve team throughput by 20%.
**Reflection:** Would have added anomaly detection alerts from day one — stakeholders kept asking "why did this spike?" after the fact. Proactive alerting would have shifted conversations from reactive to strategic.
**Best for questions about:** Impact, data engineering, stakeholder collaboration, automation, self-initiative

### [Technical] SQL ETL Optimization — 40% Speed Gain
**Source:** Report #001 — Twitch (Amazon) — Data Scientist
**S:** Reporting across departments at CSUEB was slow, impacting decision-making for a 10,000+ client user base.
**T:** Improve data retrieval speed without disrupting existing workflows.
**A:** Developed and optimized SQL ETL processes; profiled query performance and implemented targeted indexing strategy.
**R:** 40% improvement in data retrieval speed; enabled real-time analytics at scale.
**Reflection:** Query profiling before optimization saved significant time — learned to measure first, then fix rather than assuming the bottleneck.
**Best for questions about:** Technical problem solving, SQL, data engineering, performance optimization

### [Healthcare ML] Patient Readmission Prediction — ROC-AUC 0.87
**Source:** Report #001 — Twitch (Amazon) — Data Scientist
**S:** A healthcare client needed to identify patients at risk of readmission within 30 days to enable early intervention.
**T:** Build a predictive model on 100,000+ anonymized clinical records with actionable clinical team output.
**A:** Engineered features from EHR data (lab results, diagnoses, medication history) using Pandas, SQL, NumPy; built XGBoost model; created Power BI dashboards for clinical teams.
**R:** ROC-AUC of 0.87; estimated 18% reduction in readmission rates.
**Reflection:** Should have shipped the Power BI dashboard to clinical teams earlier to gather feedback before final model tuning — stakeholder input would have shaped better feature engineering.
**Best for questions about:** ML end-to-end delivery, cross-functional collaboration, healthcare analytics, stakeholder communication
