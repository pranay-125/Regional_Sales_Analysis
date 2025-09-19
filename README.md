# Regional_Sales_Analysis

📌 Executive Summary
This project delivers an end-to-end regional sales analytics solution built on five years of U.S. sales data. By integrating exploratory data analysis (EDA), advanced feature engineering, and an interactive Power BI dashboard, it uncovers key drivers of revenue and profitability across products, customers, channels, and geographies.
The analysis bridges the gap between raw data and business strategy—highlighting seasonality, customer segmentation, and channel trade-offs—and provides actionable recommendations to support data-driven decision-making at the leadership level.

🎯 Business Problem
Sales teams lacked a clear, data-driven understanding of regional performance, leading to:
Inconsistent revenue and profit performance across U.S. regions.
Limited visibility into seasonal swings, channel profitability, and SKU concentration.
Difficulty in prioritizing growth levers and aligning resources.
Objective: Develop a scalable analytical framework and dashboard that surfaces insights on sales performance, margin dynamics, and regional opportunities.

📂 Repository Contents 
── EDA_Regional_Sales_Analysis.ipynb # Python-based Exploratory Data Analysis 
── Sales_data(EDA Exported).csv # Cleaned dataset (EDA-ready) 
── Regional Sales Dataset.xlsx # Raw dataset (multi-table format) 
── SALES REPORT.pbix # Interactive Power BI Dashboard
── PPT --- Regional Sales Analysis.pptx # Executive presentation deck 
── README.md # Project documentation





🗂 Data Engineering & Preparation
The raw dataset consisted of unlinked sales, customer, product, region, and budget tables. Key steps applied:
Standardization: Unified column naming and data formats.
Merging & Transformation: Joined multiple tables into a consolidated dataset.
Feature Engineering: Derived metrics such as profit and profit_margin_pct.
Validation: Ensured no missing values or duplicates.
Final Dataset: 20+ attributes spanning financials, customers, regions, and planning.

🔍 Analytical Approach Exploratory Data Analysis 
(Python – Jupyter Notebook)
Trend Analysis: Seasonal patterns, outliers, annual cycles.
Product Performance: Revenue & profit margin benchmarking.
Channel Analysis: Wholesale, distributor, and export profitability comparisons.
Geographic Insights: State-level & regional market contributions.
Customer Segmentation: Revenue vs. profit margin cohorts.
Correlation Analysis: Identified pricing as the primary revenue/profit driver.
Visualization & Storytelling (Power BI).
Performance Summary Dashboard: Revenue, profit, order volume trends.
Customer Segmentation View: Revenue distribution vs. profitability.
Revenue Scenarios: Channel and product contribution simulations.

📊 Key Findings
Seasonality: Revenue peaks in May–June; January is the weakest month.
SKU Concentration: Top 2 products drive ~25% of sales, requiring SKU rationalization.
Channel Trade-Off: Wholesale generates 54% of sales; Export yields highest margins (~38%).
Geographic Distribution: California contributes $230M; Northeast underperforms.
Customer Segmentation: Large accounts often receive discounts, lowering margins.

📝 Strategic Recommendations
Revenue Stability: Introduce April recovery campaigns and amplify January promotions.
SKU Optimization: Focus investment on high-performing SKUs (Products 26 & 25) and reprice low-margin items.
Channel Strategy: Incentivize Export partnerships for margin expansion and Wholesale for volume growth.
Regional Focus: Replicate California’s model in Midwest & Northeast to balance sales concentration.
Margin Management: Implement monitoring for sub-80% margin orders to control cost leakage.


🛠 Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly) – Data cleaning, EDA & statistical insights.
Jupyter Notebook – Analytical workflow documentation.
Power BI – Interactive, self-service dashboard for stakeholders.
Excel/CSV – Data integration and validation.

📌 Impact
This project demonstrates my ability to:
Translate raw multi-source sales data into business-ready insights.
Combine statistical EDA and interactive BI tools for multi-level stakeholders.
Deliver executive-grade recommendations that support sales growth, margin improvement, and regional expansion strategies.
Build scalable analytics solutions that can onboard new datasets seamlessly.

🚀 Next Steps
Extend analysis to include predictive modeling for sales forecasting.
Integrate real-time data pipelines for continuous dashboard refresh.
Expand customer segmentation using RFM (Recency, Frequency, Monetary) analysis.



Expand customer segmentation using RFM (Recency, Frequency, Monetary) analysis
