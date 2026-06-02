# GameZone Sales Performance Analysis

#### Project Background

GameZone is an online retailer specializing in gaming consoles, gaming accessories, and gaming-related electronics. The company sells products through multiple marketing channels and serves customers across various regions. As sales data accumulates over time, it becomes increasingly important to understand customer purchasing behaviour, product performance, and the effectiveness of different acquisition channels.

This project analyzes GameZone's sales transactions from 2019 to 2021 to uncover insights that can support data-driven business decisions and revenue growth. The analysis focuses on identifying sales trends, evaluating product performance, understanding regional demand patterns, assessing marketing channel effectiveness, and measuring customer value through Lifetime Value (LTV).

Insights and recommendations are provided on the following key areas:

**Sales Performance Analysis**: Evaluation of Gross Merchandise Value (GMV), order volume, and Average Order Value (AOV) to identify overall business performance and sales trends over time.

**Product Performance Analysis**: Assessment of revenue contribution, order volume, sales mix, and unit pricing across GameZone's product portfolio to identify top-performing products.

**Marketing Channel Analysis**: Examination of customer acquisition channels to determine their impact on sales performance and customer value.

**Regional Performance Analysis**: Comparison of sales performance and customer value across geographic regions to identify high-performing markets.

**Customer Lifetime Value (LTV) Analysis**: Analysis of historical customer value by region and marketing channel to understand which customer segments generate the greatest long-term revenue.

An interactive Tableau dashboard was developed to visualize key business metrics and performance trends.

The complete Jupyter Notebook containing data cleaning, preprocessing, exploratory data analysis, KPI calculations, and business-driven insights can be found here.

The Tableau workbook used to create the dashboard and visualizations can be found here.

The original dataset used for this project can be found here.

#### Data Structure & Initial Checks
The GameZone dataset contains sales transaction records from 2019 to 2021, including information on products, orders, marketing channels, purchase platforms, and regions.


Before analysis, the data was explored and validated in Jupyter Notebook through data quality checks, including:

•	Inspection of data types and missing values
•	Duplicate record verification
•	Validation of sales and order metrics
•	Review of categorical variables such as Product Name, Region, and Marketing Channel

The analysis identified missing values in the Region and Marketing Channel fields, which were considered when interpreting regional and customer value metrics.

#### Deep Dive into Insights
**Sales Performance**
•	GameZone generated a total GMV of $6.14M across 21,719 orders, with an average order value (AOV) of $281.16.
•	Sales experienced a decline in January 2020 before recovering and reaching peaks in April, September, and December 2020, indicating potential seasonal demand patterns.

**Product Performance**
•	The 27-inch 4K Gaming Monitor generated the highest revenue ($1.95M), despite recording fewer orders than the Nintendo Switch, which achieved the highest order volume (10,386 orders).
•	Revenue generation was driven by both product popularity and unit pricing, with higher-priced products contributing disproportionately to total sales.

**Regional Performance**
•	The US/Null region contributed the highest sales, followed by EMEA and APAC.
•	APAC recorded the highest average historical Customer Lifetime Value (LTV), suggesting stronger long-term customer value among available regional data.

**Marketing Channel Performance**
•	The Direct marketing channel generated the highest revenue, significantly outperforming all other channels.
•	Customers acquired through the Affiliate channel exhibited the highest average historical LTV, while Email and Social Media channels recorded the lowest customer value.

**Data Quality Observations**
•	Missing values were identified within the Region and Marketing Channel fields, which may influence regional and customer value analyses and should be considered when interpreting results.

#### Recommendations
Based on the analysis of GameZone's sales performance, product trends, marketing channels, and customer value metrics, the following recommendations are proposed:
1. Leverage High-Performing Products
The 27-inch 4K Gaming Monitor, Nintendo Switch, and Sony PlayStation 5 Bundle generated the majority of revenue. Marketing efforts, inventory planning, and promotional campaigns should prioritize these products to maximize sales and profitability.
2. Improve Low-Performing Marketing Channels
Email and Social Media channels recorded the lowest Customer Lifetime Value (LTV). Campaign strategies for these channels should be reviewed and optimized to attract higher-value customers and encourage repeat purchases.
3. Capitalize on Seasonal Demand
Sales peaked during April, September, and December 2020, suggesting recurring periods of higher demand. Future promotional campaigns, inventory allocation, and marketing budgets should be aligned with these peak sales periods.
4. Increase Average Order Value (AOV)
Cross-selling, upselling, and product bundle strategies can be implemented to encourage customers to purchase complementary products, thereby increasing the average revenue generated per order.
5. Improve Data Collection Quality
A significant number of missing values were identified in the Region and Marketing Channel fields. Improving data collection and tracking processes will enable more accurate customer segmentation, regional analysis, and marketing performance evaluation.
