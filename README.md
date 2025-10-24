# Insurance Risk & Claims Analysis Dashboard

## 📄 Business Requirement

An insurance company needed to better understand its policyholder base and claim patterns to make data-driven business decisions. Their key challenge was that policy and claims data were scattered across multiple sources, making it difficult for stakeholders to track performance and identify trends.

The solution was to create a centralized, interactive dashboard in Power BI to provide a clear, consolidated overview of all key metrics.


## 🚀 Key Features

The dashboard is built around two key dynamic measures: **Total Claim Amount** and **Total Policies**. It provides a high-level summary via KPIs and a deep-dive analysis through various charts.

### 📈 Key Performance Indicators (KPIs)

* **Total Policies:** Measures the size of the active customer base.
* **Total Claim Amount:** Tracks the overall financial impact of claims.
* **Claim Frequency:** Analyzes how often claims are being made.
* **Average Claim Amount:** Assesses claim severity and potential risk exposure.
* **Gender-wise Total Policies:** Understands customer distribution across genders for better segmentation.

### 🎨 Key Visualizations

To allow stakeholders to explore patterns, relationships, and anomalies, the following charts were included:

* **By Car Use (Donut Chart):** Analyzes policy distribution and claim amounts based on car use (e.g., personal, commercial).
* **By Car Make (Bar Chart):** Identifies which car brands have higher policies and claims.
* **By Coverage Zone (Donut Chart):** Evaluates policies and claims by geographic zones for regional risk analysis.
* **By Age Group (Frequency Chart):** Assesses policyholders’ age distribution and identifies which age brackets file more claims.
* **By Car Year (Area Chart):** Analyzes how the car’s age (year of manufacture) impacts policy counts and claim amounts.
* **By Kids Driving (Ribbon Chart):** Compares the impact of young drivers in households on policy count and claim amounts.
* **By Education (Pie Chart):** Understands how education levels correlate with insurance policy adoption and claims.
* **By Education & Marital Status (Matrix Heat Grid):** Explores the combined effect of education and marital status on policies and claims, highlighting customer profiles.

---

## 🛠️ Tech Stack

* **Data Consolidation:** (Data from multiple sources)
* **Data Modeling & Visualization:** **Power BI**
* **Data Analysis:** **DAX** (Data Analysis Expressions) for creating all key measures and KPIs.
