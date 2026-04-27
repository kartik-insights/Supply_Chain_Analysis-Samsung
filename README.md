# Samsung Supply Chain: Strategic Analytics Suite

## 🌐 Project Philosophy
This **Power BI** ecosystem was developed to bridge the visibility gap across Samsung's global supply chain. By synthesizing disparate data streams into a centralized source of truth, this project transitions the supply chain from a reactive cost center to a proactive strategic asset.

## 🛠 Technical Architecture
The backend is built on a high-performance **Star Schema** data model designed for low-latency filtering across millions of records.

* **Logic Layer:** Advanced **DAX** implementation for time-intelligence (YoY Growth, Rolling Averages) and dynamic KPI scaling.
* **Data Orchestration:** Managed through Power Query for automated ETL, ensuring data integrity from procurement to final shipment.
* **Relational Schema:** Five central **Fact Tables** (`Sales`, `Production`, `Procurement`, `Shipment`, `Inventory`) linked to shared **Dimension Tables** for seamless cross-filtering.

---

## 📈 Executive Insights & Modules

### 1. Revenue & Market Dynamics (Sales)
Focuses on the financial health of the supply chain. Beyond high-level revenue tracking, it evaluates the **elasticity of profit margins** against discount strategies and monthly demand shifts.

### 2. Operational Integrity (Production)
A deep dive into manufacturing health. This module isolates **Defect Rate %** and **Batch Efficiency** to pinpoint specific facilities or production lines that require process optimization.

### 3. Strategic Sourcing (Procurement)
Evaluates the efficiency of the "upstream" chain. It tracks **Vendor Lead Times** and **Cost-per-Unit** volatility to ensure procurement maintains a high Supplier Quality Score.

### 4. Fulfillment & Logistics (Shipment)
Analyzes the "last mile" of the supply chain. Key focus areas include **On-Time Delivery (OTD)** metrics and a **Delay Reason Analysis** to distinguish between internal bottlenecks and external logistics failures.

### 5. Vendor Ecosystem (Supplier Performance)
A comprehensive scorecard system that tiers suppliers based on reliability and geographical distribution, ensuring a diversified and low-risk sourcing strategy.

---

## 🔬 Core Metric Glossary
* **Profitability:** Net Revenue, Margin %, and Cost Ratios.
* **Quality Control:** Defect Rates and Supplier Quality Grades.
* **Agility:** Lead Times and On-Time Delivery performance.
* **Freight Efficiency:** Cost per Kg and Shipment Volume trends.

---

## 🚀 The Roadmap
* **Predictive Layer:** Implementing ML-driven demand forecasting to reduce inventory carrying costs.
* **Live Stream:** Shifting to DirectQuery for real-time warehouse monitoring.
* **Automated Governance:** Deployment of Data Alerts to notify stakeholders the moment a KPI (like Defect Rate) exceeds the tolerance threshold.
