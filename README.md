# Target_CaseStudy_SQL_BigQuery

# Target Brazil Operations Analysis

This project focuses on analyzing Target's operations in Brazil using a dataset encompassing 100,000 orders placed between 2016 and 2018. By diving into various dimensions including order status, pricing, payment and freight performance, customer location, product attributes, and reviews, the analysis uncovers valuable insights into Target's strategies and customer behavior in the Brazilian market.

_______________________________________


## **Overview**

Target, a globally recognized brand, maintains its status as a preferred shopping destination by delivering exceptional value and a superior guest experience. This project focuses on analyzing 8 CSV files, each providing unique perspectives on customer behavior, product attributes, payments, and logistics.

## Dataset Description

Dataset link: https://drive.google.com/drive/folders/1TGEc66YKbD443nslRi1bWgVd238gJCnb

The data is available in 8 csv files:

- customers.csv: Details of consumers, including location and unique IDs.
- sellers.csv: Information about registered sellers, their locations, and IDs.
- order_items.csv: Specifics about ordered items, including product and seller IDs, prices, and shipping details.
- geolocation.csv: Geographical data including zip codes, latitudes, longitudes, and cities.
- payments.csv: Payment-related details such as type, installments, and values linked to order IDs.
- orders.csv: Order-specific information like status, timestamps, and delivery estimates.
- reviews.csv: Customer reviews including scores, comments, and timestamps.
- products.csv: Attributes of products ordered, including categories, descriptions, and dimensions.

## **Data Schema**

![image](https://github.com/Venkatesh-Maroju/Target_CaseStudy_SQL_BigQuery/assets/113306395/f445da40-622f-4c78-8bed-5321c949c6c0)


## **Problem Statement**

The aim was to extract actionable insights and recommendations from the dataset. The project embarked on various exploratory analyses and evaluations to understand customer behavior, market trends, and operational efficiencies within the Brazilian segment.


## **Queries and Results** 

I have denormalized the data from these 8 tables by understanding the data schema, Then performed the analysis on this data, The queries of all the analysis are there in the attched pdf file. The insights drawn from the analysis are attached below with the possible recommendations for the company.

Queries & Results are attached in this doc: https://docs.google.com/document/d/1_jCvT_cPCqVVyOfXAw4wENvYkIUCfcBTbc83VDLxMtM/edit?usp=sharing

## **Key Insights**

- There is a seasonality in drop in number of orders in month of June in both the years, And there is a overall
increase in trend on number of orders as a whole for the given time period
- Most of the orders are placed in the time 1 PM to 6 PM, which is 38.35% of the total orders. And the least orders
are places in the time period of 1 AM to 6AM which is 2.86% of the total orders
- When we see customers distribution across states in brazil 42% of the customers are from SP (Sao Paulo state).
- Out of the 27 states in Brazil, the top 5 states consists of almost 80% of the the customers of target.
- There is an almost 137% increase in the total payment value from the year 2017(Jan to Aug) to 2018(Jan to
Aug) in the months of January to August as we don’t have significant data after august in 2018.
- Average price is highest in the state PB (Paraíba ) along with the highest freight_value
- Average price is lowest in the state SP (Sao Paulo) along with the lowest freight value
- Average time to delivery is highest in the state AP
- Average time to delivery is lowest in the state SP
- Average difference between estimated delivery and actual delivery is highest in state AC, which means delivery
is relly fast, compared to estimated delivery
- Average difference between estimated delivery and actual delivery is lowest in state AL, which means delivery
is not so fast, compared to estimated delivery
- 75% of the customers use credit card as their payment type
- And 20% of the customers use UPI as their payment type
- Only 3.5% of the customers use Vouchers to pay their orders
- And only 1.5% of the customers use debit cars to pay their orders
- Over the period there is significant growth in usage of credit card payments and UPI payments on target
platform, while Debit card and Voucher payments are not increasing
- Around 50 % of the orders are paid within 1 installment only
- While 85% of the orders are paid within the first 6 installments of the payments, So most customers tend to pay
their orders within the first 6 months

## **Future Recommendations**
- Target has to focus on tactics to tackle a seasonal drop in sales in month of June
- Most of the orders are placed in the timeperiod of 1 PM to 6 PM of the day, so target can launch their
exclusive sales offers in this time to attract most number of customers and maximize their revenue.
- And 1 AM to 6 AM is not a good time to launch any products or sale offers, because only 2-3% of the
orders are placed in this time period
- 42% of the customers are from state SP Sao Paulo, So target can focus on special regional offers for this
state as that can maximize their revenue
- Target can collaborate with credit card companies and offer casbacks or vouchers which bring back them
to buy again on target website since 75% of the orders are paid using credit card method
- Around 85% of the customers tend to pay their orders within the first 6 months, So target can consider No cost EMI’s as that will increase the number of customers finishing their payments within first 6 months
even more
- There is a 137% of increase in total revenue for target over the past year, So Target should continue their
strategies for advertising and customer retention tactics, So that they can Increase their revenue even
more in the coming years


## **Contributing**
Feel free to contribute by suggesting improvements, additional analyses, or insights that could enhance the project's scope and depth.
