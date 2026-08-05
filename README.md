# 🚗 Automotive Market Performance Dashboard

> A comprehensive **Power BI dashboard** designed to analyze automotive market performance through vehicle pricing, performance metrics, fuel efficiency, market demand, and manufacturer comparisons. The solution combines an **Executive Overview Dashboard** with a **Drill-Through Analysis Dashboard**, allowing users to seamlessly transition from high-level business metrics to detailed vehicle-level insights for informed decision-making.

---

## 📖 Table of Contents

- [Project Overview](#-project-overview)
- [Dashboard Preview](#-dashboard-preview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Dataset Overview](#-dataset-overview)
- [Dashboard Pages](#-dashboard-pages)
- [Key Performance Indicators](#-key-performance-indicators)
- [Dashboard Features](#-dashboard-features)
- [Visualizations](#-visualizations)
- [Key Insights](#-key-insights)
- [Business Value](#-business-value)
- [Data Analysis Workflow](#-data-analysis-workflow)
- [Tools & Technologies](#-tools--technologies)
- [Repository Structure](#-repository-structure)
- [How to Use](#-how-to-use)
- [Skills Demonstrated](#-skills-demonstrated)
- [Future Improvements](#-future-improvements)
- [Disclaimer](#-disclaimer)
- [Author](#-author)
- [License](#-license)

---

# 📌 Project Overview

The **Automotive Market Performance Dashboard** is a Business Intelligence solution developed in **Microsoft Power BI** to provide comprehensive insights into the automotive industry. It enables users to evaluate vehicle pricing, manufacturer performance, fuel efficiency, speed, acceleration, mileage, and market demand through interactive visualizations.

The report is structured into two connected dashboards:

- **Executive Overview Dashboard** – Presents a high-level summary of key automotive performance metrics and market trends.
- **Vehicle Drill-Through Dashboard** – Provides detailed insights into individual vehicle models, enabling deeper exploration of specifications and performance indicators.

This project demonstrates advanced Power BI development techniques, including **drill-through navigation, DAX calculations, KPI reporting, interactive filtering, and data storytelling**.

---

# 🖼 Dashboard Preview

## Executive Overview Dashboard

![Cars-Dataset-Dashboard](GENERAL%20OVERVIEW%20DASHBOARD.PNG)
---

## Vehicle Drill-Through Dashboard

![Cars-Dataset-Dashboard](DRILL%20THROUGH%20DASHBOARD.PNG)

---

# 💼 Business Problem

Automotive manufacturers and dealerships manage large volumes of vehicle performance and market data. Without an integrated analytics platform, it becomes difficult to:

- Monitor overall market performance.
- Compare manufacturers based on performance and pricing.
- Identify high-performing vehicle brands.
- Analyze vehicle speed and acceleration.
- Evaluate fuel efficiency.
- Understand regional market demand.
- Compare vehicle popularity and mileage.
- Support pricing and production decisions.

This dashboard addresses these challenges by consolidating critical automotive metrics into an interactive and executive-friendly reporting solution.

---

# 🎯 Project Objectives

The dashboard aims to:

- Monitor overall automotive market performance.
- Compare vehicle brands based on key performance metrics.
- Analyze vehicle pricing and fuel efficiency.
- Evaluate speed and acceleration across manufacturers.
- Identify brands with the highest mileage.
- Understand regional market demand.
- Enable detailed vehicle-level drill-through analysis.
- Support strategic, data-driven decision-making.

---

# 📂 Dataset Overview

The dashboard analyzes automotive market data containing attributes such as:

- Vehicle Model
- Brand
- Manufacturer
- Country
- Vehicle Price
- Horsepower
- Performance Index
- Top Speed
- Acceleration
- Fuel Efficiency
- Fuel Type
- Transmission
- Mileage
- Market Demand
- Production Units
- Safety Rating

The dataset was cleaned, transformed, and modeled using **Power Query** before analysis.

---

# 📄 Dashboard Pages

## 1️⃣ Executive Overview Dashboard

The Executive Dashboard provides a comprehensive summary of market performance using interactive KPIs and analytical visualizations.

Users can monitor:

- Average Vehicle Price
- Performance Index
- Fuel Efficiency
- Mileage
- Brand Comparisons
- Market Demand
- Production Trends
- Speed and Acceleration

---

## 2️⃣ Vehicle Drill-Through Dashboard

The Drill-Through Dashboard allows users to explore detailed information for a selected vehicle model.

Information displayed includes:

- Vehicle Model
- Brand
- Country
- Fuel Type
- Safety Rating
- Top Speed
- Acceleration
- Fuel Efficiency
- Transmission Type
- Market Demand

This functionality enables users to move seamlessly from executive summaries to detailed vehicle analysis.

---

# 📊 Key Performance Indicators (KPIs)

## Executive Dashboard

| KPI | Value |
|------|-------:|
| 🚘 Average Vehicle Price | **262.07K** |
| 📈 Performance Index | **2.55M** |
| ⛽ Average Fuel Efficiency | **50.19K** |
| 🛣 Average Mileage | **126.49K** |

---

## Drill-Through Dashboard (Example: Porsche)

| KPI | Value |
|------|-------:|
| 🚗 Vehicle Model | **488 GTB** |
| 🏷 Brand | **Porsche** |
| 🌍 Country | **Asia** |
| ⛽ Fuel Type | **Diesel** |
| ⭐ Safety Rating | **★★★★☆** |
| 🚀 Top Speed | **273.70** |
| ⚡ Acceleration | **260.09K** |

---

# 🚀 Dashboard Features

- Executive KPI Cards
- Interactive Drill-Through Navigation
- Manufacturer Comparison
- Vehicle Performance Analysis
- Geographic Market Demand Mapping
- Safety Rating Overview
- Fuel Efficiency Analysis
- Speed & Acceleration Comparison
- Interactive Filtering
- Executive-Level Reporting

---

# 📈 Visualizations

## 📊 Executive KPI Cards

Displays high-level business metrics including:

- Average Vehicle Price
- Performance Index
- Fuel Efficiency
- Average Mileage

These KPIs provide a quick snapshot of the automotive market.

---

## 🚗 Brand Performance Comparison

A clustered column chart compares vehicle brands based on:

- Horsepower
- Performance Index

This visualization highlights manufacturers delivering superior performance.

---

## ⚖ Weight vs Speed by Brand

A scatter plot illustrates the relationship between vehicle weight and speed across manufacturers.

This helps identify performance characteristics and engineering trade-offs.

---

## 🚘 Popular Brands by Mileage

A horizontal bar chart ranks manufacturers according to mileage performance.

Useful for comparing vehicle efficiency and long-term value.

---

## 📈 Price Distribution by Market Demand

A donut chart displays the distribution of vehicle prices across different demand levels:

- High Demand
- Medium Demand
- Low Demand

This provides insights into consumer purchasing patterns.

---

## 🚀 Speed & Acceleration Analysis

A bar chart compares brands based on:

- Top Speed
- Acceleration

Helping users identify high-performance vehicles.

---

## 🏭 Production Units by Popularity

An area chart visualizes production output across different popularity categories.

This highlights how demand influences manufacturing volumes.

---

## ⛽ Fuel Efficiency by Brand

A combination chart compares fuel efficiency and pricing across manufacturers, enabling users to evaluate overall value.

---

## 🌍 Market Demand by Country

An interactive map displays the geographic distribution of automotive demand, helping identify key regional markets.

---

## 🚘 Vehicle Detail Card (Drill-Through)

The drill-through page presents detailed specifications for the selected vehicle, including:

- Model
- Brand
- Country
- Fuel Type
- Transmission
- Safety Rating
- Speed
- Fuel Efficiency

---

# 🔍 Key Insights

The dashboard enables users to identify several important business insights:

- The average vehicle price is approximately **262K**, indicating the overall market value.
- Performance metrics vary considerably across manufacturers, highlighting competitive differences.
- Some brands consistently outperform others in horsepower, speed, and acceleration.
- Mileage differs significantly among manufacturers, helping identify fuel-efficient vehicles.
- Vehicle demand varies across regions, providing opportunities for targeted market strategies.
- Drill-through analysis enables detailed evaluation of individual vehicle models, supporting informed product comparisons.

---

# 💼 Business Value

This dashboard supports strategic decision-making by enabling organizations to:

- Monitor automotive market performance.
- Compare manufacturers objectively.
- Evaluate vehicle performance metrics.
- Optimize pricing strategies.
- Understand regional market demand.
- Improve production planning.
- Support executive reporting.
- Enable data-driven business decisions.

---

# ⚙ Data Analysis Workflow

## 1. Data Collection

Collected automotive data including:

- Vehicle Specifications
- Manufacturer Information
- Performance Metrics
- Pricing
- Market Demand
- Fuel Efficiency
- Geographic Data

---

## 2. Data Cleaning

Performed using **Power Query**:

- Removed duplicate records.
- Corrected inconsistent values.
- Standardized manufacturer names.
- Handled missing values.
- Validated data quality.

---

## 3. Data Modeling

Created relationships between tables to support dynamic filtering, drill-through navigation, and efficient reporting.

---

## 4. DAX Measures

Custom calculations include:

- Average Vehicle Price
- Performance Index
- Average Fuel Efficiency
- Average Mileage
- Speed Metrics
- Brand Rankings
- Market Demand Indicators

---

## 5. Dashboard Development

The dashboard follows Business Intelligence best practices by emphasizing:

- Executive-friendly reporting
- Interactive exploration
- Consistent design language
- Clear visual hierarchy
- Effective analytical storytelling

---

# 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Data Cleaning
- Data Visualization
- Geographic Mapping
- Drill-Through Navigation
- Business Intelligence

---

# 📁 Repository Structure

```text
Cars-Dataset-Dashboard/
│
├── Cars dataset.pbix
├── GENERAL OVERVIEW DASHBOARD.PNG
├── DRILL THROUGH DASHBOARD.PNG
├── README.md
└── LICENSE
```

---

# 🚀 How to Use

### Clone the Repository

```bash
git clone https://github.com/Ita-Leonard/Automotive-Market-Performance-Dashboard.git
```

### Open the Dashboard

1. Install **Microsoft Power BI Desktop**.
2. Open the `.pbix` file.
3. Refresh the dataset if required.
4. Explore the Executive Dashboard.
5. Right-click a vehicle or brand and select **Drill Through** to view detailed vehicle insights.

---

# 💡 Skills Demonstrated

This project showcases expertise in:

- Business Intelligence
- Automotive Analytics
- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- KPI Development
- Drill-Through Navigation
- Geographic Analysis
- Performance Analytics
- Interactive Dashboard Design
- Data Storytelling
- Executive Reporting

---

# 📈 Future Improvements

Future enhancements may include:

- Real-time automotive market data integration.
- Electric vehicle (EV) performance analysis.
- Price forecasting using predictive analytics.
- Customer preference segmentation.
- Dealer performance analysis.
- Profit margin calculations.
- Mobile-responsive dashboard design.
- Deployment to Power BI Service with scheduled refresh.

---

# 📚 Disclaimer

This dashboard was developed for **educational**, **portfolio**, and **Business Intelligence demonstration** purposes. The data presented is intended to showcase analytical techniques and dashboard development skills and may not represent the performance of an actual automotive company or dealership.

---

# 👨‍💻 Author

## Leonard Ayamba Ita

**Data Analyst | Power BI Developer | Medical Laboratory Scientist**

I am passionate about transforming complex datasets into meaningful business insights through interactive dashboards, advanced analytics, and compelling data storytelling. My work focuses on building scalable Business Intelligence solutions that empower organizations to make informed decisions.

---

# 🤝 Connect With Me

- 💼 **LinkedIn:** *www.linkedin.com/in/leonard-ita*
- 🐙 **GitHub:** *https://github.com/Ita-Leonard*
- 📧 **Email:** *italeonard153@gmail.com*

---

# ⭐ Support

If you found this project useful, consider giving this repository a **⭐ Star**. Your support is greatly appreciated and helps showcase my work while encouraging the development of more impactful analytics projects.

---

# 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more information.

---

> **"Data is the new oil, but insight is the refined fuel."**
