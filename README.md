# Supply_Chain_Analysis-Samsung


## 🚀 Project Overview
This project is a comprehensive **Samsung Supply Chain Analytics Dashboard** built using **Power BI**. It provides an end-to-end view of the supply chain lifecycle, integrating data from Sales, Production, Procurement, Shipment, and Supplier Performance to drive data-driven decision-making.

The dashboard is designed to:
* **Track key KPIs** in real-time.
* **Identify inefficiencies** across the production and logistics value chain.
* **Improve operational decisions** through interactive data exploration.
* **Optimize performance** by visualizing trends and outliers.

---

## 📌 Dashboard Pages

### 🟦 1. Sales Overview
* **Financial Metrics:** Gross Revenue, Net Revenue, Profit, Profit Margin %, and Discount Rate %.
* **Trends:** Monthly Sales Trend and Product-wise Sales Analysis.

### 🟩 2. Production Analysis
* **Volume & Quality:** Total Production Quantity, Defective Units, and Defect Rate %.
* **Efficiency:** Production Efficiency and Batch-wise Production Analysis.
* **Facility:** Performance benchmarking across different manufacturing units.

### 🟨 3. Procurement Insights
* **Cost Analysis:** Total Procurement Cost and Cost per Unit.
* **Efficiency:** Average Lead Time and Purchase Order Analysis.
* **Quality:** Supplier Quality Score integration.

### 🟥 4. Shipment & Delivery
* **Reliability:** On-Time Delivery % and Delayed Shipments.
* **Logistics Costs:** Cost per Shipment and Cost per Kg.
* **Root Cause:** Delivery Trends and Delay Reason Analysis.

### 🟪 5. Supplier Performance
* **Scorecards:** Supplier Quality Score and Average Lead Time.
* **Segmentation:** Supplier Tier Analysis and Country-wise Distribution.
* **Ranking:** Top & Bottom performing suppliers.

---

## 📊 Key KPIs Tracked
| Category | KPI |
| :--- | :--- |
| **Sales** | Gross Revenue, Net Revenue, Profit, Profit Margin %, Discount Rate % |
| **Operations** | Cost Ratio %, Production Efficiency %, Defect Rate % |
| **Logistics** | On-Time Delivery %, Cost per Kg |

---

## 🛠 Tools & Technologies
* **Power BI:** For data visualization and dashboard creation.
* **DAX (Data Analysis Expressions):** Used for complex measures and calculated columns.
* **Data Modeling:** Implemented a **Star Schema** for optimized query performance.
* **Power Query:** For ETL (Extract, Transform, Load) processes.

---

## 🗂 Dataset Structure
The project utilizes a robust star schema with the following tables:

### Fact Tables
* `fact_inventory`
* `fact_sales`
* `fact_production`
* `fact_procurement`
* `fact_shipment`

### Dimension Tables
* `dim_facility`
* `dim_product`
* `dim_customer`
* `dim_supplier`
* `dim_date`

---

## 💡 Key Insights Derived
* **Production:** Identified specific production batches with abnormally high defect rates, suggesting equipment maintenance needs.
* **Supplier Impact:** A direct correlation was found between low supplier quality scores and delivery performance delays.
* **Profitability:** Discount strategies were found to have a disproportionately high impact on net profit margins in certain regions.
* **Logistics:** Shipment delays are primarily driven by specific logistics inefficiencies rather than production bottlenecks.

---

## 📈 Future Improvements
* **Forecasting:** Integrate Machine Learning (Python/R) for demand and inventory forecasting.
* **Real-time Integration:** Move from scheduled refreshes to DirectQuery for live data streams.
* **Advanced Analytics:** Implement drill-through pages for granular root-cause analysis.
* **Alerting:** Set up Power BI KPI alerts to notify stakeholders when defect rates or delays exceed thresholds.
