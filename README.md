
# ⚡ Electric Vehicle Market Analysis Dashboard 

### 📊 End-to-End Data Analytics Project | Tableau • Excel • Data Visualization  

![Excel](https://img.shields.io/badge/Data-Excel-green)  
![Tableau](https://img.shields.io/badge/Visualization-Tableau-orange)  

---

## 📌 Project Description  

An end-to-end data analytics project focused on the Electric Vehicle (EV) market, analyzing a dataset of approximately **150,000 records** to uncover trends in **adoption, manufacturer performance, and technological shifts**.

This project demonstrates how raw CSV data can be transformed into a **fully interactive Tableau dashboard**, providing granular insights for business stakeholders.

---

## 🎯 Business Problem  

The EV industry and regulatory bodies need to answer critical questions such as:

- What is the overall market growth and acceptance of EVs since 2011?  
- What is the average electric range across manufacturers?  
- How is the market split between BEVs and PHEVs?  
- Which manufacturers and models are market leaders?  
- What percentage of vehicles are eligible for CAFV incentives?  

---

## 📊 Dataset Overview  

- **Records:** 150,000+ rows  
- **Features:** 17 columns  

### Includes:
- **Vehicle Info:** VIN (ID), Make, Model, Model Year  
- **Geographic Data:** City, State, Postal Code  
- **Technical Metrics:** EV Type (BEV/PHEV), Electric Range  
- **Regulatory Data:** CAFV Eligibility  

---

## 🛠️ Tech Stack  

| Layer | Tools Used |
|---------|-----------|
| Data Storage | Excel / CSV |
| Data Processing | Tableau (Logical & Physical Layers) |
| Visualization | Tableau Desktop / Tableau Public |

---

## 🔄 Project Workflow  

1. **Data Connection**  
   - Connected CSV dataset to Tableau using text file connectors  

2. **Data Walkthrough**  
   - Explored fields, data types, and key identifiers (Vehicle ID)  

3. **KPI Development**  
   - Created calculated fields for key performance metrics  

4. **Trend Analysis**  
   - Built area and line charts for year-over-year growth  

5. **Geographic Mapping**  
   - Visualized EV distribution using maps  

6. **Manufacturer Analysis**  
   - Implemented "Top N" filters for leading brands  

7. **Dashboard Design**  
   - Designed interactive dashboard using containers and clean UI  

---

## 🔧 Data Preparation  

- Applied filters for records between **2011–2024**  
- Created calculated fields:
  - **Total Vehicles:** `COUNTD([Vehicle ID])`  
  - **EV Type Split:** BEV vs PHEV distribution  
  - **Average Range:** Mean electric range  
- Standardized naming using aliases (e.g., BEV, PHEV)  
- Cleaned and validated dataset before visualization  

---

## 📸 Dashboard Preview  

<p align="center">
  <img src="Tableau Dashboard.png" width="900">
</p>

---

## 🔍 Key Insights  

- **Exponential Growth:** EV adoption peaked significantly in 2023  
- **Market Dominance:** Tesla accounts for over **52%** of total EVs  
- **BEV vs PHEV:** BEVs dominate with **78%**, PHEVs at **22%**  
- **Geographic Concentration:** Washington state leads EV adoption  
- **CAFV Eligibility:** ~41% vehicles qualify for incentives  

---

## 💡 Business Recommendations  

- **Manufacturer Strategy:** Shift focus toward BEVs to remain competitive  
- **Range Development:** Improve average EV range to match market leaders  
- **Regional Expansion:** Expand infrastructure in underdeveloped regions  
- **Regulatory Alignment:** Ensure CAFV eligibility compliance  
- **Strategic Planning:** Use data insights for long-term EV growth strategies  

---

## ▶️ How to Run  

1. Download the dataset (Electric Vehicle Population Data CSV)  
2. Open **Tableau Desktop** or **Tableau Public**  
3. Connect using **Text File → Select CSV**  
4. Apply filter: **Model Year ≥ 2011**  
5. Open the **Dashboard tab** to explore insights  

---

## 👨‍💻 Author  

**[Your Name]**  
Aspiring Data Analyst | Excel | Tableau  

---

## ⭐ If you found this useful  

Give this repo a ⭐ and share your feedback!
