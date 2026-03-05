# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior data to understand purchasing patterns, customer preferences, and revenue trends.

The goal of this project is to generate business insights using SQL, Python, and Power BI.

## Tools Used
- Python (Pandas)
- MySQL
- SQL
- Power BI
- Excel

## Dataset
The dataset contains information about:
- Customer ID
- Item Purchased
- Purchase Amount
- Shipping Type
- Review Rating
- Subscription Status

## Data Cleaning
Data cleaning was performed using Python:
- Removed null values
- Converted data types
- Checked duplicates
- Standardized column names

## Key Analysis Performed

1. Top 5 products with highest average review rating
2. Comparison of Standard vs Express shipping purchase amounts
3. Subscriber vs Non-subscriber spending analysis
4. Customer purchase behavior analysis
5. Product popularity analysis

## Example SQL Query

Top 5 products with highest average rating:

SELECT item_purchased,
AVG(review_rating) AS avg_rating
FROM shopping_data
GROUP BY item_purchased
ORDER BY avg_rating DESC
LIMIT 5;

## Dashboard
Power BI dashboard includes:
- Sales by product
- Customer purchase distribution
- Subscription revenue comparison
- Shipping type analysis

## Key Insights
- Subscribers spend more on average than non-subscribers.
- Some products have consistently higher review ratings.
- Express shipping customers tend to make higher value purchases.

## Project Files
- Dataset
- SQL Queries
- Power BI Dashboard
- Project Presentation (PPT)

## Author
Pallavi Amrut
Data Analyst
