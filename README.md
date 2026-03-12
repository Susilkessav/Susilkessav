# Hey, I'm Susil 👋
 
I'm a grad student at **Northeastern University** finishing up my MS in Data Analytics Engineering (Dec 2025). I spend most of my time building data pipelines, ML infrastructure, and occasionally breaking into boxes on Hack The Box.
 
Right now I'm looking for full-time roles in **Data Engineering**, **AI/ML Engineering**, or **Data-Platform SWE** — basically anything where I get to build systems that move, transform, or learn from data at scale.
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/susilkessav)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:seshadribhuvaneswa.s@northeastern.edu)
 
---
 
## What I've been building
 
### RAG Chatbot — Amazon Automotive Reviews
`LangChain` `ChromaDB` `SentenceTransformers` `Airflow` `Langfuse` `RAGAS` `FastAPI` `Docker`
 
An LLM-powered Q&A system over 2M+ automotive reviews. The pipeline does query decomposition, retrieves context from ChromaDB vectors, and synthesizes answers through agent-style tool calls. Hits ~90% faithfulness on RAGAS at under 2 seconds. I wired up Langfuse to track retrieval drift and latency so I could actually debug prompt issues instead of guessing.
 
### Predictive Analytics Pipeline — Telemetry Data
`PySpark` `Spark SQL` `dbt` `XGBoost` `MLflow` `Delta Lake` `Kafka`
 
Distributed feature engineering across 5+ telemetry sources and 10M+ records. The interesting part was getting lag-aware joins right and enforcing dbt contracts across 20+ feature tables so three downstream ML teams didn't run into training-serving skew. Medallion Architecture on Delta Lake brought compute costs down 45%. Best model hit 0.73 ROC-AUC with a ~20% precision@k lift.
 
### Task & Workflow Management Platform
`FastAPI` `React` `PostgreSQL` `Redis` `JWT/RBAC` `Docker` `GitHub Actions` `pytest`
 
Full-stack app with 20+ REST endpoints, auth, and role-based access. The fun challenge was schema optimization and adding Redis caching to get API latency down ~35% under real read/write loads. CI/CD pipeline with 88% test coverage — deploys don't scare me.
 
### IoT Health Monitoring Platform
`Kafka` `MySQL` `PostgreSQL` `Great Expectations` `Tableau`
 
ETL workflows processing 120k+ IoT sensor records from 12 device streams. I engineered time-series HRV features (RMSSD, SDNN, circadian rhythm) that fed into mental health analytics models. Built 12+ Tableau dashboards so analysts could actually correlate stress biomarkers with sleep patterns instead of staring at raw CSVs.
 
---
 
## Tech I reach for
 
**Pipelines & Platforms** — PySpark · Databricks · Azure Synapse · Delta Lake · dbt · Airflow · Kafka · Great Expectations  
**ML & LLMs** — PyTorch · TensorFlow · Scikit-Learn · XGBoost · LangChain · RAG · LoRA/PEFT · ONNX · MLflow · Langfuse  
**Cloud & Infra** — AWS (S3, SageMaker, Lambda) · Azure · Docker · Kubernetes · GitHub Actions · Terraform  
**Languages** — Python · SQL · Java · JavaScript · C++ · Bash  
**Databases** — PostgreSQL · MongoDB · Snowflake · BigQuery · Redshift · ChromaDB · FAISS
 
---

 
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=susilkessav&show_icons=true&theme=default&hide_border=true&count_private=true" alt="GitHub Stats" height="150" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=susilkessav&hide_border=true" alt="GitHub Streak" height="150" />
</p>
 
