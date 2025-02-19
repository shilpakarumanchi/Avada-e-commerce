
# Overview

Avada is an e-commerce platform established in 2018, selling the most popular consumer electronics and accessories at a global scale.
The company has >100k records of data on sales, product offerings, marketting efforts and operational effectiveness. 
A comprehenssive analysis has been performed on this data inorder to provide insights to improve Avada's commercial performance.
This project provides insights and recommendations on the following areas:
1. Sales Trends: Month Over Month (MOM) and Year Over Year (YOY) growth rates, Average Order Value (AOV) & Number of orders.
2. Product performance: Market impact of individual product lines.
3. Operational effectiveness: Asessment of product delivery times across the product line and across the globe.
4. Marketting efforts: Assessment of effectiveness of the loyalty program that has been inititated to improve sales and its future.
5. Refunds: Refund rates, Highly refunded items, AOV.

# Tools
- Excel
- Sql
- Tableau

# Data processing
- Original dataset can be found [here]
- Steps taken to clean the inconsistencies and non-sensical values are detailed [here](https://github.com/shilpakarumanchi/Avada-e-commerce/blob/f541a30ab36c7882ae310ac77c14eef550c869cc/Avada_issue_log.xlsx).
- SQL queries used to derive insigths can be found [here](https://github.com/shilpakarumanchi/Avada-e-commerce/blob/471184cb64ad8eb3ade58a3a6c11e3cae75aae50/sql_code.sql)

# Executive Summary

# Data insights
## Sales 
	
![image](https://github.com/user-attachments/assets/89f311cd-918d-4df8-920d-b537be04c79b)


- Avada e-commerce has obtained over 108k orders between 2019 and 2022, and generated a total of $28 M in sales revenue, with an AOV of $260.
- Between 2019 and 2022, 2020 has the highest revenue of $10M with an AOV of $300 followed by 2021 with 9M in revenue and an AOV of $255. However the number of orders were higher in 2021 with 35k followed by 2020 with 33k.
- YOY growth rate was highest for 2020, with 101% increase in the number of orders and 163% increase in sales revenue when compared to 2019.
- Over all sales have substantially increased from March 2020 till December 2020, possibly due to pandemic spending.

### Seasonality
![image](https://github.com/user-attachments/assets/7cafa699-251f-4785-93ea-dab9789f8705)

- Within each year, sales have increased during the months of September and December that can be attributed to back to school and holiday seasons.
- Lowest sales were noticed between February and June and in October, i.e. right after the holidays and back to school seasons. 
### Product line
![image](https://github.com/user-attachments/assets/64e894d4-80ac-4a4f-8f9d-07eb1a6d7676)

- Overall 27in 4k gaming monitors, Apple Airpods, Macbook Air Laptops and Thinkpad Laptops are the highest grossing products, adding up to a total of $27M that corresponds to 96% of sales revenue. 
- Top 2 grossing products include 27in 4k gaming monitors, Macbook Air Laptops, adding up to a total of $17.5M in revenue that corresponds to 63% of total sales revenue. 
- On the contrary, Bose soundsport headphones, Apple Iphone, Samsung charging cable pack & Samsung webcam are the least grossing products, adding up to a total of $1M in revenue that corresponds to 4% of total sales revenue.
## Product Delivery
![delivery](https://github.com/user-attachments/assets/35689546-d8fb-4e7f-a5f4-d62cd5f46bad)

- On average, Avada takes 2 days to ship and 8 days to deliver a product, a trend that has remained consistent across all four global regions and eight product lines.
- However, the shipping time for the Samsung Charging Cable to EMEA increased to 9 days, while the shipping time for the Apple AirPods headphones in NA was 6 days.
- As a result, the delivery times for these products in EMEA and NA were extended to 15 and 11 days, respectively.
## Loyalty Program
					
![image](https://github.com/user-attachments/assets/7f3d3eab-1507-4b27-92cf-bb0167f6e33f)


- Overall, customers not in loyalty program made sales revenue of $17M, that is 61% higher than customers in loyalty progam with sales revenue of $11M.
- However this trend is not consistent with yearly breakdown. In 2019 and 2020 customers in loyalty program contributed to 11% and 29% of the sales revenue. This trend has reversed in 2021 and 2022 with 53% and 55% of sales revenue from the customers in loyalty program.
- In addition, the AOV is gradually increasing over the years for customers in loyalty program, and in 2022 the AOV of loyalty program customers ($245) is higher than the AOV of customers not in loyalty program ($214).
  
## Refunds
![Screenshot 2025-02-19 124221](https://github.com/user-attachments/assets/fd33f78a-f8d0-4686-a7f2-2e1a11815d82)


- Since 2019, a total of 5379 products have been refunded that corresponds to a overall refund rate of 5%.
- Highest refund rates correspond to ThinkPad Laptop (12%) and Macbook Air Laptop (11%), while the Apple Airpods Headphones (2,636) and 27in 4K Gaming Monitor (1,444) have the highest number of refunds.
- North America has the highest refund rate (56%), followed by EMEA (27%).

# Recommendations
## Sales 
- Rebates or special offers can be introduced during the lowest sales revenue tiems of the year (i.e. between February and April and during October) inorder to encourage customer spending.
- Inorder to improve operational efficiency Avada can narrowdown the product line to the highest grossing products i.e. 27in 4k gaming monitors, Apple Airpods, Macbook Air Laptops and Thinkpad Laptops.
## Product Delivery
- Measures should be taken to ship the product on the day of purchase, so that delivery time can be reduced by 25%. 
## Loyalty Program
Total sales revenue and AOV of loyalty program customers has been increasing ove the past year, giving positive indications that the loyalty program can be continued.
## Refunds
- Overall refund percentage is 5%, indicating that Avada is providing quality products and receiving high customer satisfaction.
- However, measures can be taken to minimize refund rates for Thinkpad Laptops and Macbook Air Laptops - the two products that had high refund rates.
- There were no refunds in 2022 that needs to be looked into.

## Entity Relationship Diagram (ERD)
The following image provides the Entity Relation Diagram (ERD) of the current database.
![ERD](https://github.com/user-attachments/assets/eb9bdbdc-5ea5-451a-8a98-cbcb33d1ef6c)

