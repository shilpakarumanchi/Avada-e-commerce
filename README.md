
# Overview

Avada is an e-commerce platform founded in 2018, offering popular consumer electronics and accessories worldwide. The company holds over 100K records of data related to sales, product offerings, marketing efforts, and operational performance. A thorough analysis of this data has been conducted to provide insights aimed at enhancing Avada's commercial performance.

This project delivers insights and recommendations in the following areas:

1. **Sales Trends**: Month-over-month (MOM) and year-over-year (YOY) growth rates, Average Order Value (AOV), and number of orders.
2. **Product Performance**: Market impact of individual product lines, and identification of highest and lowest grossing items.
3. **Operational Effectiveness**: Evaluation of product delivery times across various product lines and regions.
4. **Marketing Efforts**: Analysis of the effectiveness of the loyalty program introduced to boost sales, along with its future potential.
5. **Refunds**: Examination of refund rates, highly refunded items, and geographical patterns in refund data.

# Tools
- Excel
- Sql
- Tableau

# Data processing
- Original dataset can be found [here](https://github.com/shilpakarumanchi/Avada-e-commerce/blob/fc0e5f3726e21f50835d5f88f68ca6db9604fb8f/Elist_Data_trimmed.xlsx)
- Steps taken to clean the inconsistencies and non-sensical values are detailed [here](https://github.com/shilpakarumanchi/Avada-e-commerce/blob/f541a30ab36c7882ae310ac77c14eef550c869cc/Avada_issue_log.xlsx)
- SQL queries used to derive insigths can be found [here](https://github.com/shilpakarumanchi/Avada-e-commerce/blob/471184cb64ad8eb3ade58a3a6c11e3cae75aae50/sql_code.sql)

# Executive Summary
![image](https://github.com/user-attachments/assets/f0948444-957b-470c-b515-a8daacd20907)


# Deep dive into insights
## Sales 
![image](https://github.com/user-attachments/assets/89f311cd-918d-4df8-920d-b537be04c79b)
- Avada e-commerce processed over 108K orders from 2019 to 2022, generating a total of $28M in sales revenue, with an average order value (AOV) of $260.
- In terms of revenue, 2020 saw the highest at $10M, with an AOV of $300, followed by 2021 with $9M in revenue and an AOV of $255. However, the number of orders was higher in 2021 at 35K, compared to 33K in 2020.
- - The year-over-year (YOY) growth rate was the highest in 2020, with a 101% increase in the number of orders and a 163% increase in sales revenue.
- Overall, sales saw a significant boost from March to December 2020, likely driven by pandemic-related spending.
- Lowest sales revenue was noticed during 2019 ($3.8M), followed by 2022 ($4.9M).
- 
### Seasonality
![Screenshot 2025-02-19 163236](https://github.com/user-attachments/assets/3c044eb2-aa3f-4bb6-952e-81f48b8be917)

- Sales consistently increased in September and December each year, likely due to the back-to-school and holiday shopping seasons.
- The lowest sales were observed between February and June, as well as in October, typically occurring right after the holiday and back-to-school periods.
- However, this trend was less noticeable in 2022, as there was an overall decline in sales, with the final quarter of the year seeing sales drop below 2019 levels.
- 
### Product line
![image](https://github.com/user-attachments/assets/64e894d4-80ac-4a4f-8f9d-07eb1a6d7676)
- The highest-grossing products overall are the 27-inch 4K gaming monitors, Apple AirPods, MacBook Air laptops, and ThinkPad laptops, which together account for $27M in revenue, representing 96% of total sales.
- The top two revenue-generating products are the 27-inch 4K gaming monitors and MacBook Air laptops, which together contribute $17.5M in revenue, making up 63% of total sales.
- On the other hand, the least grossing products include the Bose SoundSport headphones, Apple iPhone, Samsung charging cable pack, and Samsung webcam, which collectively generate $1M in revenue, or 4% of total sales.
- Laptops have the highest Average Order Value (AOV), with the MacBook Air laptop at $1,500, followed by the ThinkPad laptop at $1,100. The lowest AOV is seen with the Samsung charging cable pack, priced at $20.
- Apple AirPods are the most frequently purchased items, with a total of 48K units sold, representing 45% of all orders, followed by the 27-inch 4K gaming monitor with 23K units sold, making up 22% of total orders.
- Bose soundsport headphones are the least purchased items with a total of 27 units sold, representing 0.02% of all orders, followed by Apple iphone with 288 units sold, making up 0.3% of total orders.
  
## Product Delivery
![delivery](https://github.com/user-attachments/assets/35689546-d8fb-4e7f-a5f4-d62cd5f46bad)
- On average, Avada takes 2 days to ship and 8 days to deliver a product, a trend that has remained consistent across all four global regions and eight product lines.
- However, the shipping time for the Samsung Charging Cable to EMEA increased to 9 days, while the shipping time for the Apple AirPods headphones in NA was 6 days.
- As a result, the delivery times for these products in EMEA and NA were extended to 15 and 11 days, respectively.
  
## Loyalty Program			
![image](https://github.com/user-attachments/assets/7f3d3eab-1507-4b27-92cf-bb0167f6e33f)
- Overall, customers who are not part of the loyalty program generated $17M in sales revenue, which is 61% higher than the $11M in sales revenue from loyalty program members.
- However, this trend doesn't hold when broken down by year. In 2019 and 2020, loyalty program customers contributed 11% and 29% of the sales revenue, respectively. This trend reversed in 2021 and 2022, with loyalty program customers accounting for 53% and 55% of the sales revenue.
- Additionally, the Average Order Value (AOV) for loyalty program customers has been steadily increasing over the years. By 2022, the AOV for loyalty program members ($245) surpassed that of non-loyalty program customers ($214).
  
## Refunds
![Screenshot 2025-02-19 124221](https://github.com/user-attachments/assets/fd33f78a-f8d0-4686-a7f2-2e1a11815d82)
- Since 2019, a total of 5,379 products have been refunded, resulting in an overall refund rate of 5%.
- The highest refund rates are seen with the ThinkPad Laptop (12%) and MacBook Air Laptop (11%), while the products with the most refunds are the Apple AirPods Headphones (2,636) and the 27-inch 4K Gaming Monitor (1,444).
- Among the refunded items, North America has the highest refund rate at 56%, followed by EMEA with 27%.
- Refunds peaked in 2020 and the first half of 2021, likely correlating with the surge in sales during that period.
- There have been no refunds since July 2021, which requires further investigation.

# Recommendations
## Sales 
**Maximize the Success of High-Grossing Products, most frequently purchased products & Peak Sales Periods**: Since the 27-inch 4K gaming monitors, Apple AirPods, MacBook Air laptops, and ThinkPad laptops account for a significant portion of the revenue (96%), continue to prioritize these items in your product offerings. Highlight them in promotions, ensure sufficient stock, and consider seasonal discounts (between  September and December) or limited-time offers & create loyalty incentives.

**Revitalize Low-Grossing Products**: Products like the Bose SoundSport headphones, Apple iPhone, Samsung charging cable pack, and Samsung webcam, which make up only 4% of the sales. Assess the reasons behind their low sales (e.g., lack of visibility, consumer demand, or quality concerns) and strategize on how to boost their performance by discounts, improved marketing, or product repositioning.

**Leverage High AOV Products**: Since laptops have the highest AOV, emphasize their premium status and the value they offer. Consider offering financing or payment plans for customers to make these higher-priced products more accessible.

**Improve the Sales of underperforming items & off-Peak months**: The Bose SoundSport headphones and Apple iPhone have the lowest purchase frequency, and may need further analysis to understand customer preferences. It might be useful to assess whether pricing adjustments, new marketing strategies, or promotional efforts are needed to boost their visibility and appeal. Given that sales dip between February and June, as well as in October, consider introducing promotions, limited-time offers, or new product launches during these months to stimulate interest and maintain sales momentum. 

## Product Delivery
- Measures should be taken to ship the product on the day of purchase, so that delivery time can be reduced by 25%. 
## Loyalty Program
**Focus on Loyalty Program Expansion**: Given that loyalty program customers are now contributing a larger share of sales revenue (53% in 2021 and 55% in 2022), it would be beneficial to further invest in the loyalty program. This could include promoting exclusive benefits, offering personalized incentives, or increasing customer engagement to attract more non-loyalty customers to join the program.

**Leverage Increasing AOV**: Since the AOV for loyalty program customers has been steadily increasing, this indicates that these customers are more likely to spend more per transaction. You could design targeted marketing campaigns to further increase their spending, such as introducing tiered rewards or limited-time offers that encourage larger purchases.

**Analyze Non-Loyalty Customer Segments**: While non-loyalty customers generated higher overall revenue ($17M), this group could be a valuable target for conversion to the loyalty program. Consider strategies to encourage these customers to join, such as offering an attractive signup bonus, highlighting the benefits of the loyalty program, or providing personalized promotions.

**Optimize AOV for Non-Loyalty Customers**: Although the AOV for non-loyalty customers is lower ($214), it's still substantial. Offering incentives like free shipping, bundles, or limited-time discounts could help increase the AOV for this group, potentially bringing them closer in line with loyalty program customers in terms of spending.
## Refunds
**Investigate the high refund rates for ThinkPad Laptops and MacBook Air Laptops**: Check if there are consistent issues with these models (e.g., hardware defects, software issues, compatibility problems) and whether these problems are being addressed in newer models or firmware updates.

**Analyze the reasons for high refund numbers of AirPods and Gaming Monitors**: Consider whether the high volume of refunds is due to quality issues, product recalls, or customer expectations that are not being met.

**Focus on North American Refunds**: Explore if there's a specific region or customer base in North America where refunds are particularly high, and whether there are factors related to distribution channels, product usage, or customer service that might be contributing to this trend.

**Examine the sudden drop in refunds after July 2021**:Verify if this is due to improved product quality or operational changes. Ensure there is no reporting error or data anomaly causing this gap.


## Entity Relationship Diagram (ERD)
The following image provides the Entity Relation Diagram (ERD) of the current database.
![ERD](https://github.com/user-attachments/assets/eb9bdbdc-5ea5-451a-8a98-cbcb33d1ef6c)

