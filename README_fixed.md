# Vaccination Data Analysis and Visualization (Power BI)

## 📌 Overview
This repository contains a complete **Vaccination Data Analysis project**, integrating data cleaning (Python), structured storage (PostgreSQL on Neon), and interactive visualization (Power BI).  
The primary objective is to analyze **global vaccination coverage, disease incidence, and effectiveness**, and provide insights for **public health strategies, disease prevention, and policy-making**.

---

## 🎯 Objectives
- Understand **dose drop-off patterns** and **booster uptake** trends.  
- Compare **vaccination coverage vs. disease incidence** globally.  
- Visualize the **geographical spread** of diseases and vaccination performance.  
- Support **resource allocation** and **policy recommendations** with data-driven evidence.  

---

## 📊 Power BI Pages — Detailed Descriptions

### Page 1: Dose Drop-off & Booster Uptake
**Purpose:**  
To analyze vaccination coverage by dose schedules, regional disparities, and booster adoption trends over time.

**Key Visualizations & Metrics:**
- **KPI Cards:** Dose Drop-off %, Booster Uptake %, Avg. Schedule Rounds  
- **Bar Chart:** Avg Coverage % by Schedule Rounds (dose drop-off points)  
- **Horizontal Bar Chart:** Avg Coverage % by WHO Region (regional comparison)  
- **Line Chart:** Booster Uptake % by Year and WHO Region (temporal trends)  
- **Heatmap:** Disease vs WHO Region (performance across diseases)  

**Interactivity:**  
- Filters for **Year**, **Country**, **Disease**, and **Antigen**  
- Cross-highlighting between visuals  

**Dashboard Preview:**  
![Page 1 Dashboard](page 1 powerbi.jpg)  
*Identifies where vaccination drop-offs occur and tracks booster adoption trends.*

---

### Page 2: Coverage vs Incidence & Geographical Spread
**Purpose:**  
To compare vaccine coverage against disease incidence and visualize global disease burden.

**Key Visualizations & Metrics:**
- **KPI Cards:** Avg. Coverage %, Avg. Incidence Rate, Total Cases  
- **Scatter/Bubble Plot:** Coverage vs Incidence by Country  
  - Bubble size = Total Cases  
  - Bubble color = Disease  
- **Geographic Map:** Countries with Total Cases  
- **Combo Chart:** Vaccine Coverage % (bars) vs Disease Incidence (line) over Time  

**Interactivity:**  
- Filters for **Year**, **Country**, **Disease**, and **Antigen**  
- Tooltips on map and scatter bubbles  

**Dashboard Preview:**  
![Page 2 Dashboard](page 2 powerbi.jpg)  
*Shows correlation between vaccination coverage and disease incidence, plus global case distribution.*

---

## 🔎 Navigation Guide
1. Use **slicers (filters)** at the top of each page to refine by **Year**, **Country**, **Disease**, or **Antigen**.  
2. Click on visuals (bars, bubbles, regions) to **cross-filter other charts**.  
3. Hover over map points or scatter bubbles for detailed stats.  
4. Switch between **Page 1** and **Page 2** using report tabs at the bottom.  

---

## 📂 Data Sources
Data was cleaned, validated, and stored in PostgreSQL. The following datasets were used:
- **Coverage Data:** vaccination coverage by antigen, country, year  
- **Incidence Rate Data:** disease incidence per population  
- **Reported Cases:** annual disease case counts by country  
- **Vaccine Introduction Data:** rollout timelines across WHO regions  
- **Vaccine Schedule Data:** schedule rounds and target populations  

👉 [Dataset Reference (Google Drive)](https://drive.google.com/drive/folders/1YQ6mNrZCrlEeBP4GH3VnLBNXb7OBD4tf?usp=sharing)

---

## 🛠 Tech Stack
- **Python (pandas, pandera, SQLAlchemy):** Data cleaning, validation, and upload  
- **PostgreSQL (Neon):** Structured storage for cleaned datasets  
- **Power BI:** Interactive dashboards and visual storytelling  

---

## 🤝 Contributors
Contributions are welcome!  

**Guidelines:**
1. Fork the repository and create a feature branch.  
2. Document any new Power BI visuals or SQL queries added.  
3. Ensure filters and slicers remain consistent across pages.  
4. Submit a pull request with clear descriptions of changes.  

---

## 📜 Changelog / Version History
- **v1.0 (Sept 2025):**  
  - Page 1 (Dose Drop-off & Booster Uptake)  
  - Page 2 (Coverage vs Incidence & Geographical Spread)  
  - PostgreSQL integration with Neon  
  - Documentation and dataset references  

Future updates may include:
- Page 3: **Vaccine Effectiveness Analysis**  
- Expanded KPIs vs WHO targets  

---

## 📌 License
This project is shared for **educational and research purposes** in public health analytics.  
