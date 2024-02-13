# Atliq-Hardware-Finance-Supply-Chain-Analytics

## Overview


Welcome to the Atliq Hardware Analytics Project! This project aims to improve Atliq Hardware's operations by providing actionable insights. The insights are derived from a comprehensive analysis of key data sources, including customer behavior, transaction history, product trends, and regional dynamics. These insights help the company understand trends and make strategic decisions that match market demands and consumer preferences.

## Atliq Business Model


Atliq operates in the hardware industry, selling gadgets to various customers like Croma, BestBuy, Amazon, Staples, Flipkart, etc. Customers, in this context, refer to direct customers of Atliq, while consumers are the end users who consume the products. Atliq has a manufacturing unit and distributes its hardware gadgets to different customers across various countries. The company utilizes two types of platforms and three channels (Retailer, Direct, Distributors) for product sales.




## Database Structure


![1_5p-2ZW1BTo2sNFsPhEKvsg](https://github.com/sahooraghunath/Atliq-Hardware-Finance-Supply-Chain-Analytics-Using-MySQL/assets/119792506/34a8956b-d352-441a-8687-35f41b6efb22)


![1_Sb7W97tpW3NvscggmKqWLA](https://github.com/sahooraghunath/Atliq-Hardware-Finance-Supply-Chain-Analytics-Using-MySQL/assets/119792506/87b97ea4-2542-46d6-b1e6-338d916c7529)

The comprehensive infrastructure of the Atliq Hardware initiative encompasses a multi-faceted framework, incorporating essential components such as Customer, Products, Sales, pre and post-invoice deductions, and manufacturing tables. Key tables include:

* dim_customer: Stores information about customers.

* dim_product: Contains details about the products offered by Atliq Hardware.

* fact_forecast_monthly: Describes Atliq’s monthly sales prediction information.

* fact_freight_cost: Provides information about Atliq’s transportation costs.

* fact_gross_price: Describes the gross price for each unique product.

* fact_manufacturing_cost: Contains data related to the COGS amount.

* fact_post_invoice_deductions: Describes post-invoice deduction information.

* fact_pre_invoice_deductions: Contains pre-invoice deduction amount.

* fact_sales_monthly: Summarizes monthly sales transaction information.

## Fiscal Year and Project Management
Atliq initiates its business/financial year in September, aligning with high sales and the festive season lasting from September to December. The project employs the Kanban methodology for project management, a prominent approach within agile development. JIRA serves as the Kanban cockpit, allowing efficient navigation of tasks, deadlines, and project progress.

## Problem Statements


The project addresses various ad hoc requests, such as generating sales reports, preparing financial statements, creating visualizations, and automating processes through user-defined functions and stored procedures

# Task


### Finance Analytics:

1. Individual Product Sales Report for CROMA India Customer (FY=2021): Generate a report of individual product sales aggregated on a monthly basis.
   
  The report should have the following fields,
  *	Month
  *	Product Name
  *	Variant
  *	Sold Quantity
  *	Gross Price per item
  *	Gross price total


3. Aggregate Monthly Gross Sales Report for CROMA India Customer:
   * Prepare a report on aggregate monthly gross sales to track sales generated by CROMA India.
   * Prepare a report on yearly gross sale generated by CROMA India.
  
   * 
     ![Croma yearly sales](https://github.com/Raghunaths834/Atliq-Hardware-Finance-Supply-Chain-Analytics/assets/119792506/7a7400f2-02e6-423c-bb60-b92a49686f40)
     

     ![Uploading top market pie chart.png…]()

5. Automated Report Generation for Gross Sales: Create stored procedures for generating monthly and yearly gross sales reports for any customer.
       
6. Market Badge Determination: Create a stored procedure to determine the market badge (Gold or Silver) based on the total sold quantity.

## Top Customers, Products, Markets:

1. Top and Bottom 5 Reports: Generate reports on the top and bottom 5 markets, products, and customers by net sales.

2. Bar Chart for Top 10 Markets (% Net Sales): Prepare a bar chart report for FY=2021 for the top 10 markets by % net sales.

3. Pie Chart for Net Sales% Breakdown by Region: Create a pie chart for the net sales% breakdown of customers region-wise (APAC, EU, LTAM).

4. Top N Products in Each Division by Quantity Sold: Use dense rank function to get the top N products in each division by quantity sold.

## Supply Chain Analytics:
1. Forecast Accuracy Report
2. Get the customers for which forecast accuracy has dropped from 2020 to 2021
## Conclusion
The Atliq Hardware Analytics Project aims to provide comprehensive insights into the company's operational and financial performance. Leveraging a data-centric approach, the project facilitates informed decision-making, optimizing strategies, and fostering continuous improvement. The structured database and analytical methodologies ensure a thorough understanding of customer behavior, product trends, and market dynamics, contributing to the overall success of Atliq Hardware.
