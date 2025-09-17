# __Sales Analysis (2014–2018) — Acme Company__
📌 Project Overview

This project analyzes Acme Co.’s U.S. sales data from 2014–2018 to identify key drivers of revenue and profitability across products, channels, and regions. The analysis explores seasonality, pricing, and margin patterns, detects outliers, and benchmarks performance against budgeted figures.

The ultimate goal is to extract actionable insights that guide pricing strategies, promotional planning, and market expansion decisions. A Power BI dashboard is planned to extend these insights into interactive reporting.

## Problem Statement 🎯

Acme Co. seeks to understand:

Which products, channels, and regions contribute most to revenue and profitability.

How seasonal trends and anomalies affect planning and forecasting.

Where outlier transactions distort averages and pose risks.

How unit price and profit margin interact, revealing pricing inefficiencies.

What strategies can ensure sustainable growth while reducing concentration risks.

## Dataset 🗂

Time Period: 2014–2018

Geography: United States

Key Fields:

Product Name, Category, Unit Price, Quantity

Revenue, Profit, Profit Margin %

Channel (Wholesale, Distributor, Export)

Region/State

Budgeted vs. Actual figures

## Tools & Libraries 🛠

Python: Pandas, NumPy, Matplotlib, Seaborn

Jupyter Notebook for analysis & visualization

Power BI (planned for dashboarding)

## 🔍 Methodology
1. Data Profiling & Cleaning

Validated schema and ensured consistency.

Standardized data types (dates, numeric fields).

Handled missing values (especially budget).

Removed duplicates and corrected formatting issues.

2. Univariate Analysis

Revenue, Unit Price, Profit Margin distributions.

Identified skewness and spread of values.

3. Bivariate Analysis

Product vs. Revenue/Profit comparison.

Channel contribution analysis.

Unit Price vs. Profit Margin % (scatter density).

4. Trend & Seasonality

Monthly and yearly sales trends (2014–2018).

Investigated recurring patterns and anomalies (e.g., 2017 dip).

5. Outlier Detection

Flagged abnormally high/low unit prices and revenues.

Checked for budget vs. actual variances.

6. Segmentation & Correlation

Grouped customers by revenue & margin performance.

Correlation between revenue, unit price, and margin.

## 📈 Key Insights

Monthly Revenue Cycle:
Stable at ~$23M–$26.5M (2014–2017), no strong seasonal spikes. Sharp dip in early 2017 (~$21.2M).

Channel Mix:
Wholesale: 54% | Distributors: 31% | Exports: 15% → growth opportunity in exports.

Top Products:

Product 26: $118M

Product 25: $110M

Product 13: $78M

Mid-tier: $68M–$75M

Low-tier: $52M–$57M

Profit Margins:
Range: ~18% to ~60%. No clear correlation with unit price, suggesting uniform pricing across tiers.

Seasonality:
Slight uptick in May–June. No consistent trend; early 2017 dip requires deeper investigation.

Regional Performance:

California: ~$230M | 7,500+ orders

Illinois, Florida, Texas: $85M–$110M | 3,500–4,500 orders

NY & Indiana: ~$54M | ~2,000 orders

## 💡 Recommendations

Outlier Strategy

Exclude extreme bulk/discount transactions when calculating averages.

Reassess promotional SKUs with unusually low margins.

Margin Uplift

Focus on mid/low-tier products to boost profitability.

Streamline costs for underperforming SKUs.

Channel Strategy

Double down on Wholesale & Distributor networks.

Invest in Export expansion to diversify revenue streams.

Seasonal Planning

Build campaigns around May–June uplift.

Investigate 2017 disruption to prevent future dips.

Regional Growth

Scale further in California.

Target Illinois, Florida, Texas for expansion.

Reassess NY/Indiana strategy due to weak returns.

## 📊 Deliverables

Exploratory Data Analysis Notebook: Detailed step-by-step insights (this repo).

Visualizations: Revenue trends, profit margins, product/channel breakdowns.

Power BI Dashboard (Planned): Interactive reporting tool for leadership.

## 🚀 Next Steps

Automate monthly reporting pipeline.

Deploy Power BI dashboard with drilldowns.

Integrate predictive modeling for demand forecasting.

📂 Repository Structure
``` bash
Sales-Analysis/
│── EDA_Regional_Sales_Analysis.ipynb   # Jupyter notebook with full EDA  
│── Regional Sales Dataset.xlsx          # Original dataset  
│── Sales_data(EDA Exported).csv         # Cleaned dataset  
│── SALES REPORT.pbix                    # Power BI report (planned)  
│── README.md                            # Project documentation (this file)
```  

🔥 This project demonstrates how EDA can directly shape business strategy, guiding decisions on pricing, promotions, and market expansion.
