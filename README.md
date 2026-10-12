![cover_photo](cover_image.png) 
# SALES PERFORMANCE ANALYSIS

## PROJECT OVERVIEW
This project focuses on the analysis of historical sales data using Microsoft Excel. The purpose of the project was to transform transactional sales data into meaningful information that could be used to understand revenue performance across different regions, salespeople, product types, years, and months.
The original dataset contained sales transactions covering the period from 2013 to 2015. Each transaction included information about the year, month, product type, salesperson, region, sales value, units sold, and order number.
The dataset was reviewed and prepared before being analyzed using Excel. PivotTables and charts were used to summarize the data and identify patterns in sales performance. A dashboard was subsequently developed to provide a consolidated visual representation of the major performance indicators and sales trends.
The analysis recorded 444 transactions, representing 2,322,594 units sold and total sales revenue of 3,254,576.95. The Central region generated the highest revenue, Parker recorded the highest sales among the salespeople, Ice Cream was the highest-revenue product type, 2014 recorded the highest annual revenue, and April generated the highest revenue among the months represented in the dataset.

## Business Problem
### Background
Sales data provides businesses with important information about financial and operational performance. However, raw transactional records can be difficult to interpret without appropriate analysis and visualization.
This project was developed to analyze historical sales records and transform them into useful business information. The analysis focuses on identifying patterns in revenue across different regions, salespeople, product types, years, and months.
Microsoft Excel was used as the primary analytical tool because it provides capabilities for data organization, calculations, PivotTables, charts, and dashboard development.
### Purpose of the Project
The purpose of this project is to analyze historical sales performance and provide a clear visual representation of the results.
•	Overall sales performance
•	Regional revenue distribution
•	Salesperson performance
•	Product type performance
•	Yearly sales trends
•	Monthly sales patterns
•	Transaction and unit volumes

## Project Objectives
1.	Examine the structure and quality of the sales dataset.
2.	Organize the sales information for analysis.
3.	Calculate total sales revenue.
4.	Determine the total number of units sold.
5.	Determine the total number of transactions.
6.	Analyze revenue by region.
7.	Analyze revenue by salesperson.
8.	Analyze revenue by product type.
9.	Compare sales performance across years.
10.	Analyze monthly revenue performance.
11.	Identify the highest-performing categories.
12.	Create charts that communicate the findings clearly.
13.	Develop a sales-performance dashboard.
14.	Generate useful business insights from the analysis.

## Business Questions
### Overall Performance
What is the total revenue generated?
2.	How many units were sold?
3.	How many transactions were recorded?
### Regional Analysis
4.	Which region generated the highest revenue?
5.	Which region generated the lowest revenue?
6.	How is revenue distributed across the regions?
### Salesperson Analysis
7.	Which salesperson generated the highest revenue?
8.	Which salesperson generated the lowest revenue?
9.	How does revenue compare across salespeople?
### Product Analysis
10.	Which product type generated the highest revenue?
11.	Which product type generated the lowest revenue?
12.	How does revenue compare across product types?
### Time Analysis
13.	Which year generated the highest revenue?
14.	Which month generated the highest revenue?
15.	How did revenue change across the analyzed years?

## Dataset Description
The raw dataset was provided in an Excel workbook named sales_raw-dataset.xlsx. The dataset contains 444 sales transaction records and 8 columns.

Product types represented:
•	Ice Cream
•	Frozen Yogurt
•	Popsicles
•	Tasty Treats
Regions represented:
•	Central
•	North
•	South
•	West
Salespeople represented:
•	Bishop
•	Lee
•	Parker
•	Pullen
•	Watson
Months represented:
•	January
•	February
•	March
•	April
•	May
•	November
•	December

## Data Cleaning and Preparation
### Checking Missing Values
All eight columns were checked for missing values. The final dataset contained 0 missing values across all eight fields.
### Checking Duplicate Records
The dataset was checked for duplicate rows. The analysis identified 0 exact duplicate rows, so no duplicate records needed to be removed.
### Checking Order Numbers
There were 444 unique order numbers across 444 records, indicating a one-to-one relationship between the recorded transaction rows and their order numbers in the supplied dataset.
### Data Types

### Sales Calculation
The completed workbook contains calculated sales values. In several rows, the Sales field is calculated using the Units field multiplied by a factor of 1.5.
Sales = Units × 1.5
For example: 1,597 units × 1.5 = 2,395.50 sales.

