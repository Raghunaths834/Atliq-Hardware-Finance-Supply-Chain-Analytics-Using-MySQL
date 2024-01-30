# Atliq-Hardware-Finance-Supply-Chain-Analytics-Using-MySQL


**Overview**


Welcome to the Atliq Hardware Analytics Project! This project is designed to transform Atliq Hardware’s operational landscape by establishing a robust framework for generating actionable insights. The insights are derived from a comprehensive analysis of key data sources, including customer behavior, transaction history, product trends, and regional dynamics.

By harnessing the power of data-driven insights, Atliq Hardware aims to revolutionize its decision-making process. These insights not only identify emerging patterns and trends but also empower the company to make strategic moves aligned with market demands and consumer preferences. This data-centric strategy forms a virtuous cycle, ensuring decisions are grounded in empirical evidence, minimizing risks, and maximizing opportunities.

**Atliq Business Model**


Atliq operates in the hardware industry, selling gadgets to various customers like Croma, BestBuy, Amazon, Staples, Flipkart, etc. Customers, in this context, refer to direct customers of Atliq, while consumers are the end users who consume the products. Atliq has a manufacturing unit and distributes its hardware gadgets to different customers across various countries. The company utilizes two types of platforms and three channels (Retailer, Direct, Distributors) for product sales.

**Profit & Loss Analysis**


Let's delve into the profit and loss analysis of Atliq Hardware using an example:

-Atliq sells a mouse to Croma for $30.
-A pre-invoice deduction of $2 is applied, resulting in a Net Invoice Sales of $28.
-Croma offers promotional discounts to consumers, facilitated by Atliq.
-Various post-invoice deductions, such as festival sales discounts, platform fees, and performance rebates, are applied to the Net Invoice Sales.
-The final Net Sales are obtained by deducting the post-invoice deduction amount from Net Invoice Sales.
-The Cost of Goods Sold (COGS), including manufacturing cost, freight cost, and other expenses, is deducted from Net Sales to calculate Gross Margin.
-Atliq's profit margin is determined as a percentage of Net Sales.


**Database Structure**


The comprehensive infrastructure of the Atliq Hardware initiative encompasses a multi-faceted framework, incorporating essential components such as Customer, Products, Sales, pre and post-invoice deductions, and manufacturing tables. Key tables include:

dim_customer: Stores information about customers.
dim_product: Contains details about the products offered by Atliq Hardware.
fact_forecast_monthly: Describes Atliq’s monthly sales prediction information.
fact_freight_cost: Provides information about Atliq’s transportation costs.
fact_gross_price: Describes the gross price for each unique product.
fact_manufacturing_cost: Contains data related to the COGS amount.
fact_post_invoice_deductions: Describes post-invoice deduction information.
fact_pre_invoice_deductions: Contains pre-invoice deduction amount.
fact_sales_monthly: Summarizes monthly sales transaction information.
Fiscal Year and Project Management
Atliq initiates its business/financial year in September, aligning with high sales and the festive season lasting from September to December. The project employs the Kanban methodology for project management, a prominent approach within agile development. JIRA serves as the Kanban cockpit, allowing efficient navigation of tasks, deadlines, and project progress.

**Problem Statements and Solutions**


The project addresses various problem statements, including generating sales reports, preparing financial statements, and creating visualizations. Solutions involve SQL queries, user-defined functions, stored procedures, and views. Key problem statements include:

Individual Product Sales Report for CROMA India Customer (FY=2021): Generate a report of individual product sales aggregated on a monthly basis.

Aggregate Monthly Gross Sales Report for CROMA India Customer: Prepare a report on aggregate monthly gross sales to track sales generated by CROMA India.

Automated Report Generation for Gross Sales: Create stored procedures for generating monthly gross sales reports for any customer, product, or market.

Market Badge Determination: Create a stored procedure to determine the market badge (Gold or Silver) based on the total sold quantity.

Top and Bottom 5 Reports: Generate reports on the top and bottom 5 markets, products, and customers by net sales.

Bar Chart for Top 10 Markets (% Net Sales): Prepare a bar chart report for FY=2021 for the top 10 markets by % net sales.

Pie Chart for Net Sales% Breakdown by Region: Create a pie chart for the net sales% breakdown of customers region-wise (APAC, EU, LTAM).

Top N Products in Each Division by Quantity Sold: Use dense rank function to get the top N products in each division by quantity sold.

**Conclusion**
The Atliq Hardware Analytics Project aims to provide comprehensive insights into the company's operational and financial performance. Leveraging a data-centric approach, the project facilitates informed decision-making, optimizing strategies, and fostering continuous improvement. The structured database and analytical methodologies ensure a thorough understanding of customer behavior, product trends, and market dynamics, contributing to the overall success of Atliq Hardware.
