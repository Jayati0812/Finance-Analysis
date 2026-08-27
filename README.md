# Finance-Analysis
1. project Title
   Finance Analysis
   built an end to end finance analysis in microsoft fabric ingesting ~2000+ accounts of customers through fabric pipeline to understand which customers have consistently been a problem and how much money is at risk.

2. short description
   The finance Analysis is an analytical report designed to help Rakesh(from Finance department) understand why Over the last few quarters, our Days Sales Outstanding (DSO) has been creeping up. Cash that should be in our account is sitting with customers longer than it should. This dashboard focuses on which customers have consistently been a problem and how late typically and how much money is at risk. This tool is intended for use by data analysts, the finance department, management, and data-driven strategists who want to understand DSO trends.

3. Tech Stack
The dashboard was built using the following tools and technologies:

Microsoft pipeline – Ingested ~2000+ customer records through an online dataset and applied transformations using notebook on the data.
microsoft pyspark notebook – Data transformation, cleaning, and feature engineering for preparing the data using pyspark.
Microsoft Lakehouse – Primary data source with structured Delta tables in the Tables section.
Microsoft Fabric Semantic Model – Created the data model and built relationships.
DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.
Power BI Desktop – Main data visualization platform used for report creation.
OneLake Security - Created Column Level Security and row level security to ensure the safety of personal data.
App - Published App_HR for end-user access.
File Format – .pbix for development and .png for dashboard previews.

4. Data Source
Source: Finance Factoring - IBM Late Payment Histories
Link: Kaggle ![Dataset](https://www.kaggle.com/datasets/hhenry/finance-factoring-ibm-late-payment-histories)
Data covers ~2000+ customer records, including details such as invoice date, invoice amount, paperless bill, due date, days late, and days to settle, for the years 2012–2013.

6. Feature Highlights
Business Problem
I used AI as a client, roleplaying as Rakesh from Finance department where Our company sells on credit to distributors and business clients — standard 30/45/60 day payment terms. Over the last few quarters, our Days Sales Outstanding (DSO) has been creeping up. Cash that should be in our account is sitting with customers longer than it should.

Key Questions:

How much money are we actually talking about?
Which customers have consistently been late?
Is there a pattern in why people pay late?
Is late payment behavior worsening month over month?
When customers are late, how late?

Goal of the Dashboard
The goal of this dashboard was to create an interactive report that helped Finance department understand the cause of such a delay in payments, given that the standard 30/45/60 day payment terms. This dashboard helped Rakesh from Finance communicate to leadership and senior management what steps could be taken to reduce and manage DSO by identifying its key drivers.

Key Visuals
KPI'S used in this report:
1. Money at risk: 53.96K - total invoice amount with late customers
2. late customers: 83 - count of customers who paid late
3. total customer:100 - distinct count of customers
4. late customer % YoY Comparison: -3.51% - late payment performance improved by 3.51%
5. avg days late: 9.68 - avg days customer paid after invoice date

slicers used
1. year - invoice year
2. month - invoice month
3. country code

Total Invoices and Customer % Late Trend over time
this chart is line and column combo chart in which the column represents the total invoices each month and line represents late customer %. so that we can see out of these many invoices see much % were late

Customer % Late by Disputed Bills
this chart is a bar chart which shows if the bill is disputed drives the late payment issues or not.

Customers Late by 30+ days 
this is a matrix of customers who paid after 30+ days to see whether the amount to be paid by them was more or not as it will help us plan our treasury easily and in advance 

Top 10 Customers by Avg Days Late
this is a matrix of customers who paid max of the payments late i.e max late customer % and it also consists of total invoices and avg days late

Customer % Late by Type of Bills
this is a bar chart that helps us understand whether paper bills or electronics bills are late or not. so that we can plan accordingly to shift to that bill which causes less late payment

7. Insights

 - Money at risk i.e. the total amount with late customer is 53.96K
 - the DSO or we can say the late customer % year over year has improved by 3.5%.
 - the top 10 customers whose late customer % is high needs to be called first.
 - some of the customers who pay after 30 days are having high invoice amount.
 - the bills that are disputed tends to have more late payments
 - paper bills tends to generate more late payments
 - the bills with large income an=mount band are receiving the most late payments

8. Business Impact

   -
