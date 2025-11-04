# ☁️ Automated ETL Intelligence & Unified Data Cloud Framework  
**Repository:** `automated-etl-intelligence-framework`  
**Powered by:** Databricks | BigQuery | Power Automate | PyMC | MLflow | Supermetrics | PMG Analytics  

![ETL Cloud Framework Pipelines](docs/ETL_Cloud_Framework_Pipelines.png)

> **From Raw Data to Real-Time Intelligence**  
> A scalable, transparent, and automated architecture uniting marketing, media, and business data across Databricks, BigQuery, and Power Automate — delivering live insights, cross-channel ROI, and decision-ready analytics.

---

## 🧩 Overview
The **Automated ETL Intelligence Framework** is a **repeatable, cloud-native data ecosystem** designed to ingest, transform, and serve marketing and business data from dozens of platforms into a single, transparent analytics layer.  

This framework unifies **Supermetrics API data**, **SFTP publisher feeds**, **sales and business results**, and **ad platform data (Meta, Google, Apple, TikTok, OOH, Radio, TV, etc.)** into a consistent, governed structure.  
It empowers analytics, marketing, and strategy teams to operate from one version of truth — with **automated refreshes, lineage tracking, and ready-to-use intelligence models**.

---

## 💡 Key Framework Layers

| Stage | Function | Description |
|--------|-----------|-------------|
| **Source** | 🔗 **Multi-Channel Data Inputs** | Integrates digital, offline, and business data sources including **Google Ads, Meta, TikTok, TV, OOH, Radio, Sales Data, and Business KPIs**. |
| **Ingest** | ☁️ **Automated Data Acquisition** | Uses **Supermetrics** and **SFTP** pipelines to pull campaign, spend, and results data into Databricks **Delta Lake**. Power Automate triggers ensure time-aligned data refreshes and health checks. |
| **Transform** | 🧠 **Data Engineering & ML Pipelines** | Databricks **Auto-Loader**, **Delta Live Tables**, and **event-triggered queries** manage schema evolution, cleansing, and enrichment. Transformation logic written in **Python, PySpark**, and orchestrated through **Databricks Workflows**. |
| **Query & Process** | ⚙️ **Data Science, ML & Governance** | Unified under **Unity Catalog** for governance. **PyMC + MLflow** enable real-time and batch **Marketing Mix Modeling (MMM)**, attribution, and forecasting. |
| **Serve** | 🧩 **Model Serving & Data Warehousing** | Outputs delivered to **BigQuery** and **Databricks SQL** for cross-platform analysis. **Delta Sharing** and **HighTouch** power data activation and segmentation pipelines. |
| **Consumer / Output** | 📊 **Real-Time Insights & Activation** | **Power BI dashboards** deliver live spend, ROI, and performance tracking; **Teams / Power Automate alerts** notify stakeholders instantly; publishers use data for **custom audience building** and **creative personalisation**. |

---

## 🧠 Why It Matters
This framework creates a **unified, intelligent foundation** for analytics and marketing optimisation.  
By automating every stage of the data journey, it eliminates manual handling, ensures full transparency, and scales effortlessly across multiple clients.

**Business Value:**
- 🔄 **End-to-end automation** — from ingestion to insight delivery  
- 🌍 **Cross-channel visibility** — unify digital, offline, and business KPIs  
- 🧮 **Model-ready data** — built for MMM, forecasting, and attribution models  
- ⚡ **Real-time refresh matrix** — transparent tracking of all data flows  
- 🧱 **Reusable components** — scalable across PMG client portfolios  
- 🧩 **Data governance & compliance** — via Unity Catalog and Delta Lake lineage  
- 📈 **Actionable insights** — Power BI dashboards and Teams alerts drive faster optimisation  

---

## 🖼️ Framework Visual

![ETL Cloud Framework Pipelines](docs/ETL_Cloud_Framework_Pipelines.png)

**Diagram:** `ETL_Cloud_Framework_Pipelines.png`  
This image visualises the entire end-to-end architecture:
- **Left (Source):** Media and performance data from Apple, Meta, Google Ads, TikTok, Bing, TV, Radio, OOH, Sales, and Business Results.  
- **Middle (Databricks):** Unified ingestion, transformation, governance, and orchestration — including **Delta Live Tables**, **Unity Catalog**, and **PyMC** model training.  
- **Right (Output):** **Power BI**, **Teams**, and publisher pipelines providing live insights, audience building, and automated performance reporting.

---

## 🧩 Architecture Components

| Layer | Tools & Tech | Key Function |
|-------|---------------|---------------|
| **Data Ingestion** | Supermetrics, SFTP, Power Automate | Automated retrieval of structured and unstructured data from multi-channel sources |
| **Data Engineering** | Databricks Auto-Loader, Delta Live Tables, PySpark | Event-driven ETL, schema evolution, and validation |
| **Storage** | Delta Lake (Bronze/Silver/Gold), Google BigQuery | Clean, scalable, versioned storage for analytics and ML |
| **Data Science & ML** | MLflow, PyMC, Python | Real-time and batch MMM, ROI modelling, forecasting |
| **Data Serving** | BigQuery SQL, Databricks SQL, Delta Sharing | High-speed querying, model output serving, and external data sharing |
| **Analytics & Activation** | Power BI, HighTouch, Power Automate, Teams | Real-time dashboarding, alerting, and audience activation |

---

## 🚀 Framework Benefits

| Business Impact | Description |
|------------------|-------------|
| **Speed** | Reduce manual data collection time from days to minutes |
| **Transparency** | Complete lineage visibility through Unity Catalog and Delta Lake |
| **Scalability** | Reusable architecture for multi-client and multi-region deployment |
| **Trust** | Live validation ensures data accuracy and governance compliance |
| **Collaboration** | Unified ecosystem for data engineers, analysts, and marketers |
| **Performance** | Immediate access to model-ready data and live performance insights |

---

## 🔧 Example Use Cases
- **Real-Time MMM** — Continuous Marketing Mix Modeling with PyMC and MLflow tracking  
- **Cross-Channel ROI Analysis** — Combine spend, results, and conversion data for actionable ROI  
- **Automated Media Planning** — Sync live MMM outputs to media planning tools via Delta Sharing  
- **Competitor Intelligence** — Integrate external subscription APIs for live benchmarking  
- **Sentiment Analysis Integration** — Layer customer and social data into campaign performance  

---

## 👥 Contributors
| Name | Role | Contact |
|------|------|----------|
| Kevin Killion | Lead Data Analyst & AI Engineer | [LinkedIn](https://linkedin.com/in/kevin-killion) |
| PMG Analytics Team | Data Science & Automation | internal@pmg.com |

---

## 📜 License
MIT License © 2025 Principle Media Group  
_“The best time to automate was yesterday. The second best time is now.”_
