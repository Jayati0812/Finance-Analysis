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
I used AI as a client, roleplaying as Rakesh from Finance department 

Key Questions:

Which department is bleeding the most?
Which job role is most affected by attrition?
What is the average tenure after which employees leave?
What is the salary band of employees who left?
Do age group or marital status drive attrition?
What education field did employees who left belong to?
How does overtime affect attrition?
Does business travel play a role in driving attrition?
