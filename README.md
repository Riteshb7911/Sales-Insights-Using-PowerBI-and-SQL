
# Atliq-Hardware-Sales-Insights-Using-PowerBI-and-SQL
### Dashboard Link: 
https://app.powerbi.com/groups/me/reports/301ccc31-39ad-4887-abb0-bc3575c5b687/b178d3786edc57625fa9?experience=power-bi

## Problem Statement



AtliQ Hardware is a company that provides computer hardware and peripheral manufacturers to its clients, with multiple branches across India.
The company's sales director is having a difficult time comprehending how the business is operating and what problems the company is currently experiencing because sales are not meeting expectations and are rapidly falling. 
And when he phones the regional managers to inquire about the current state of sales and the market, these people are not comfortable eating numbers from excel files, which is an obvious source of dissatisfaction. 
They now lack a solid understanding of their sales data, making it difficult for them to make informed decisions and prepare for the future. 
This lack of insight makes it impossible for AtliQ to identify trends, understand client preferences, manage inventory efficiently, and market successfully. 
As a result, individuals miss out on opportunities to advance and earn more money.
### Solution
Atliq opted to onboard the Data Analytics team for data-driven decision-making to track the sales insights that were not visible to sales previously.
### Objective.
Create a 360-degree dashboard for timely sales analytics across several regions.




# Data Discovery

Project Planning using AIMS Grid - It is a project management tool which consists of four components-

 * Purpose - (What to do exactly)

 * Stackholder - (Who will be involved)
 * End result - (What do you want to achieve)
 * Success Criteria - (Cost optimization and time save)
### AIMS Grid
1) Purpose :- To unlock sales insights that are not visible before for the sales them for decision support and automate them to reduced manual time spent in data gathering.

2) Stakeholders :- Sales Director, Marketing Team, Customer Service Team, Data and Analytics Team, IT

3) End result :- An automated dashboard providing quick and latest sights in order to support Data driven decision making.

4) Success Criteria :- Dashboard uncovering sales order insights with latest data available. Sales team able to take better decisions and prove 10% cost saving of total spend. Sales analysis stop data gathering manually in order to save 20% business time and reinvest it value added activity.

## Data Analysis using MySQL

Completed data discovery and then utilized MySQL for data analysis. The SQL database dump is located in the db_dump.sql file linked above. Download the db_dump.sql file to your local computer.

1) Importing Data into MySQL Workbench.
2) Data analysis involves searching through many tables and reflecting trash values.
3) Analysis of various SQL statements on a database using complicated SQL queries.

## Data Cleaning and ETL(Extract, Transform, & Load)
In the field of data analysis, data cleaning and ETL (Extract, Transform, Load) are critical steps in ensuring that the data we work with is correct, consistent, and ready for analysis. The following are the detailed phases in our data cleaning and ETL process:

**Step 1: Use PowerBI Desktop to connect to a MySQL database-**
Connecting our MySQL database to PowerBI Desktop is the first step in the process. This link acts as a conduit for accessing raw data, laying the groundwork for in-depth study.

**Step 2: Load Data into Power BI Desktop-** At this point, all tables created in the database are loaded into Power BI Desktop. This loading process makes a seamless connection with the SQL database, importing all records and creating the Power BI environment. The integration of data from the source into Power BI is critical for subsequent analysis and visualization.

**Step 3: Transform Data Using Power Query-** The primary goal of data cleaning and ETL is to convert raw data into a structured and useable state. Power Query comes to the rescue, allowing us to clean and reshape the dataset. Inconsistencies are corrected, missing values are handled, and the data is filtered to correspond with our analytical goals using a variety of transformations and manipulation. After this careful cleaning and modification, the dataset is ready for the next step: data modeling. With a clean and structured dataset in hand, we can dive into advanced analytics, find trends, and extract relevant insights to support informed decision-making.

This method ensures that the data we study is not only correct, but also optimized for gaining important insights, making it an essential component of our data analysis workflow.

## Building Dashboards 
In this critical stage, we use Power BI Desktop to create comprehensive dashboards and reports. We dive deep into data visualization using a variety of Data Analysis Expressions (DAX) metrics, transforming raw data into useful insights. DAX, a strong calculation language, allows us to generate calculated columns, tables, and advanced measures, which increases the granularity of our research.

## Insights And Decision-making
* The dashboard displays the company's total revenue of ₹985M over 4 years, total profit margin of ₹24.7M, profit margin percentage of 2.5%, and sales quantity of ₹2M. In 2020, the company generated ₹ 142M in revenue from 350K sales and made a profit of ₹ 2.1M.

* In four years, Delhi NCR has been our greatest market in terms of revenue with ₹520M and a total contribution of 52.8% with total revenue. However, when we look at the profit margin, In 2020, Bhubaneshwar enters the picture with the highest profit margin of 10.48%. 
* Similarly, if we look at Profit -- Contribution% by Market, we can see that Mumbai is the greatest contributor, accounting for 23.89% of overall profit.
* Electricalsara Stores is a top 5 customer, generating ₹ 413 M in revenue over 4 years.
* In our top 5 products, Prod318 has produced a total of ₹69M in sales over 4 years.
* Distribution generated ₹494M in revenue, whereas ownbrand generated ₹494M over the course of four years.
* Revenue Trend shows that revenue declined significantly in June 2020 compared to the previous year, with the lowest profit margin in April 2020.
## Tools and Languages
* MySQL server and SQL workbench
* Microsoft Power BI desktop
* Power Query Editor
## References
* https://www.youtube.com/@codebasics











































