## 💧 Kansas Water Quality Analysis & Dashboard
### 📌 Project Overview
This project analyzes Kansas water quality using data from the Water Quality Portal (WQP) and other socio-economic datasets. The goal is to create an interactive Power BI dashboard that helps users explore water quality trends, visualize socio-economic factors, and understand regional variations in water conditions.

The analysis focuses on:

Visualizing water quality metrics across Kansas counties.

Exploring socio-economic correlations, including income levels and water quality.

Identifying trends in water characteristics (e.g., pH, phosphorus, nitrogen levels).

Providing an interactive, user-friendly dashboard for analysis and decision-making.

### 📂 Data Source
The dataset combines:

Water Quality Portal (WQP) – Provides water quality data collected by the USGS & EPA.

IRS Tax Statistics (2021) – Used for socio-economic insights.

### 📊 Data & Methodology

Dataset Features: Water quality characteristics, collection sites, income levels, geographic attributes.

Data Cleaning:

Filtered Kansas-specific water quality data (2018-2023).

Merged IRS income data at the county level.

Removed missing values (173,140 records analyzed).

Exploratory Data Analysis (EDA):

Identified water quality trends & socio-economic disparities.

Mapped high/low-income counties & their water characteristics.

Analyzed correlations between income & water quality.

### 📊 Power BI Dashboard
🔗 [View the Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzk5ZGFlMDItYzliMS00MWU4LWE3MmUtYjgyYzU1OTY0NzM0IiwidCI6IjExMTNiZTM0LWFlZDEtNGQwMC1hYjRiLWNkZDAyNTEwYmU5MSIsImMiOjN9)

### Visualizations Included

✔ Choropleth Map (Income by County)

✔ Choropleth Map (Water Quality by County)

✔ Scatter Plot (Income vs. Water Quality Correlation)

✔ Trend Analysis (2018-2023 Water Quality Data)

### 🚀 Technologies Used

Data Processing: Python (Pandas, NumPy), Excel

Data Visualization: Power BI, Matplotlib, Seaborn

Interactive Dashboard: Power BI

### 📢 Key Findings

Higher-income counties tend to have better water quality, but data gaps exist.

Some counties lack sufficient water quality data, making analysis difficult.

Correlation between income & water quality varies by region, with some counties showing strong relationships.

Filtering water quality data to 50 key characteristics helped focus the analysis.

### 📌 Future Work

🔹 Expand the dataset with historical water quality trends.

🔹 Use machine learning models to predict water contamination risks.

🔹 Integrate more socio-economic variables (e.g., population density, land use).
