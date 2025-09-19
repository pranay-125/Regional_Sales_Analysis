# Regional_Sales_Analysis

**📌 Executive Summary**

This project delivers an end-to-end regional sales analytics solution leveraging 5 years of U.S. sales data.
Through Exploratory Data Analysis (EDA) and an interactive Power BI dashboard, it uncovers key drivers of revenue, profitability, and customer behavior.

👉 The insights inform sales strategies, margin optimization, and regional investments, enabling stakeholders to make data-driven decisions.



**🎯 Business Problem**

Sales teams face challenges due to:

❌ Inconsistent revenue and profit performance across U.S. regions

❌ Limited visibility into seasonal swings and channel profitability

❌ Difficulty in identifying top SKUs and growth opportunities

Objective:
Develop a scalable analytics framework that surfaces sales trends, profitability levers, and customer/region insights while providing self-service dashboards for business teams.



**📂 Repository Structure**

├── EDA_Regional_Sales_Analysis.ipynb    # Python-based Exploratory Data Analysis

├── Sales_data(EDA Exported).csv         # Cleaned dataset for EDA

├── Regional Sales Dataset.xlsx          # Raw dataset

├── SALES REPORT.pbix                    # Interactive Power BI Dashboard

├── PPT --- Regional Sales Analysis.pptx # Executive Presentation Deck

├── README.md                            # Project Documentation



**🗂 Data Preparation & Engineering**

Initial Dataset Issues:

Data scattered across multiple unlinked tables (Sales, Customers, Products, Regions, Budgets).

No defined relationships between key tables.

Data Cleaning & Transformation.


🔹 Standardized column names and formats

🔹 Merged multiple tables into a single analysis-ready dataset

🔹 Created profit and profit_margin_pct features

🔹 Validated dataset – no missing values or duplicates


Final Dataset Attributes:

Identifiers: Order number, Order date, Customer, Product, Channel

Financials: Quantity, Unit Price, Revenue, Cost, Profit, Profit Margin %

Geography: State, Region, Latitude, Longitude

Calendar: Month Name, Month Number, Year

Planning: Annual Budget




**🔍 Analytical Approach**


1. Exploratory Data Analysis (Python)

📈 Trend analysis (monthly/seasonal sales patterns)

📊 Product performance (revenue & margin)

🛒 Channel profitability (wholesale, distributor, export)

🌎 Geographic contribution (state & region level)

👥 Customer segmentation (revenue vs. margin cohorts)

🔗 Correlation analysis (unit price as the key driver of profit)


2. Interactive Visualization (Power BI)

Performance Summary Dashboard – Sales, profit, margin KPIs.

Customer Segmentation – Revenue clusters vs. profitability.

Revenue Scenarios – Product/channel contribution comparisons.



**📊 Key Findings**


Seasonality: Sales peak in May–June, lowest in January.

SKU Concentration: Top 2 products generate ~25% of revenue.

Channel Trade-Off: Wholesale = 54% of sales, Export = highest margin (~38%).

Geographic Trends: California leads with $230M revenue; Northeast lags.

Customer Insights: Large customers often receive discounts, lowering margins.



**📝 Recommendations**

📌 Revenue Stability: Launch recovery campaigns in April and amplify promotions in January.

📌 SKU Optimization: Focus on high-margin SKUs (Products 26 & 25), re-evaluate underperformers.

📌 Channel Strategy: Expand Export partnerships; incentivize Wholesale with volume deals.

📌 Regional Focus: Scale California’s playbook to the Midwest & Northeast.

📌 Margin Monitoring: Flag orders below 80% margin and optimize pricing.



**🛠 Tools & Technologies**

Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly) – Data cleaning, EDA, statistical insights

Jupyter Notebook – Analytical workflow documentation

Power BI – Interactive dashboards for business users

Excel/CSV – Raw & processed datasets



**📌 Impact**

✔️ Delivered executive-grade insights into sales performance.

✔️ Enabled self-service dashboards for real-time decision-making.

✔️ Identified growth levers across products, customers, and regions.

✔️ Improved visibility into seasonality and margin drivers.

This project demonstrates expertise in sales analytics, BI reporting, and strategic recommendations—transforming raw datasets into actionable business insights.



**🚀 Next Steps**

🔮 Integrate predictive models for sales forecasting.

🔄 Automate data pipelines for real-time refresh.

🧩 Expand customer segmentation with RFM (Recency, Frequency, Monetary) analysis analysis.
