# 📊 Retail Sales & Profitability Analytics Dashboard

## 🎯 Objective
This project analyzes a dataset of 8,300+ retail transactions to uncover actionable business insights regarding regional performance, product profitability, and customer segmentation. The goal was to transform raw, inconsistent data into a fully interactive, production-ready Business Intelligence (BI) dashboard.

## 🛠️ Tech Stack & Tools
* **Data Cleaning & Preprocessing:** Microsoft Excel 
* **Data Modeling & Calculations:** DAX (Data Analysis Expressions)
* **Data Visualization & UI Design:** Power BI
* **Version Control:** Git/GitHub

## 🧹 Data Engineering & Cleaning
Before visualization, the raw dataset required rigorous sanitization to ensure accurate mathematical aggregations:
* **Date Parsing:** Engineered workarounds to bypass regional system restrictions, successfully converting stubborn text strings into valid `MM/DD/YYYY` date types for accurate time-series analysis.
* **Missing Value Handling:** Identified and resolved null values within the `Product Base Margin` column using statistical averages to maintain dataset integrity.
* **Validation:** Verified 0 duplicate records across unique `Order ID` and `Row ID` primary keys.

## 🏗️ Dashboard Architecture & UI/UX
The dashboard was designed with a focus on user experience, treating the canvas much like a front-end interface:
* **Dynamic State Filtering:** Implemented cross-filtering across all visual components, allowing users to click any metric (e.g., "Corporate" segment) to instantly dynamically update the entire dashboard state.
* **Visual Hierarchy:** Engineered a top-level KPI header row for immediate high-level insights (Total Sales, Total Profit), flowing down into granular categorical breakdowns.
* **Interactive Controls:** Deployed customized dropdown slicers to give end-users total control over regional and priority-based data exploration.

## 💡 Key Business Insights
1. **Top Performing Region:** The **West** region leads overall sales by a significant margin.
2. **Most Profitable Category:** While Office Supplies drives the highest transaction volume, **Technology** generates the highest total profit.
3. **Revenue Drivers:** High-ticket items like the *Global Troy Executive Leather Tilter* and *Polycom Videoconferencing Unit* are the primary revenue drivers.
4. **Target Demographic:** The **Corporate** segment is the most lucrative, heavily outperforming the Consumer and Small Business sectors.
5. **Sales Trends:** Following a downward trajectory from 2009–2011, overall sales demonstrated a strong rebound entering 2012.

## 🚀 How to View the Project
1. Static Report: [View the High-Resolution PDF Export](Data%20Analytics%20Project%201.pdf)
2. **Source File:** Download the `Data Analytics Project 1.pbix` file in this repository to explore the DAX measures and data model directly in Power BI Desktop.
