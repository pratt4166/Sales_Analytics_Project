
# Sales_Insights_Project

Sales Analysis of a hardware company Atliq Technologies for years 2017-2020 

# Introduction

This project aims to analyse sales data of "Atliq Technologies" to extract meaningful insights that drive business decisions. Using SQL for data extraction and Power BI for transformation and visualization, we develop key performance indicators (KPI's) to understand sales trend, customer behaviour and product performance.


# Objectives

* Analyse sales performance over time
* Understand customer demographics and purchasing behavior
* Identify best selling and underperforming products
* Evaluate revenue growth and profitability
* Examine sales distribution across different regions

# Data Collection and Prepration

* Data Sources
  * Sales Transaction Data- Contains order details, product info, quantity sold and profit
  * Customer Data- Includes customer demographics, region and purchase frequency
  * Product Data- Provides product type and pricing
  * Time Dimention- Date based data for trend analysis

# Data Preprossesing and Cleaning
 
 * Data Extraction(SQL)
   * Extracted sales data from relational database using SQL queries

 * Data Cleaning(Power Query)
   * Handled missing values by applying filtering
   * Standardized date columns to date formats
   * Standardized currency formats to INR (some sales amount were in USD)
   * Ensured data consistency across different columns

 * Data Modelling(Power BI)
   * Imported clean data into Power BI
   * Created data relationships between tables (e.g., customers, products, sales, markets)
   * Defined calculated measures using DAX (Data Analysis Expressions)  

 # Key Metrics and Insights
 
 * Key Metrics (KPI's)
   * Total Sales Revenue- Sum of all sales transactions
   * Profit Margin %- (Profit/Revenue) x 100
   * Sales Growth- (Current period revenue / Previos period revenue) 
   * Profit Margin Contribution (for e.g., markets, revenue)- (Profit margin / Total Profit Margin) x 100
   * Profit Target- Created a field parameter to keep a check on targets fulfillment

 * Key Insights

   * Overall Sales Performance
     * The company generated 985 million in total sales revenue over the analysed period.
     * The sales numbers clocked to 2 million durind this period.
     * The peak sales perion was observed in (January to August), likely due to seasonal demand or promotions.
     * The lowest sales months were September to December, suggesting a potential need for marketind efforts or discounts during these periods.
     * Electricalsara contributed most in the company's revenue with 65 million in sale amount.
     * Electricalsara was the also the customer that made the highest sales by 1 million.

   * Top and bottom performing products
     * The top selling product was Prod090, contributing 1.4% to total revenue.
     * The least performing product was Prod017, selling only 315 units in the four year time period.
     * The most popular product type was own brand, accounting 38% of total revenue.

   * Markets Performance
     * The highest revenue generating market was Delhi NCR followed by Mumbai and Ahmedabad.
     * Delhi NCR was also the highest in sales quantity with Mumbai and Nagpur being second and third respectively.
     * Brick and mortar contributed 95% of the market share of Delhi and 5% was with E-Commerce.
     * In sales quantity Brick and mortar had 90% share with remaining held by E-Commerce.

   * Profit Analysis
     * A total of 2.1 million profit was made during this period of analysis.
     * The maximum profit was made by Bhubaneshwar accounting at 10.5%.
     * Meanwhile in profit contribution Mumbai topped the list with 23.9% by a bare margin of 0.8% with Delhi NCR coming second with 22.1% profit.
     * On the customer level the company made the highest profit from Electricalsbea accounting 15.6%.

   * Performance Insights
     * On the zonal level, only 2019 was the year that met the profit target in all zones whereas in the rest years there were one or two zones lacking behind
     * Revenue trend was seen growing in the years 2017, 2018 while in the upcoming years 2019,2020 the trend was steadily decreasing towards the end of the year.
     * Amount of sales done was the highest in 2018 with 997K and the year 2020 saw a drastic decrease in sales accounting just 350K sales in total which could be due to the pandemic situation.
     * Revenue also declined in these years with 2018 generating 414M to 2020 generating just 142M.
     * Profit made durind this period was around 20 million in the years 2018-19 whereas it hit the lowest in 2020 with a mere value of 2.1 million

















