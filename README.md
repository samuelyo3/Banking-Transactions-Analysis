# Banking-Transactions-Analysis
## Introduction
In this project, I took on the role of a bank data analyst, analyzing a comprehensive banking dataset that simulates internal transaction data used by financial institutions to understand customer behaviour, optimize services, and inform strategic planning.
The dataset contains 20,000 enriched financial transactions across products like checking accounts, loans, mortgages, and card payments. 

This analysis will help the bank:
-	Understand how different customer segments behave financially
-	Identify high-fee and high-risk patterns for cost control and opportunity
-	Evaluate operational efficiency by channel and region
-	Develop data-driven strategies to boost engagement and retention
## Dataset Overview
The dataset (from FP20 Analytics Challenges Group) contains detailed banking activity and includes the following key fields:
- Transaction ID
- Customer ID
- Transaction Date
- Transaction Type
- Amount
- Product Category
- Branch City
- Branch Lat
- Branch Long
- Channel
- Currency
- Credit Card Fees
- Insurance Fees
- Late Payment Amount
- CustomerScore
- MonthlyIncome
- CustomerSegment
- RecommendedOffer
## Tools
Microsoft Power BI
## Exploratory Data Analysis
### Pre-Analysis Questions
Customer Insights & Segmentation
-	Which customer segments (e.g., high income vs. low income) are most transaction-active?
-	Which financial products are most popular within each segment?
-	Do credit scores align with transaction frequency or accumulated fees?

Transaction Behavior Analysis
-	What are the dominant transaction types by volume and value?
-	Which cities or branches are transaction hotspots or underperformers?
-	How does usage vary between mobile, ATM, and branch banking?

Revenue & Cost Insights
-	Which transactions drive the most fee-based revenue (e.g., credit card, insurance, late payments)?
-	Are certain customer groups incurring disproportionate costs?
-	What are the most frequent sources of revenue-generating friction?

Trend & Performance Analytics
-	Do certain months or seasons reflect transactional peaks or slowdowns?
-	Are product recommendations aligned with actual customer needs and behaviors?
-	What trends emerge across segments or channels over time?

This interactive report is designed with: Dynamic currency conversion (EUR/USD), KPI indicators showing YoY growth trends, drillable visuals for detailed segment and product insights, slicers for multi-level filtering and exploration
## Insights
1. Year-over-Year Trends
 From 2023 to 2025, the platform experienced a steady decline in overall transaction activity, with 2023 marking the peak year.
  - Transactions: 1,288 (2023) → 1,259 (2024, -2.25%) → 479 (2025, -61.95%)
  - Transaction Amount: $6.46M → $6.42M (-0.70%) → $2.41M (-62.43%)
  - Revenue: $39.61K → $40.56K (+2.39%) → $15.75K (-61.16%).
3. Customer Segments & Seasonality
 Middle-income customers made the most transactions, followed by high- and low-income segments.
 Transactions peaked in April (middle/high) and March (low income) but tended to dip later in the year, particularly in September and November.
4. Product & Channel Insights
 Credit cards led in transaction volume, followed by loans, while mortgages and checking accounts were lowest (19.43% each).
 Across channels, ATMs had the most activity, with mobile, branch, and online close behind.
5. Fee-Based Revenue Trends
 Overall, late payment fees generated the highest revenue ($48.89K), followed by insurance ($31.31K) and credit card fees ($15.72K).
 In 2024, all fee types grew modestly: insurance (+3.44%), late payment (+0.19%), and credit card (+7.25%).
 However, 2025 saw sharp declines across all categories: insurance (-64.44%), late payment (-58.92%), and credit card (-61.35%), signalling a major slowdown in fee-based revenue activity.
6. Temporal Insights
 January recorded the highest revenue, followed by April and March, while June and July had the lowest.
 Transaction activity was stronger on weekdays than at weekends, reflecting higher engagement during business day

