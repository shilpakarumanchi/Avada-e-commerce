
# Overview

Avada is an e-commerce platform founded in 2018, offering popular consumer electronics and accessories worldwide. The company holds over 100K records of data related to sales, product offerings, marketing efforts, and operational performance. A thorough analysis of this data has been conducted to provide insights aimed at enhancing Avada's commercial performance.

This project delivers insights and recommendations in the following areas:

1. **Sales Trends**: Month-over-month (MoM) and year-over-year (YoY) growth rates, Average Order Value (AOV), and number of orders.
2. **Product Performance**: Market impact of individual product lines, and identification of highest and lowest grossing items.
3. **Operational Effectiveness**: Evaluation of product delivery times across various product lines and regions.
4. **Marketing Efforts**: Analysis of the effectiveness of the loyalty program introduced to boost sales, along with its future potential.
5. **Refunds**: Examination of refund rates, highly refunded items, and geographical patterns in refund data.

# Data processing
- Original dataset in Excel can be found [here](https://github.com/shilpakarumanchi/Avada-e-commerce/blob/fc0e5f3726e21f50835d5f88f68ca6db9604fb8f/Elist_Data_trimmed.xlsx)
- Steps taken to clean the inconsistencies and non-sensical values are detailed [here](https://github.com/shilpakarumanchi/Avada-e-commerce/blob/04d40f47001832f8343bd352032b47cf970bf0ce/Avada_issue_log_git.xlsx)
- SQL queries used to derive insigths can be found [here](https://github.com/shilpakarumanchi/Avada-e-commerce/blob/471184cb64ad8eb3ade58a3a6c11e3cae75aae50/sql_code.sql)
- Data analysis in Excel can be found [here](https://github.com/shilpakarumanchi/Avada-e-commerce/blob/a087a4413d174ad601b6fcfbed092c1fd3b2eef5/Avada_ecommerce_Analysis_git.xlsx)
- ERD can be found [here](https://github.com/shilpakarumanchi/Avada-e-commerce/blob/edc29c3d9a457949844e5f6d8b8bedff263e9360/ERD_grey.png)

# Executive Summary
![image](https://github.com/user-attachments/assets/f0948444-957b-470c-b515-a8daacd20907)

1. **Pandemic-Driven Demand Spike (2020-2021):** Sales of electronics, particularly **27-inch 4K gaming monitors, MacBook Air laptops, Apple AirPods, and iPhones**, saw significant increases during the COVID-19 pandemic. This trend aligns with increased remote work, virtual communication, and home entertainment needs.  
2. **Peak Sales Periods:** Spikes in sales occurred during key months such as **January, September, and December**, suggesting seasonal demand (possibly influenced by mid-year sales, back-to-school, and holiday shopping).  
3. **Declining Trend Post-2021:** After peaking in 2021, sales began to decline throughout 2022 aligning with 2019 sales by the last quarter of 2022, indicating a potential market saturation or reduced consumer demand post-pandemic.  
4. **Lower-Volume Products:** Items like **Samsung Charging Cable Packs and Webcams** remained relatively stable in sales without major fluctuations, likely reflecting consistent but lower demand.
*NOTE: The figure includes dynamic filters that can be utilized in Excel.

# Insights Deep Dive
## Sales 
<p align="center">
  <img src="https://github.com/user-attachments/assets/4eafd840-efad-401b-9253-d78b4d6219b7">
</p>
- Avada e-commerce processed over 108K orders from 2019 to 2022, generating a total of $28M in sales revenue, with an average order value (AOV) of $260.
- In terms of revenue, 2020 saw the highest at $10M, with an AOV of $300, followed by 2021 with $9M in revenue and an AOV of $255. However, the number of orders was higher in 2021 at 35K, compared to 33K in 2020.
- The year-over-year (YOY) growth rate was the highest in 2020, with a 101% increase in the number of orders and a 163% increase in sales revenue.
- Overall, sales saw a significant boost from March to December 2020, likely driven by pandemic-related spending.
- Lowest sales revenue was noticed during 2019 ($3.8M), followed by 2022 ($4.9M).
  
### Seasonality
![Screenshot 2025-02-19 163236](https://github.com/user-attachments/assets/3c044eb2-aa3f-4bb6-952e-81f48b8be917)

- Sales consistently increased in September and December each year, likely due to the back-to-school and holiday shopping seasons.
- The lowest sales were observed between February and June, as well as in October, typically occurring right after the holiday and back-to-school periods.
- However, this trend was less noticeable in 2022, as there was an overall decline in sales, with the final quarter of the year seeing sales drop below 2019 levels.
  
### Product line
<p align="center">
  <img src="https://github.com/user-attachments/assets/62fbfe72-38dc-4bd0-8787-e371fd0caea3">
</p>
- The highest-grossing products overall are the 27-inch 4K gaming monitors, Apple AirPods, MacBook Air laptops, and ThinkPad laptops, which together account for $27M in revenue, representing 96% of total sales.
- The top two revenue-generating products are the 27-inch 4K gaming monitors and MacBook Air laptops, which together contribute $17.5M in revenue, making up 63% of total sales.
- On the other hand, the least grossing products include the Bose SoundSport headphones, Apple iPhone, Samsung charging cable pack, and Samsung webcam, which collectively generate $1M in revenue, or 4% of total sales.
- Laptops have the highest Average Order Value (AOV), with the MacBook Air laptop at $1,500, followed by the ThinkPad laptop at $1,100. The lowest AOV is seen with the Samsung charging cable pack, priced at $20.
- Apple AirPods are the most frequently purchased items, with a total of 48K units sold, representing 45% of all orders, followed by the 27-inch 4K gaming monitor with 23K units sold, making up 22% of total orders.
- Bose soundsport headphones are the least purchased items with a total of 27 units sold, representing 0.02% of all orders, followed by Apple iphone with 288 units sold, making up 0.3% of total orders.
  
## Product Delivery
- On average, Avada takes 2 days to ship and 8 days to deliver a product—a trend that holds across all four global regions and eight product lines, despite some anomalies.  
- Two products stand out with significantly longer shipping times than the rest: Samsung Charging Cable in EMEA takes 9 days, and Apple AirPods Headphones in North America take 6 days.  
- Consequently, the average delivery times for these products are extended to 15 days in EMEA and 11 days in North America.  
- In contrast, Bose Soundsport Headphones have slightly lower shipping times in APAC and LATAM, averaging 1 day.  
- When factoring in these anomalies, the overall average shipping time increases to 3 days in EMEA and 4 days in North America, with the average delivery time rising to 9 days.
  
## Loyalty Program			
<p align="center">
  <img src="https://github.com/user-attachments/assets/dfa66220-545f-470f-bf2c-3a45b3d33ed9">
</p>
- Overall, customers who are not part of the loyalty program generated $17M in sales revenue, which is 61% higher than the $11M in sales revenue from loyalty program members.
- However, this trend doesn't hold when broken down by year. In 2019 and 2020, loyalty program customers contributed 11% and 29% of the sales revenue, respectively. This trend reversed in 2021 and 2022, with loyalty program customers accounting for 53% and 55% of the sales revenue.
- Additionally, the Average Order Value (AOV) for loyalty program customers has been steadily increasing over the years. By 2022, the AOV for loyalty program members ($245) surpassed that of non-loyalty program customers ($214).
  
## Refunds
<p align="center">
  <img src="https://github.com/user-attachments/assets/b86984ff-caea-4acd-94cf-9543a721af20">
</p>
- Since 2019, a total of 5,379 products have been refunded, resulting in an overall refund rate of 5% (Ref: Table - Product line section).
- The highest refund rates are seen with the ThinkPad Laptop (12%) and MacBook Air Laptop (11%), while the products with the most refunds are the Apple AirPods Headphones (2,636) and the 27-inch 4K Gaming Monitor (1,444).
- North America has the highest number of refunded items at 2,998, making up 56%, followed by EMEA with 1,462 refunds, accounting for 27%.
- Refunds peaked in 2020 and the first half of 2021, likely correlating with the surge in sales during that period.
- There have been no refunds since July 2021, which requires further investigation.

# Recommendations
## Sales 
**Sales surge during the COVID-19 pandemic**: The COVID-19 pandemic significantly boosted electronics sales (YOY growth rate in 2020: 101%) due to lifestyle shifts toward remote work, education, and entertainment. However, as restrictions eased, demand declined, suggesting a return to normal consumption patterns. This insight is crucial for inventory planning and marketing strategies in the consumer electronics sector.

**Maximize the Success of High-Grossing Products, most frequently purchased products & Peak Sales Periods**: Since the 27-inch 4K gaming monitors, Apple AirPods, MacBook Air laptops, and ThinkPad laptops account for a significant portion of the revenue (96%), continue to prioritize these items in product offerings. Highlight them in promotions, ensure sufficient stock, and consider seasonal discounts (between  September and December) or limited-time offers & create loyalty incentives.

**Leverage High AOV Products**: Since laptops have the highest AOV (≈$1300), emphasize their premium status and the value they offer. Consider offering financing or payment plans for customers to make these higher-priced products more accessible.

**Improve the Sales of underperforming items & off-Peak months**: The four lowest-selling products contribute only 4% of total sales. Additionally, February to June and October are identified as off-peak months. It is essential to analyze the factors contributing to low sales of these underperforming items, such as lack of visibility or quality concerns. To enhance their performance and boost sales during off-peak months, consider strategies like pricing adjustments, limited-time offers, or launching new products during these periods.

## Product Delivery
**Optimize Shipping Processes**: Implement measures to ensure same-day or next-day shipping across all regions to reduce overall shipping delays.

**Investigate Shipping Anomalies & Improve Logistics in High-Delay Regions**: Analyze the causes behind the extended shipping times for Samsung Charging Cable in EMEA (9 days) and Apple AirPods Headphones in North America (6 days) to identify and resolve inefficiencies, bring delivery times closer to the global average.
  
## Loyalty Program
**Focus on Loyalty Program Expansion**: Given that loyalty program customers are now contributing a larger share of sales revenue (53% in 2021 and 55% in 2022), it would be beneficial to further invest in the loyalty program. This could include promoting exclusive benefits, offering personalized incentives, or increasing customer engagement to attract more non-loyalty customers to join the program.

**Leverage Increasing AOV**: Since the AOV for loyalty program customers has been steadily increasing (AOV $207 in 2019 Vs $245 in 2022), this indicates that these customers are more likely to spend more per transaction. Targeted marketing campaigns cn be designed to further increase their spending, such as introducing tiered rewards that encourage larger purchases.

**Analyze Non-Loyalty Customer Segments and Optimize AOV**: Although non-loyalty customers have a lower AOV ($214 in 2022), they contributed higher overall revenue ($17M), making them a valuable target for conversion to the loyalty program. To encourage sign-ups and to help increase AOV, consider strategies such as offering an attractive signup bonus, emphasizing program benefits, or providing personalized promotions like free shipping, product bundles, or limited-time discounts.

## Refunds

**Analyze the reasons for high refund rates  and high refund numbers**: Highest refund rates are seen with the ThinkPad Laptop (12%) and MacBook Air Laptop (11%) and highest number of refunds are seen the Apple AirPods Headphones (2,636) and the 27-inch 4K Gaming Monitor (1,444).  Check if there are consistent issues with these items (e.g., hardware defects, software issues, compatibility problems, product recalls, or customer expectations) and whether these problems are being addressed in newer models or firmware updates.

**Focus on North American Refunds**: North America has the highest number of refunded items at 2,998 (56% of total refunds). Explore if there's a specific region or customer base in North America where refunds are particularly high, and whether there are factors related to distribution channels, product usage, or customer service that might be contributing to this trend.

**Examine the sudden drop in refunds after July 2021**: Verify if this is due to improved product quality or operational changes. Ensure there is no reporting error or data anomaly causing this gap.

## Entity Relationship Diagram (ERD)
The following image provides the Entity Relation Diagram (ERD) of the current database.
![ERD](https://github.com/user-attachments/assets/eb9bdbdc-5ea5-451a-8a98-cbcb33d1ef6c)

