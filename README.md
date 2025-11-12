# Ontario-Energy-Demand-Case-Study-2025-

## 📊 Project Overview
This project analyzes Ontario’s 2025 hourly electricity demand using **IESO demand data** and **Toronto weather data** from Environment Canada.  
The goal was to explore how **temperature and seasonality impact total energy demand** and translate those findings into actionable insights for operational planning, budgeting, and maintenance scheduling.

Built entirely in **Power BI**, this case study focuses on **data storytelling**, **analytical framing**, and **business interpretation**.

---

## 🧩 Dataset
- **Source 1:** Independent Electricity System Operator (IESO) – Hourly Ontario Demand  
- **Source 2:** Environment Canada – Toronto City Weather Station  
- **Timeframe:** January 1, 2025 – November 7, 2025  
- **Key Columns:**  
  - `Date`, `Hour`, `Ontario Demand`  
  - `Mean Temperature (°C)`, `CDD`, `HDD`

---

## 🧠 Analytical Framing
### What do we want to know?
- Total energy demand patterns across 2025.
- How temperature fluctuations affect energy use.
- The contribution of weather-dependent vs. fixed consumption.

### Why does it matter?
- Supports **budgeting**, **maintenance scheduling**, and **forecast planning**.
- Helps identify **peak months** and **baseline demand** for performance analysis.

### How was it measured?
- Total Demand (MW) = `SUM(OntarioDemand)`
- Baseline Energy = Lowest HDD and CDD month (September)
- Weather Normalized Load = Demand adjusted for HDD/CDD impact
- Variance = `[Total Demand] - [Baseline Energy]`

---

## 📈 Key Insights
- **June 24, 2025** recorded the **peak daily demand**, coinciding with a heatwave event.
- September served as the **baseline month** due to minimal heating and cooling demand.
- Strong correlation between **temperature extremes** and **load surges**.
- Seasonal trends indicate **predictable summer and winter peaks**.

---

## 🧩 Tools Used
- **Power BI** – Data modeling, DAX measures, and visualization  
- **Excel** – Pre-cleaning and validation  
- **Power Query** – ETL process  
- **Analytical Techniques:** Weather normalization, baseline comparison, demand variance, forecasting  

---

## 🗺️ Dashboard Overview
The Power BI dashboard includes:
- Total and average demand trends  
- Weather normalization and variance analysis  
- Seasonal breakdown of energy demand  
- Forecast visualization for November 2025 

---

## 💡 Recommendations
- Integrate **weather alerts** into forecasting models to improve operational readiness.  
- Differentiate **fixed vs. variable (weather-driven)** demand to refine budgeting accuracy.  
- Schedule **maintenance** during low-demand seasons.  
- Use **seasonal patterns** to anticipate and prepare for extreme weather-driven loads.

---

## 📜 Project Objective (Prompt)
> You are a data analyst supporting Ontario’s Energy & Sustainability team.  
> Leadership wants to understand electricity demand trends for 2025 to better prepare for November operations and inform next month’s budget planning.  
> Using IESO demand and Toronto weather data, analyse electricity demand and provide key insights and recommendations to support capacity planning and efficiency initiatives.

---

## 👤 Author
**Jesse Evwoh**  
Business Intelligence & Data Analyst  
📍 Toronto, ON  
🔗 [LinkedIn](https://www.linkedin.com/in/jesse-evwoh) | [Portfolio](https://jesseevwoh.netlify.app) | [GitHub](https://github.com/jesseevwoh)

---

## ⚙️ How to View
1. Download the `.pbix` file or open the PDF report.
2. 
---

## 📄 License
This project is for educational and portfolio purposes.  
Data sourced from publicly available repositories (IESO & Environment Canada).

