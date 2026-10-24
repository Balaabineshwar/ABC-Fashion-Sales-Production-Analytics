# ABC Fashion Pvt. Ltd. - Executive Sales & Production Performance Dashboard

An executive-level Power BI data analytics solution developed for ABC Fashion Pvt. Ltd., a women's apparel manufacturer in South India, to address rising inventory costs, product underperformance, and regional distributor stock shortages.

---

## 🚀 Project Overview
This project builds a comprehensive, single-page executive command center that unifies financial sales trends with manufacturing output and inventory variances. It bridges time-sensitive retail transactions with overall factory production baselines to support strategic decision-making.

---

## 📊 Key Dashboard Features & Layout
* **Executive Title Banner:** Clean uppercase branding and scope definition.
* **Vertical Left-Side KPI Panel:** Custom icon cards tracking Total Revenue (`4.92M`), Total Qty Sold (`8K`), Total Produced (`95K`), and Fulfillment Rate (`92.83%`).
* **Monthly Revenue Line Chart:** Tracks revenue growth and sales momentum from January through June.
* **Production vs. Sales Bar Chart:** Highlights the gap between factory manufacturing output and customer purchases by product style.
* **Distributor Performance Column Chart:** Evaluates regional sales volume distribution across wholesale partners.
* **Production Variance Matrix Table:** Provides a detailed size-and-style audit breaking down planned vs. produced quantities and variances.
* **Interactive Slicers:** Top-header dynamic filters for Month and Product.

---

## 🛠️ Tech Stack & Architecture
* **Tool:** Power BI Desktop
* **Data Modeling:** Star Schema architecture with centralized bridging and relationship cross-filtering.
* **DAX & Calculations:** Custom measures (`CALCULATE`, `SUM`, `FORMAT`, context modifiers).

---

## 📁 Repository Structure
* `/dataset` - Raw transactional and master data files.
* `/dashboard` - Power BI Desktop source file (`.pbix`).
* `/Presentation` - Executive presentation slides (`.pptx`).

---

## 📈 Business Recommendations
1. **Re-align Production Targets:** Adjust future manufacturing batches to match real market demand and curb holding costs.
2. **Optimize Regional Stock:** Monitor distributor velocity to eliminate regional stock shortages.
3. **Monitor Style-Level Variances:** Use the size matrix to correct manufacturing imbalances prior to batch production.
