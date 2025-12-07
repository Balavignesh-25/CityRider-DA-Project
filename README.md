# 🚍 CityRider — Urban Transport Data Analytics Project

## 📌 Project Overview
CityRider is an end-to-end Data Analytics project built using 40,000+ simulated transport trip records spanning 50 routes and 600+ stops.  
The analysis focuses on operational delays, demand variations, route efficiency, and weather impact to support data-driven decisions in urban mobility management.

This project includes:
- Data collection & preprocessing  
- Advanced cleaning and feature engineering  
- Exploratory data analysis (EDA)  
- Clustering and anomaly analysis  
- Multi-page Power BI dashboard  
- Insight generation and strategic recommendations  

---

## 🎯 Business Objective
To analyze and optimize transport performance by identifying:
- Delay patterns and congestion windows  
- Passenger load distribution  
- Route performance variability  
- Weather and anomaly impact  
- Opportunities for fleet and schedule optimization  

---

## ❓ Key Business Questions
1. Which routes and stops show the highest delays?  
2. What time periods exhibit peak congestion?  
3. How does weather affect delays?  
4. What factors drive severe delays?  
5. Which routes are underutilized or overburdened?  
6. What operational adjustments can improve reliability?

---

## 📊 Key Performance Indicators (KPIs)

| KPI                      | Value   |
|-------------------------|---------|
| **Total Trips**          | 40,000+ |
| **Average Delay (mins)** | 6.71    |
| **On-Time Reliability**  | 42.4%   |
| **Average Load Factor**  | 0.67    |
| **Severe Delay %**       | 5.8%    |

---

## 🧹 Data Cleaning & Feature Engineering

### ✔ Data Cleaning
- Missing timestamps treated using interpolation & forward fill  
- Duplicate and invalid entries removed  
- Outliers handled using statistical thresholds  
- Weather inconsistencies corrected  
- Route/stop/time columns standardized  

### ✔ Feature Engineering
More than 15 analytical features created:
- Delay (minutes)  
- Peak Hour Indicator  
- Load Factor  
- Stop Congestion Index  
- Route Efficiency Score  
- Weather Impact Score  
- Day of Week  
- Trip Reliability Category  

---

## 🔍 Exploratory Data Analysis (EDA)

Focus areas:
- Delay trends over days, weeks, and hours  
- Route-wise performance  
- Passenger load distribution  
- Weather impacts  
- Stop-level congestion patterns  
- Identification of anomaly days  

### Key Insights:
- Delay spikes at **08:00–10:00** and **17:00–19:00**  
- Rain & storms significantly increase delay times  
- Long-distance routes show higher delay variance  
- Overcrowded stops → corridor-level inefficiencies  

---

## 🧠 Advanced Analytics

### ✔ Route Clustering
K-Means clustering grouped routes into:
- **Excellent**
- **Moderate**
- **Poor**

Based on:
- Avg delay  
- Load factor  
- Distance  
- Trip reliability  

### ✔ Anomaly Detection
Identified deviation days caused by:
- Storms  
- Festivals  
- Demand surges  

---

## 📊 Power BI Dashboard

### **Page 1 — City Overview**
- KPIs  
- Delay trend  
- Day-wise analysis  
- Weather impact  

### **Page 2 — Route Performance Overview**
- Route ranking  
- Reliability comparison  
- Delay vs Distance map  
- Route clusters  

### **Page 3 — Route-Level Deep Dive**
- Selected route KPIs  
- Daily delay trend  
- Top delay-prone stops  
- Trip-level table  

**Dashboard file:**  
📁 `dashboard/CityRider.pbix`  
**Screenshots:**  
📁 `dashboard/Screenshots/`

---

## 📘 Insights Report
A structured 3-page professional PDF summarizing all findings.  

📁 `report/CityRider_Insights_Report.pdf`

---

## 🧩 Project Structure
```
CityRider-DA-Project/
│
├── data/
│   ├── transport_raw.csv
│   ├── transport_cleaned.csv
│   ├── transport_cleaned_template.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│
├── dashboard/
│   ├── CityRider.pbix
│   └── Screenshots/
│
├── report/
│   ├── CityRider_Insights_Report.pdf
│
├── README.md
└── LICENSE
```

---

## 🧭 Technology Stack
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Power BI:** KPIs, slicers, drillthrough, custom visuals  
- **Jupyter Notebook:** Cleaning, EDA, feature engineering  
- **GitHub:** Version control & project publishing  

---

## 🧩 Strategic Recommendations
- Add additional buses during peak hours  
- Introduce express services for long-distance routes  
- Reallocate fleet based on demand  
- Add buffer scheduling during adverse weather  
- Redesign poor-performing routes based on cluster insights  

---

## 🏁 Conclusion
CityRider delivers a comprehensive transport analytics pipeline—from data acquisition and preprocessing to visualization and operational recommendations.  
The project demonstrates analytical processing, dashboard creation, and strategic insight development.

---

