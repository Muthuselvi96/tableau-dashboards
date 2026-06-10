Learnt Data Visualization and Data Analytics with Tableau by solving 3 Realistic Analytics Projects.

1.Amazon Product Reviews & Recommendation Dashboard
2.Telecom Industry Customer Churn Analytics & Retention Dashboard

**Tools & Technologies Used**

MySQL Workbench, 
Excel (CSV Dataset	Source data) and 
Tableau Desktop (CSV Data Source from DBMS)

PROJECT 1: **Amazon Product Reviews & Recommendation Dashboard**

Project Overview

In this project I analyzed over 50,000 Amazon customer reviews to uncover customer sentiment, product performance, review helpfulness and recommendation trends. The solution transforms raw review data into actionable business insights through interactive Tableau dashboards that support product teams, marketing teams and customer experience managers in making data-driven decisions.

**Business Problem** - Organizations receive thousands of customer reviews daily, making it difficult to:

1.Identify highly recommended products
2.Understand customer sentiment
3.Detect recurring product complaints
4.Measure review helpfulness
5.Prioritize product improvements
6.Track customer satisfaction trends

Without analytics, valuable customer feedback remains underutilized.

**Project Objectives**
1. Customer Sentiment Analysis: Analyze customer ratings and sentiment trends.

2. Product Recommendation Analysis: Identify products customers are most likely to recommend.

3. Review Helpfulness Analysis: Determine which reviews influence customer decisions.

4. Product Improvement Opportunities: Identify low-rated products and recurring complaint themes.

5. Trend Analysis: Monitor rating and review activity over time.

**Tools & Technologies Used**

MySQL Workbench	
Excel (CSV Dataset	Source data)
Tableau Desktop (CSV Data Source from DBMS)
--Data Preprocessing Using SQL--
[Data Cleaning
Removed duplicate records
Handled missing values
Standardized review dates
Corrected inconsistent ratings
Data Transformation
Created recommendation categories
Calculated helpfulness percentage
Generated product-level aggregates
Created date hierarchy fields]

Tableau Dashboards Created
Dashboard 1: Sentiment & Rating Overview
Visualizations
Pie Chart – Rating Distribution
Line Chart – Average Rating Over Time
Bar Chart – Top Rated Products
Heatmap – Review Activity by Month/Day

Reported in project documentation.
KPIs
Average Rating Score
Total Reviews
Most Reviewed Product
Products Rated Above 4.5

Dashboard 2: Helpfulness & Reviewer Engagement
Visualizations
Bar Chart – Top Helpful Reviewers
Ratio Chart – Helpfulness Analysis
Data Table – Reviews with 100% Helpfulness
Word Cloud – Helpful Review Keywords
KPIs
Average Helpfulness %
Highly Helpful Reviews Count

Dashboard 3: Product Improvement Insights
Visualizations
Product Filter
Negative Review Volume Bar Chart
Complaint Topic Analysis
Negative Sentiment Timeline


**Recommended Reporting Type- Weekly Report**

Best option because customer reviews accumulate continuously but product teams generally review trends weekly.

Monthly Executive Report

For leadership review of:

Product performance
Customer satisfaction
Product improvement opportunities
Ad-Hoc Reporting

**Used when:**

Product complaints spike
Product launches occur
Negative sentiment suddenly increases


**Challenges Faced:**
Data Quality Issues - Missing helpfulness values, Duplicate reviews, Inconsistent review timestamps

Text Analytics Challenges - Unstructured review text, Sentiment extraction difficulties

Performance Challenges - Large dataset volume, Dashboard optimization

Visualization Challenges - Creating meaningful KPIs

**Business Impact**
Achieved:
1.Improved product recommendation visibility
2.Identified high-performing products
3.Highlighted product improvement opportunities
4.Enhanced customer feedback analysis
5.Enabled data-driven decision making

**End User Benefits**
Product Managers -> Prioritize feature enhancements
Marketing Teams -> Promote highly recommended products
Customer Experience Teams -> Monitor customer sentiment
Business Leaders -> Measure product satisfaction

**Best Practices Applied**
Interactive filtering
Dashboard hierarchy
KPI-driven design
Consistent color usage
User-friendly navigation
Actionable insights focus

**Project Summary**

This Tableau dashboard analyzes Amazon customer reviews and recommendation behavior using sentiment analysis, review helpfulness metrics, and product performance indicators. Data was cleaned and transformed using MySQL Workbench and SQL before being integrated into Tableau. The solution enables product teams to identify highly recommended products, monitor customer sentiment, evaluate review quality, and prioritize product improvements through interactive dashboards and KPI-driven reporting.

PROJECT 2: **Telecom Customer Churn Analysis**


Project Overview

This project analyzes telecom customer churn using customer demographics, contract details, payment methods, service plans, billing information, and customer support interactions. The objective is to identify churn drivers and provide actionable retention strategies that reduce customer attrition and revenue loss.

**Business Problem**

Telecom companies lose revenue when continously customers leave for competitors.

**Challenges include:**

1.Identifying churn-prone customers
2.Understanding churn reasons
3.Measuring contract effectiveness
4.Improving customer retention
5.Reducing customer acquisition costs


--Data Preprocessing--
[SQL Activities
Removed duplicates
Standardized contract categories
Created age bins
Classified churn categories
Aggregated customer call metrics]

Tableau Dashboards Created
Dashboard 1: Geographic Churn Analysis
Visualizations
State-Level Churn Analysis
Contract-Based Churn Rate
Churn Category Breakdown

Insights include Alaska churn rate and Florida churn reasons.

Dashboard 2: Customer Segment Analysis
Visualizations
Age Bin Analysis
Contract Type Analysis
Payment Method Analysis
Unlimited Data Plan Analysis

Insights identify high-risk customer segments.

Dashboard 3: Customer Service Analysis
Visualizations
Customer Call Volume
Average Calls
Service Plan Analysis
Retention Risk Monitoring

Weekly Report - Reported to:
Customer Success Teams
Retention Teams
Operations Teams

Daily Report:
Churn trend tracking
Retention campaign performance

Ad-Hoc Analysis:
Churn spikes occur
New telecom plans launch
Competitive threats emerge

Hourly reporting generally not required unless monitoring live customer service operations.

**Challenges Faced**
Data Challenges - Missing churn category values, Inconsistent customer records

Analytical Challenges - Multiple churn drivers, Complex customer segmentation

Dashboard Challenges -Large filter combinations, High-cardinality customer attributes

Business Challenges - Identifying actionable churn drivers, Converting insights into retention strategies



**Business Impact**

Identified churn drivers
Improved retention strategy development
Highlighted high-risk customer segments
Supported proactive customer engagement
Reduced potential revenue loss

**End User Benefits:**
Customer Success Managers - Identify churn-prone customers.
Retention Teams - Develop targeted campaigns.
Marketing Teams - Create personalized offers.
Executives - Monitor churn KPIs and revenue risk.

**Project Summary**
This Tableau-based Telecom Customer Churn Analysis project leveraged SQL and MySQL Workbench for data cleaning, transformation and feature engineering before visualization in Tableau. Interactive dashboards were developed to analyze churn rates across customer demographics, contracts, payment methods, geographic regions, and service plans. The solution provides actionable insights that help telecom organizations improve customer retention, reduce churn and optimize customer engagement strategies through data-driven decision-making.
