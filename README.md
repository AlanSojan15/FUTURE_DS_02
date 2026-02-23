# FUTURE_DS_02
Professional churn analysis for a SaaS business using a multi-table Star Schema to identify retention drivers and behavioral patterns.

# Customer Retention & Churn Analysis Dashboard
### Internship Task 2 - Data Science & Analysis

##  Project Overview
In this project, I acted as a Data Analyst for a subscription-based SaaS company. The goal was to analyze customer churn, identify segments at risk, and provide data-driven recommendations to improve retention.

##  Data Modeling (Star Schema)
Unlike a simple flat file, this project involved a relational data model. I established relationships between 5 key tables using `account_id` as the primary key:
Accounts: Customer demographics.
Subscriptions: Plan levels and pricing.
Churn Events: Historical data on customer exits.
Support Tickets: Interaction history and friction points.
Feature Usage: Daily behavioral logs (Duration & Frequency).

##  Key Insights
The "3-Ticket Friction Point": Churn rates spike by over 40% once a customer submits their 3rd support ticket, indicating technical or billing frustrations.
Plan Performance: The Basic/Monthly plan has the highest churn rate, while Enterprise/Annual plans show 85% higher retention.
Predictive Usage Drop: Usage duration typically declines by ~30% in the 14 days leading up to a churn event—a key "Early Warning" signal.

##  Recommendations
1. Automated Interventions: Trigger a "Success Call" or specialized support outreach once a user hits 2+ support tickets in a single month.
2. Engagement Loops: Implement automated re-engagement emails for users whose usage duration drops below their 30-day average.
3. Conversion Incentives: Offer a trial of "Pro" features or a discount on Annual billing to Basic users to increase switching costs and loyalty.

##  Tools Used
Power BI Desktop: Data Modeling, DAX, and Visualization.
Power Query: Data cleaning and transformation.
DAX Measures: Created custom measures for Churn Rate %, Total Customers, and Retention Trends.
