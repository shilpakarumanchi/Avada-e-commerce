
# Overview

Avada is an e-commerce platform established in 2018, selling the most popular consumer electronics and accessories at a global scale.
The company has >100k records of data on sales, product offerings, marketting efforts and operational effectiveness. 
A comprehenssive analysis has been performed on this data inorder to provide insights to improve Avada's commercial performance.
This project provides insights and recommendations on the following areas:
1. Sales Trends: Month Over Month (MOM) and Year Over Year (YOY) growth rates, Average Order Value (AOV) & Number of orders.
2. Product performance: Market impact of individual product lines.
3. Operational effectiveness: Asessment of product delivery times across the product line and across the globe.
4. Marketting efforts: Assessment of effectiveness of the loyalty program that has been inititated to improve sales and its future.
5. Refinds: Refund rates, Highly refunded items, AOV.

## ERD
The following image provides the Entity Relation Diagram (ERD) of the current database.

![Image ALT](https://github.com/shilpakarumanchi/Avada-e-commerce/blob/cc68913111f297ffdfe4c47ef0bf36e37101e2fd/ERD.png)

# Data processing
- Steps taken to clean the inconsistencies and non-sensical values are detailed [here](https://github.com/shilpakarumanchi/Avada-e-commerce/blob/f541a30ab36c7882ae310ac77c14eef550c869cc/Avada_issue_log.xlsx).
- SQL queried used to derive insigths can be found [here](https://github.com/shilpakarumanchi/Avada-e-commerce/blob/471184cb64ad8eb3ade58a3a6c11e3cae75aae50/sql_code.sql)

# Data insights
## Sales 
![image](https://github.com/user-attachments/assets/a7060bcd-98e1-4ee7-b4d9-f8834f15b458)

- Avada e-commerce has obtained over 108k orders between 2019 and 2022, and generated a total of $28 M in sales revenue, with an AOV of $260.
- Between 2019 and 2022, 2020 has the highest revenue of $10M with an AOV of $300 followed by 2021 with 9M in revenue and an AOV of $255. However the number of orders were higher in 2021 with 35k followed by 2020 with 33k.
- YOY growth rate was highest for 2020, with 101% increase in the number of orders and 163% increase in sales revenue when compared to 2019.
- Over all sales have substantially increased from March 2020 till December 2020, possibly due to pandemic spending.

![image](https://github.com/user-attachments/assets/9828cec6-52e3-4d45-8280-78988ddd32ae)
	
### Product line
![image](https://github.com/user-attachments/assets/512e4d86-d5c6-4d50-9a18-1c9f5db6b5c7)

- Overall 27in 4k gaming monitors, Apple Airpods, Macbook Air Laptops and Thinkpad Laptops are the highest grossing products, adding up to a total of $27M that corresponds to 96% of sales revenue. 
- Top 2 grossing products include 27in 4k gaming monitors, Macbook Air Laptops, adding up to a total of $17.5M in revenue that corresponds to 63% of total sales revenue. 
- On the contrary, Bose soundsport headphones, Apple Iphone, Samsung charging cable pack & Samsung webcam are the least grossing products, adding up to a total of $1M in revenue that corresponds to 4% of total sales revenue.
### Seasonality
![image](https://github.com/user-attachments/assets/c34a8fe1-0b60-4e48-a93c-0a2b3a254646)

- Within each year, sales have increased during the months of September and December that can be attributed to back to school and holiday seasons.
- Lowest sales were noticed between February and June and in October, i.e. right after the holidays and back to school seasons. 

## Product Delivery
- On average Avada requires 2 days to ship and 8 days to deliver a product. This trend has been consistent across the four global regions and 8 product lines.
## Loyalty Program
- Overall, customers not in loyalty program made sales revenue of $17M, that is 64% higher than customers in loyalty progam with sales revenue of $11M.
- When we look at the yearly breakdown, in 2019 and 2020 customers in loyalty program contributed up to 11% and 29% of the total sales revenue. However in 2021 and 2022 customers in loyalty program contributed up to 53% and 55% of the total sales revenue, reversing the overall trend.
- In addition, the AOV is gradually increasing over the years for customers in loyalty program and in 2022 the AOV of loyalty program customers is $245 which is higher than $214, the the AOV of customers not in loyalty program.
  
## Refunds
![refunds](https://github.com/user-attachments/assets/4d637900-0cc5-408d-8bdc-e1fc5c301e24)

- Since 2019, a total of 5379 products have been refunded that corresponds to a overall refund rate of around 5%.
- ThinkPad Laptop (12%) and Macbook Air Laptop (11%) have the highest refund rates, while the Apple Airpods Headphones (2,636) and 27in 4K Gaming Monitor (1,444) have the highest number of refunds.

# Recommendations
## Sales 
Rebates or special offers can be introduced during the lowest sales revenue tiems of the year (i.e. between February and April and during October) inorder to encourage customer spending.
Inorder to improve operational efficiency Avada can narrowdown the product line to the highest grossing products i.e. 27in 4k gaming monitors, Apple Airpods, Macbook Air Laptops and Thinkpad Laptops.
## Product Delivery
Measures should be taken to ship the product on the day of purchase, so that delivery time can be reduced by 25%. 
## Loyalty Program
Total sales revenue and AOV of loyalty program customers has been increasing ove the past year, giving positive indications that the loyalty program can be continued.
## Refunds
Overall refund percentage is 5%, indicating that Avada is providing quality products and receiving high customer satisfaction.
However, measures can be taken to minimize refund rates for Thinkpad Laptops and Macbook Air Laptops - the two products that had high refund rates.
There were no refunds in 2022 that needs to be looked into.