## Data Analysis Methodology
The analysis followed the workflow below:
Raw Sales Data  ↓
Data Inspection  ↓
Data Quality Checks  ↓
Data Preparation  ↓
PivotTables  ↓
Revenue Summaries  ↓
Charts  ↓
Dashboard  ↓
Business Insights
The main analytical metric was Sales/Revenue. Revenue was analyzed across region, salesperson, product type, year, and month. Additional performance indicators included total sales, total units, and total transactions.

## Sales Analysis and Findings


## Dashboard Development
A dedicated dashboard was created in sales-performance-dashboard.xlsx. The dashboard consolidates the major findings into a single visual interface, combining key performance indicators with revenue analysis by month, year, region, salesperson, and product type.

### Dashboard KPI

### Dashboard Visualization
•	REVENUE
•	REVENUE BY YEAR
•	REVENUE BY REGION
•	REVENUE BY SALESPERSON
•	REVENUE BY TYPE
### Dashboard Purpose
The dashboard was designed to reduce the need to manually examine individual tables. It allows users to quickly identify total revenue, total units, transaction volume, regional performance, salesperson performance, product performance, annual performance, and monthly revenue patterns.

## Key Insights
Overall Revenue — The dataset generated total sales of 3,254,576.95 across 444 transactions.
Central Region — The Central region generated the highest revenue, 1,391,555.30, representing approximately 42.8% of total revenue.
Salesperson Performance — Parker generated the highest revenue among the five salespeople, 760,122.80.
Product Performance — Ice Cream was the highest-revenue product type at 1,379,573.20, representing approximately 42.4% of total revenue.
Annual Performance — 2014 generated the highest annual revenue at 1,138,686.00.
Monthly Performance — April was the highest-performing recorded month at 640,494.40.

## Recommendation
Examine the Central Region — Because Central generated the largest share of revenue, management could investigate the customer, product, salesperson, and transaction factors contributing to its performance.
Investigate Lower-Performing Regions — The South region recorded the lowest revenue. Further analysis could determine whether this relates to transaction volume, customer count, product mix, sales coverage, or market conditions.
Monitor Product Performance — Ice Cream generated substantially more revenue than the other product categories. Its demand, inventory, pricing, and regional performance should be monitored while lower-performing products are investigated.
Review Salesperson Performance — Differences in salesperson revenue could be examined alongside transaction count, units sold, average transaction value, customer count, and region to provide greater context.
Investigate Monthly Patterns — April generated the highest revenue among recorded months. Further information on promotions, seasonality, customer behavior, and product availability could help explain this pattern.

## Conclusion
This project demonstrated how Microsoft Excel can be used to transform raw sales transaction data into meaningful business information. The analysis examined 444 transactions covering 2013–2015 and included product types, salespeople, regions, sales revenue, units sold, months, and order numbers.
The analysis produced several important findings. Total sales amounted to 3,254,576.95, while total units sold reached 2,322,594. The Central region generated the highest revenue, Parker was the highest-revenue salesperson, and Ice Cream was the highest-revenue product type. At the annual level, 2014 produced the highest revenue, while April was the highest-performing recorded month.
The completed dashboard provides a consolidated visual representation of these results and demonstrates how Excel can be used not only for calculations but also for business analysis and data visualization.

## Limitation
Incomplete Monthly Coverage — The dataset contains records for only seven months: January, February, March, April, May, November, and December. June through October have no records.
Limited Business Variables — The dataset does not include customer information, marketing expenditure, cost of goods sold, profit, discounts, inventory, or competitor information.
Historical Dataset — The analysis is based on historical records from 2013–2015 and therefore describes the supplied historical data.
Limited Context for Performance Differences — The dataset shows differences between regions, salespeople, and products but does not establish the reasons behind those differences.

## Tools and Skills Demonstrated
### Tools Used
•	Microsoft Excel
•	Excel formulas
•	PivotTables
•	Pivot Charts
•	Excel Dashboard
•	Data sorting and filtering
•	Data validation/checking
### Skills Demonstrated
•	Data inspection
•	Data quality checking
•	Duplicate checking
•	Missing-value checking
•	Data-type verification
•	Revenue analysis
•	Comparative analysis
•	Time-based analysis
•	KPI calculation
•	Data visualization
•	Dashboard design
•	Business insight generation
•	Report writing

## Appendix
The following appendices provide supporting screenshots from the Excel workbook, including the raw data, analysis outputs, and final dashboard.
  

![My Dashboard]( AppendixA)


