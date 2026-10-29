
# Customer Analytics – Churn Analysis

## Project Overview
This project analyzes customer churn for an **OTT subscription platform** using **SQL and Python**. It explores customer behavior, subscription patterns, support interactions, and revenue impact to identify churn trends and recommend data-driven customer retention strategies.

## Objectives
- Identify customer churn patterns across subscription plans and contract types.
- Analyze customer retention and cancellation trends.
- Evaluate the impact of customer complaints and support escalations on churn.
- Calculate key business KPIs and quantify revenue at risk.
- Recommend strategies to improve retention and customer lifetime value.

## Tools & Technologies
- **SQL** – Data extraction, joins, filtering, and aggregations
- **Python** – Data analysis and processing
- **Pandas & NumPy** – Data cleaning, transformation, and feature engineering
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook / VS Code** – Development and analysis
- **SQLite / SQL Database** – Data storage and querying

## Dataset Structure

| Table | Description |
|---|---|
| `db_customer` | Customer demographics, location, and interests |
| `db_subscription` | Subscription plans, contract types, charges, cancellations, CLTV, and churn scores |
| `db_support` | Customer complaints, escalations, CSAT scores, and feedback |

## Project Workflow
1. **Database Connection:** Connect the SQL database to Python.
2. **Data Extraction:** Import data using SQL queries and Pandas.
3. **Data Cleaning:** Handle missing values, correct data types, rename columns, and perform quality checks.
4. **Feature Engineering:** Create calculated columns, transform data, and apply filters.
5. **Exploratory Data Analysis (EDA):** Analyze churn patterns using aggregations, grouping, and pivot tables.
6. **KPI Calculation:** Measure churn, retention, ARPU, tenure, revenue at risk, and support metrics.
7. **Data Visualization:** Create charts to identify churn trends and high-risk customer segments.
8. **Business Recommendations:** Translate findings into actionable retention strategies.

## Key Performance Indicators (KPIs)
- **Churn Rate:** Churned customers / Total customers × 100
- **Retention Rate:** 100% − Churn Rate
- **Churn by Plan Type:** Churn rate segmented by Basic, Standard, and Premium plans
- **Churn by Geography:** Churn patterns by country and state
- **ARPU:** Subscription revenue / Active customers
- **Average Customer Tenure:** Average duration of customer subscriptions
- **Revenue at Risk:** Revenue associated with high-risk customers
- **Escalation Rate:** Escalated support interactions relative to total complaints
- **Average Complaints per Customer:** Total complaints / Distinct customers

## Key Findings

Based on the initial analysis:

- **Churn Rate:** 28.6%
- **Retention Rate:** 71.4%
- **Monthly Contract Churn:** 55.6%
- **Annual Contract Churn:** 8.3%
- **Average Customer Tenure:** 1,451 days
- **ARPU:** ₹18.8
- **Estimated Revenue Loss Due to Churn:** 18%
- **Priority Region:** Karnataka
- **Priority Period for Investigation:** September 2024

> **Note:** These figures are based on the initial analysis and should be validated against the final dataset and KPI definitions.

## Business Recommendations
- Investigate churn in Karnataka and identify possible regional service or pricing issues.
- Review pricing and product changes around September 2024.
- Prioritize medium- and high-risk customers based on churn scores and customer lifetime value.
- Investigate customer complaints, support escalations, and satisfaction trends.
- Explore annual subscription incentives and targeted retention campaigns.
- Use email, SMS, and customer support outreach to address issues before cancellation.

## Business Impact
The analysis supports data-driven decisions to:

- Reduce customer attrition.
- Improve subscription renewal rates.
- Identify revenue leakage and at-risk customers.
- Prioritize retention efforts based on customer value.
- Improve customer satisfaction and long-term customer lifetime value.

## Skills Demonstrated
**SQL | Python | Pandas | NumPy | Data Cleaning | Feature Engineering | Exploratory Data Analysis | KPI Analysis | Data Visualization | Customer Segmentation | Business Analytics**

## Future Enhancements
- Develop a predictive churn model using machine learning.
- Build an interactive dashboard using Power BI or Tableau.
- Automate periodic churn and revenue reporting.
- Implement customer risk segmentation and retention monitoring.

## Author
**Vankatesh**

GitHub: [@vyanky12](https://github.com/vyanky12)
