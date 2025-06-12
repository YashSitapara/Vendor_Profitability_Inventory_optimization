# 📊 Vendor Performance, Profitability & Inventory Optimization Analysis

## Overview

An end-to-end data analytics pipeline focused on identifying inefficiencies in vendor performance and inventory control within the retail domain. The project leverages vendor transaction-level data to compute and evaluate key metrics such as gross profit, profit margin, stock turnover ratio, and sales-to-purchase ratios. Data preprocessing, aggregation, and feature engineering are performed using Python (Pandas, NumPy), while data visualization is handled with Matplotlib and Seaborn. SQL is used for structured query operations and KPI extraction from a SQLite database. Power BI is employed to create interactive dashboards for executive-level monitoring, and statistical techniques are applied to validate performance differences and guide data-driven decision-making.

## Features

- Data Loading: Retrieves vendor sales data from a MySQL database.
- Exploratory Data Analysis (EDA): Provides summary statistics and visualizations to understand data distributions and identify patterns.
- Statistical Tests: Utilizes t-tests to compare vendor performance metrics.
- Visualizations: Generates histograms and other plots to visualize key metrics.

## Requirements

- Python 3.x
- Libraries:
    - pandas
    - numpy
    - matplotlib
    - seaborn
    - scipy
    - sqlalchemy
    - pymysql

## 📂 Data can be downloaded

You can download the dataset used in this project from the following link:  
[📥 Click here to access the data](https://your-download-link.com/data.zip)

## 🧾 Business Objectives

- Understand and quantify key performance drivers
- Identify actionable issues or inefficiencies
- Validate business hypotheses through statistical methods
- Provide decision-makers with concise and data-backed insights
- Enable automation for repeatable analytics
- Identify underperforming brands for strategic action
- Pinpoint vendors with low stock turnover or losses
- Leverage bulk purchasing insights to reduce unit cost

## 🚀 Key Highlights

- 🔄 Automated Data Ingestion using Python scripts
- 🧠 Data Transformation & Cleaning to prepare for analysis
- 📊 SQL-based Analytical Queries to extract performance insights
- 📈 Exploratory Data Analysis to uncover patterns and anomalies
- 📉 [Domain-Specific Analysis], e.g., risk, profitability, customer churn
- 📑 Interactive Dashboard for actionable visual insights
- 📄 Comprehensive Report with data-driven recommendations

## 🛠️ Tools & Tech Stack

- Python – Pandas, NumPy, SQLite, Matplotlib, Seaborn
- SQL – Analytical functions, joins, subqueries
- Power BI – Interactive dashboards
- Jupyter Notebook – Analysis & prototyping
- PDF – Final report for stakeholders

## 📁 Repository Structure

> 📄 **LoadData.py**  
> Script to load raw datasets into MySQL database tables for structured querying and storage.

> 📄 **EDA.ipynb**  
> Initial Exploratory Data Analysis notebook for understanding data distributions, handling missing values, and merging multiple tables for deeper insights.

> 📄 **Vendor Performance Analysis.ipynb**  
> Core analysis notebook addressing business objectives, answering stakeholder queries, and evaluating vendor performance metrics like gross profit, margins, stock turnover, and sales-to-purchase ratios.

> 📄 **dashboard.pbix**
> Power BI dashboard visualizing key metrics for vendor and inventory performance.

## ❓ Research Questions Answered

- Which brands need promotional or pricing adjustments?
- Which vendors and brands show the highest sales performance?
- Who contributes most to total purchase dollars?
- How dependent is procurement on the top vendors?
- Does bulk purchasing reduce unit price? What's the optimal volume?
- Which vendors have low inventory turnover?
- How much capital is locked in unsold inventory by vendor?
- What are the 95% confidence intervals for vendor profit margins?
- Is there a significant difference in profit margins between top and low-performing vendors?

## 💡 Business Insights

- Gross profit shows a strong correlation with total sales dollars, but only a weak link with profit margin
    - Indicates that profitability is primarily driven by higher sales volume rather than margin improvements.
- A strong correlation exists between stock turnover and the sales-to-purchase ratio
    - Enhancing one of these metrics is likely to positively influence the other.
- Top vendors consistently demonstrate higher unit profitability and lower freight costs, highlighting superior operational efficiency.
- Several products are priced very close to their cost, limiting profit potential
    - Presents a clear opportunity for margin optimization through strategic pricing.
- Using pre-aggregated datasets significantly improves dashboard responsiveness and simplifies reporting processes in Power BI.

## ✅ Recommendations

- Prioritize vendors with the highest net profit-to-cost ratio.
- High-performing vendors: Explore selective price increases or bundling.
- Low-performing vendors: Focus on marketing, competitive pricing, or better distribution.

## 👨‍💼 Author
**Yash Sitapara**
[GitHub Profile](https://github.com/YashSitapara)