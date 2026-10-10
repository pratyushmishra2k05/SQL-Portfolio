\# E-Commerce Sales Analysis Using SQL



\## Project Overview



This project analyzes Brazilian e-commerce order data using MySQL to explore sales performance, payment methods, product categories, customer spending, and delivery performance.



The objective is to use SQL queries to answer practical business questions and identify patterns that can help an e-commerce business understand its performance.



\## Tools Used



\- MySQL 8.0

\- MySQL Workbench

\- SQL



\## Dataset



The project uses the Brazilian E-Commerce Public Dataset by Olist, available on Kaggle.



The dataset contains information about orders, customers, products, sellers, payments, reviews, and delivery dates.



Dataset source: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce



\## Business Questions



1\. How many orders were recorded, and how were they distributed by status?

2\. How did order volume change month by month?

3\. What were the total recorded payment values?

4\. Which payment methods contributed the most payment value?

5\. Which product categories generated the highest product sales value?

6\. Which customers had the highest recorded payment totals?

7\. What proportion of delivered orders arrived later than the estimated delivery date?

8\. What was the average time between purchase and delivery?



\## Key Findings



\- \*\*Total recorded payment value:\*\* R$16,008,872.12.

\- \*\*Leading payment method:\*\* Credit cards, with R$12,542,084.19 in recorded payment value.

\- \*\*Leading product category by product sales value:\*\* `beleza\_saude` (health and beauty), among the categories returned by the analysis.

\- \*\*Delivered orders:\*\* 96,478.

\- \*\*Delivered orders recorded as late:\*\* 7,826, approximately 8.11% of delivered orders.

\- \*\*Average purchase-to-delivery time:\*\* 12.50 days.



\## SQL Skills Demonstrated



\- SELECT, WHERE, ORDER BY, and GROUP BY

\- Aggregate functions such as COUNT, SUM, and AVG

\- INNER JOIN and LEFT JOIN

\- CASE expressions

\- Date functions and date differences

\- COALESCE

\- Data aggregation and business KPI calculations



\## Project Structure



```text

ecommerce-sql-analysis/

├── README.md

├── 01\_sales\_overview.sql

├── 02\_revenue\_analysis.sql

├── 03\_product\_analysis.sql

└── 04\_customer\_delivery\_analysis.sql

```



\## Important Notes



\- Payment value is not necessarily equivalent to net revenue or profit.

\- Product sales value is calculated using item prices and excludes freight charges.

\- Delivery performance is calculated using the dates available in the dataset.

\- Product category names are shown in their original Portuguese form in the product analysis.

\- Results reflect the imported dataset and the SQL queries used in this project.



\## Conclusion



This project demonstrates how SQL can be used to transform relational e-commerce data into useful business metrics. It covers sales trends, payment behavior, product performance, and delivery efficiency.

