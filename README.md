# Elevate-Labs-Internship-Task6_Sales_Trend_Analysis_Using_Aggregations

# Sales Trend Analysis Using Aggregations

## Task
- Analyze monthly sales trends using aggregations (SUM, COUNT).
- Group data by year, month, region, product category, and payment method.
- Validate revenue consistency and calculate advanced metrics.
- Provide actionable insights for business decision-making.

## What I Have Done
- I created the `online_sales` table with all required columns matching the Kaggle dataset.
- I wrote a basic query to analyze monthly revenue and order volume, grouping by year and month.
- I validated revenue consistency by comparing `unit_price * units_sold` with `total_revenue`.
- I enhanced the query to include month names using `TO_CHAR` and fixed `GROUP BY` and `ORDER BY` issues.
- I analyzed sales trends by product category, grouping the data accordingly.
- I extended the analysis by region, including validation checks.
- I combined region and product category in my analysis for deeper insights.
- I explored sales trends by region and payment method.
- I added average order value to my regional analysis.
- I used a CTE to calculate year-over-year revenue growth percentage by region.
