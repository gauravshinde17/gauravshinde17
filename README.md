# Hi, I'm Gaurav Shinde 👋

Data Engineer / Analytics Engineer building SQL-first pipelines and warehouses on Azure, Databricks, and Snowflake — from raw ingestion through to production-ready dashboards.

I design and build end-to-end data systems: ingestion pipelines, layered warehouse architectures (Bronze/Silver/Gold, star schema), and the analytical layer on top — with an emphasis on pipeline infrastructure over one-off analysis.

---

## 🛠 Tech Stack

| Category | Tools |
|---|---|
| Languages | Python, SQL (MySQL) |
| Cloud & Platforms | Azure (ADF, ADLS Gen2, Synapse Analytics, Key Vault), Microsoft Fabric, AWS (Glue, Lambda, S3) |
| Processing | Apache Spark / PySpark, Azure Databricks, Apache NiFi |
| Warehousing | Snowflake, star schema / dimensional modeling, SCD Type 2 |
| Orchestration & Infra | Azure Data Factory, Docker, Terraform |
| BI & Visualization | Power BI (DAX, Power Query, Direct Lake), Tableau, Excel |

---

## 📊 Featured Projects

### 🔹 Version-Aware Earthquake Event Data Platform
Production-style Azure data platform for USGS earthquake events, solving for mutable source records with an append-only, version-aware history layer (deterministic version IDs, `is_latest` flags, freshness SLA tracking) rather than a simple overwrite pipeline.
**Workflow:** USGS FDSN Event API → Azure Data Factory → ADLS Gen2 (Bronze) → Azure Databricks/PySpark → Silver Delta → Gold Delta → Azure Synapse SQL serving layer → Power BI.

### 🔹 LLM Governance & Cost Benchmarking Framework
SQL-first analytics engineering project benchmarking 5 LLM providers across 3 fintech workloads for cost efficiency, hallucination risk, and misallocation impact. 3-layer SQL transformation architecture, 21 models, 104 tests, 6 Power BI dashboards.
> Core finding: The biggest problem is not the vendor. It is the allocation policy.

### 🔹 PhonePe Pulse – Fintech Performance Analytics
End-to-end fintech analytics warehouse (2018–2024) analyzing digital adoption, merchant monetization, and regional performance. Star schema with 22 named SQL views across staging/dimension/fact layers, Power BI dashboards.

### 🔹 Real-Time Streaming Pipeline – NiFi to Snowflake
Streaming pipeline flowing generated data through Apache NiFi (Docker on EC2) → S3 → Snowpipe → Snowflake Stream/Task, maintaining full SCD Type 2 history on the target table.

### 🔹 Spotify ETL Pipeline
Serverless ETL pipeline (AWS Lambda + S3 + Snowpipe) landing Spotify data into a Snowflake `MUSIC_CATALOG` warehouse (Artists, Albums, Tracks). Includes a parallel AWS Glue/PySpark batch variant.

---

## 📈 Additional Analytics Projects

- **Aurix Motors** – EV manufacturer performance analysis ($26B revenue, 676K units) across revenue, cost, operations, and customer satisfaction in Power BI
- **Real Estate Market Analysis** – 15+ page Power BI project on pricing efficiency and agent/office performance across ~10,000 Austin/Dallas/Houston listings
- **Global Terrorism Trends** – 5-decade (1970–2020) exploratory analysis of attack patterns and geographic distribution in Python and Tableau
- **AQI Chronicle** – Recomputed AQI from raw EPA concentrations using official breakpoint formulas across 47 U.S. states, 1.7M records
- **Airbnb Impact of Regulations** – Regulatory impact on pricing and listing volume across 250,000+ listings and 5M+ reviews in 10 global cities
- **Music Retail Store** – SQL-only analysis of sales performance, genre preferences, and customer behavior
- **Pizza Sales Dashboard** – Excel pivot-table dashboard on order patterns and peak-hour trends

---

## 🔗 Connect With Me

- 📧 Email: gauravshinde0363@gmail.com
- 🔗 LinkedIn: https://www.linkedin.com/in/gaurav-shinde-897036306/
- 📊 Tableau Public: https://public.tableau.com/app/profile/gauravshinde17
- 🧠 Kaggle: https://www.kaggle.com/gauravshinde017

---

*Actively building toward production-grade data engineering — pipelines, warehouse design, and scalable processing on Azure and Fabric.*
