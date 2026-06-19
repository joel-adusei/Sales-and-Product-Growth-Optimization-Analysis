# Sales-and-Product-Growth-Optimization-Analysis

## NOURAMART SALES OPTIMIZATION ANALYSIS

![image]()



Disclaimer⚠️: All info and reports in this repository do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual. All info are dummy are design to demonstrate my capabilities of using SQL to perform advance analytics


## INTRODUCTION

This project analyzes sales performance, product distribution, and operational efficiency for NouraMart Consumer Goods, 
a leading FMCG company in United Kingdom. Using sales data across products, regions, and distribution channels, the analysis identifies business trends, evaluates performance, and generates actionable insights to support data-driven decision-making and business growth using Structured Query Language (SQL).

## PROBLEM STATEMENT

As NouraMart Consumer Goods expands across Nigeria, the company needs greater visibility into its sales performance, product portfolio, and customer trends. Understanding top-performing products, product categories, customer locations, and purchasing patterns is essential for improving decision-making, optimizing operations, and driving business growth through data-driven insights.

## AIM OF THE PROJECT

- Explore and understand NouraMart's sales, product, and customer data.
- Identify product categories and evaluate product pricing across the portfolio.
- Determine the most valuable products and classify products based on price ranges.
- Examine customer demographics and geographical distribution.
- Analyze order quantities and generate insights to support business decision-making.

## SKILL & CONCEPT DEMOSTRATED

**Business Overview:** Understanding the business, and their expectations.

**Data Overview:** Looking into the data and exploring it’s relevance to the business.

**Data Extraction:** Extract product, order, and customer data from the company's DataBase.

**SQL Queries:** Write SQL queries to extract key metrics and insights from the data.

**Recommendations:** Provide business recommendations based on the analysis.

## DATA ANALYSIS

This query retrieves key information from NouraMart's sales dataset, including order details, product information, and customer demographics. It captures important metrics such as order dates, quantities sold, selling prices, revenue, profit, product categories, customer locations, gender, and age groups. By consolidating these business-critical variables, the query provides a comprehensive overview of sales activities, product performance, and customer characteristics, forming the foundation for further analysis and data-driven decision-making at NouraMart.

![image](https://github.com/joel-adusei/Sales-and-Product-Growth-Optimization-Analysis/blob/main/assets/Q1.JPG?raw=true)


This query identifies the cities from which NouraMart receives orders and evaluates the total profit generated from each location. By grouping sales data by customer city and calculating the summed profit, it highlights the most profitable cities and ranks them based on their contribution to overall business performance. This provides valuable insight into geographic profitability and supports data-driven decisions for targeted sales, marketing, and resource allocation strategies.

![image](https://github.com/joel-adusei/Sales-and-Product-Growth-Optimization-Analysis/blob/main/assets/Q2.JPG?raw=true)


This query presents the data output of the various product categories available at Nouramart, highlighting a total of six distinct categories. By showcasing these categories, the query provides insights into the product diversity within the store, allowing for a better understanding of inventory composition and potential areas for growth or optimization in product offerings.

![image](https://github.com/joel-adusei/Sales-and-Product-Growth-Optimization-Analysis/blob/main/assets/Q3.JPG?raw=true)



This query outputs the product categories along with the corresponding number of products in each category. The results reveal that **Accessories** leads with the highest count of 458 products, followed by **Games**, while **Electronics** has the lowest count with 272 products. This analysis offers valuable insights into the distribution of products across categories, helping to identify areas of focus for inventory optimization and potential adjustments in product availability.

![image](https://github.com/joel-adusei/Sales-and-Product-Growth-Optimization-Analysis/blob/main/assets/Q4.JPG?raw=true)


This query displays the average price of products in each category, revealing that **Accessories** has the highest average price at £10622, followed by **Electronics**. In contrast, **Games** has the lowest average price at £10400, largely due to the quantity and nature of products in that category. This analysis provides insights into price distribution across categories, helping to understand the value of products offered and informing pricing and inventory strategies.

![image](https://github.com/joel-adusei/Sales-and-Product-Growth-Optimization-Analysis/blob/main/assets/Q5.JPG?raw=true)


This query displays the total quantity of products ordered in **2025**, revealing that **10,976** products were ordered were ordered in 2025. This analysis providing valuable insights into sales trends and help to forecast future inventory needs.

![image](https://github.com/joel-adusei/Sales-and-Product-Growth-Optimization-Analysis/blob/main/assets/Q7.JPG?raw=true)


This query evaluates whether a product's price is more than £10,000 creating a new column that indicates if a product is **"Above 10,000"** or **"Below or Equal to 10,000."** This classification provides a clear view of the distribution of high-value versus more affordable products, aiding in pricing strategy and product segmentation.

![image](https://github.com/joel-adusei/Sales-and-Product-Growth-Optimization-Analysis/blob/main/assets/Q8.JPG?raw=true)


## RECOMMENDATIONS

Based on the analysis of NouraMart’s sales, product, and customer data, several key recommendations can be made to improve business performance and support strategic decision-making.

Firstly, the company should focus on strengthening its presence in high-profit cities by increasing targeted marketing efforts and improving product availability in these regions. Since certain cities generate significantly higher profit, allocating more resources such as promotions, logistics support, and stock availability to these locations will help maximize revenue.

Secondly, NouraMart should review its product category distribution to ensure a more balanced inventory strategy. Categories with lower product counts or lower profitability should be assessed for potential expansion or restructuring, while high-performing categories should be further optimized and promoted.

In addition, pricing strategies should be refined based on category-level insights. High-value products (above £10,000) should be strategically positioned to maximize profitability, while lower-priced products should be leveraged to attract a broader customer base and increase sales volume.

Furthermore, the company should align inventory planning with demand trends, particularly the total quantity of products ordered in 2025. This will help reduce stock imbalances, prevent overstocking or stockouts, and improve operational efficiency.

Finally, NouraMart should continue leveraging data analytics to monitor customer behavior, regional performance, and product trends regularly. This will ensure more accurate forecasting, better decision-making, and sustained business growth.

