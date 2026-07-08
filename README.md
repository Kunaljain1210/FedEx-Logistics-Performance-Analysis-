# 📦 FedEx Logistics Performance Analysis (EDA & Feature Engineering)

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Wrangling-orange.svg)](https://pandas.pydata.org/)
[![PowerBI](https://img.shields.io/badge/Power_BI-Dashboard-yellow.svg)](https://powerbi.microsoft.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 📌 Project Overview
Operating across more than 220 countries, FedEx manages millions of high-velocity shipments daily. In such a vast logistics environment, even minor operational friction can lead to massive revenue leakage and delayed Service Level Agreements (SLAs). 

This end-to-end data analytics project focuses on transforming raw, messy global shipment history into an interactive analytics pipeline. By executing deep **Exploratory Data Analysis (EDA)**, complex **Data Wrangling**, and **Logistics Feature Engineering**, this project uncovers systemic supply chain bottlenecks, isolates cost drivers, and evaluates vendor SLA compliance.

---

## 🎯 Business Objectives & Problem Statement
Variations in delivery timelines, opaque freight cost structures, and volatile vendor performance create operational inefficiencies that escalate expenses and hurt customer retention. 

This project solves these issues by establishing data-driven insights across four core pillars:
* **Service Reliability:** Measuring on-time delivery rates, tracking average lead times, and mapping exact bottleneck locations.
* **Cost Optimization:** Evaluating total freight spend, freight cost per kilogram ($/KG), and identifying high-cost vendor anomalies.
* **Operational Load Balancing:** Analyzing seasonal demand spikes, volume distribution, and route congestion to assist capacity planning.
* **Vendor & Route Management:** Scoring third-party fulfillment partners on delivery lag and price efficiency.

---

## 🛠️ Tech Stack & Toolkit
* **Language:** Python 3.8+
* **Data Wrangling & Engineering:** NumPy, Pandas
* **Advanced String & Data Cleaning:** Regular Expressions (`re`)
* **Visualization & Analytics:** Matplotlib, Seaborn, Power BI / Tableau

---

## ⚙️ Data Engineering & Feature Engineering Framework
Before conducting analysis, raw transactional shipment logs were cleaned and structured using an automated Python pipeline:

1. **Date Standardization:** Handled mixed-format text dates (e.g., handling missing inputs and irregular structures) using `pd.to_datetime(format='mixed', errors='coerce')`.
2. **Numeric Type Enforcement:** Extracted numeric values from raw data strings containing currencies, commas, or text qualifiers (such as weight and freight metrics) utilizing robust Regex patterns (`\d*\.?\d+`).
3. **Logistics Feature Engineering:** Engineered key supply chain metrics completely from scratch:
    * `lead_time`: Calculated total days elapsed between order placement and client delivery.
    * `on_time`: Binary flag tracking if actual delivery met or beat the `scheduled_delivery_date`.
    * `freight_per_kg`: Financial efficiency metric dividing total freight cost by shipment weight.

---

## 📊 Core KPIs Evaluated
The analysis engine outputs and tracks executive-level operational performance metrics:

* **Total Shipments Processed** (Volume Load)
* **Average Lead Time** (Cycle Speed)
* **On-Time Delivery Rate (OTDR %)** (SLA Accuracy)
* **Total Freight Cost** (Gross Financial Spend)
* **Average Freight Cost per KG** (Route Efficiency)

---

## 🚀 How To Run the Project

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/FedEx-Logistics-Performance-Analysis.git](https://github.com/YOUR_USERNAME/FedEx-Logistics-Performance-Analysis.git)
   cd FedEx-Logistics-Performance-Analysis
