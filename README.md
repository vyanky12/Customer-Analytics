Customer Analytics – Churn Analysis
Project Overview

This project analyzes customer churn for an OTT subscription platform using SQL and Python. It explores customer behavior, subscription patterns, support interactions, and revenue impact to identify churn trends and recommend data-driven customer retention strategies.

Objectives
Identify customer churn patterns across subscription plans and contract types.
Analyze customer retention and cancellation trends.
Evaluate the impact of customer complaints and support escalations on churn.
Calculate key business KPIs and quantify revenue at risk.
Recommend strategies to improve retention and customer lifetime value.
Tools & Technologies
SQL – Data extraction, joins, filtering, and aggregations
Python – Data analysis and processing
Pandas & NumPy – Data cleaning, transformation, and feature engineering
Matplotlib & Seaborn – Data visualization
Jupyter Notebook / VS Code – Development and analysis
SQLite / SQL Database – Data storage and querying
Dataset Structure

The project uses three relational tables:

Table	Description
db_customer	Customer demographics, location, and interests
db_subscription	Subscription plans, contract types, charges, cancellations, CLTV, and churn scores
db_support	Customer complaints, escalations, CSAT scores, and feedback
Project Workflow
Database Connection: Connect the SQL database to Python.
Data Extraction: Import data using SQL queries and Pandas.
Data Cleaning: Handle missing values, correct data types, rename columns, and perform quality checks.
Feature Engineering: Create calculated columns, transform data, and apply filters.
Exploratory Data Analysis: Analyze churn patterns using aggregations, grouping, and pivot tables.
KPI Calculation: Measure churn, retention, ARPU, tenure, revenue at risk, and support metrics.
Visualization: Build charts to identify churn trends and high-risk customer segments.
Business Recommendations: Translate findings into actionable retention strategies.
Key Performance Indicators (KPIs)
Churn Rate: Churned customers / Total customers × 100
Retention Rate: 100% − Churn Rate
Churn by Plan Type: Churn rate segmented by Basic, Standard, and Premium plans
Churn by Geography: Churn patterns by country and state
ARPU: Subscription revenue / Active customers
Average Customer Tenure: Average duration of customer subscriptions
Revenue at Risk: Revenue associated with high-risk customers
Escalation Rate: Escalated support interactions relative to total complaints
Average Complaints per Customer: Total complaints / Distinct customers
Key Findings

Based on the initial analysis:

Overall churn rate: 28.6%
Retention rate: 71.4%
Monthly contract churn: 55.6%
Annual contract churn: 8.3%
Average customer tenure: 1,451 days
Average revenue per user (ARPU): ₹18.8
Estimated revenue loss due to churn: 18%
Karnataka and September 2024 were identified as priority areas for further investigation.

Note: These figures should be validated against the final dataset and KPI definitions before being treated as definitive results.

Business Recommendations
Investigate churn in Karnataka and identify possible regional service or pricing issues.
Review pricing and product changes around September 2024.
Prioritize medium- and high-risk customers based on churn scores and customer lifetime value.
Investigate complaints, escalations, and customer satisfaction trends.
Explore annual subscription incentives and targeted retention campaigns.
Use email, SMS, and customer support outreach to address issues before cancellation.
Expected Business Impact

The analysis supports data-driven decisions to:

Reduce customer attrition.
Improve subscription renewal rates.
Identify revenue leakage and at-risk customers.
Prioritize retention efforts by customer value.
Improve customer satisfaction and long-term lifetime value.
Skills Demonstrated

SQL querying, database integration, Python programming, data cleaning, feature engineering, exploratory data analysis, KPI development, data visualization, customer segmentation, and business storytelling.

Future Enhancements
Build a predictive churn model using machine learning.
Develop an interactive dashboard using Power BI or Tableau.
Automate periodic churn and revenue reporting.
Implement customer risk segmentation and retention monitoring.
Author

Vankatesh

GitHub: @vyanky12
