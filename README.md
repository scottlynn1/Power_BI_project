<!DOCTYPE html>
<body>
  
# Power_BI_project
---
This project uses a dataset from an outdoor sports bike company AdventureWorks and explores several business metrics and tracks the companies performance using prodect level as well as regional and client based data.

Below is the data model consisting of two main data tables and several lookup tables

<img src="images/data_model.png" alt="ratings chart" width='85%' heigth='auto'>

The main source of the data used for this analysis are transactions split between two tables, returns and sales. The lookup tables offer filtering contexts for region, time, customers, and products allowing for a comprehensive analysis of sales and returns from multiple business angles and varying levels of granularity.

## Executive Summary
---
Year to date revenue from beginning of operations in Jan, 2020 to to Jun, 2022 is $24.9 million and Year to date profit is $10.5 million. Trailing 12 month revenue for this quater was $15.5 million, more than 50% percent of total revenue to date, showing considerable growth within the past 12 months.

<img src="images/totals_cards.png" alt="ratings chart" width='60%' heigth='auto'>
<img src="images/revenue_chart.png" alt="ratings chart" width='70%' heigth='auto'>

The bike accessories product category comprised 45% of orders, indicating that customers prefer us for our many bike customization options and repairs.
The clothing product category made up a significantly smallar proportion of orders at 18.5%. This data combined with helmets having a return rate of over 3%, which was 33% higher than the average return rate for all items indicates that the clothing product category is an area that needs attention.
Despite this, monthly returns are down from previous month. Monthly revenue is higher while orders are lower due to more high ticket items being sold than the previous month.

Most of our recent revenue growth is due to the addition of our clothing and accesory product lines.
To maintain goals of 10% growth per month, additional product line expansion and marketing to higher end customers in order to sell higher ticket items are suggested to meet company goals.

Customer data shows that orders from high earning customers yeild greater profits on average due to purchases of high ticket item: however, our total customers that are high earning only comprise 11.3% of our total customers.
Although we do successfully attract equally both blue and white collar workers, we suggest that the marketing teams look into strategies to appeal to higher earning clients.


<img src="images/orders_by_category.png" alt="ratings chart" width='40%' heigth='auto'><span><img src="images/monthly_metrics_card.png" alt="ratings chart" width='40%' heigth='auto'></span>

## International growth

Total orders to date in Europe and the U.K combined represent 7,380 while total orders in Australia reached 6,060. The U.S. totaled 8,700 orders and Canada reached 3,024 orders. While the U.S. is are largest market we have gained a significant footprint overseas to the point that establishing warehouses in those region may offset shipping and logistics costs while building better customer relations.

<img src="images/map.png" alt="ratings chart" width='60%' heigth='auto'>

## Product Level Analysis and Profit

Our goal of 10% growth per month fell short last month in revenue, profit and total orders. This months metric, shown in the middle of each gauge, and the 10% growth target, marked with a bar on the gauge, shows that each metric fell just short in each category by 10%, implying no growth from the previous month.

<img src="images/gauges.png" alt="ratings chart" width='70%' heigth='auto'>

Growth has accelarated for the past 12 months; however, our clothing and accesory product lines came into full production 12 months ago and to achieve the same level of growth, additional product expansion or marketing strategies will need to be employed to meet our goals.

<img src="images/profit_chart.png" alt="ratings chart" width='80%' heigth='auto'>

## Client Level Analysis

Our monthly customers saw a marked increase of 515% just after the start of our accesory and clothing product lines from an average of 330 monthly to 1700 monthly customers. This is evidence of the success of recent product expansions and we suggest additional market research to uncover if any unmet demand can be met.

<img src="images/customers.png" alt="ratings chart" width='80%' heigth='auto'>

Our total orders by customer income level since operations has been split between high income (earning >= 100,000) 11.3%,  average income (earning >= 50,000) 46%, and low income (earning < 50,000) 42%.

<img src="images/orders_by_income.png" alt="ratings chart" width='26%' heigth='auto'><img src="images/orders_by_occupation.png" alt="ratings chart" width='30%' heigth='auto'>
Although order quantity only differ between average and low income customers by 12%, total profit from average income customers is 32% higher, due to purchasing higher ticket products which yeild better profit margins. This same variance with high end customers of higher total profit relative to orders holds true in this data set.
Total orders by customer income level correlate closely with our total customers by income level, indicating that our low proportion, 11.3%, of orders fulfilled by high end customers is due not to high end customers ordering less but more expensive items, rather that our total overall customer base earning a high income is low.

<img src="images/total_profit_by_income.png" alt="ratings chart" width='50%' heigth='auto'><img src="images/total_customers_by_income.png" alt="ratings chart" width='50%' heigth='auto'>

Although we have been able to attract both white and blue collar customers, high earning clients may be an area that we have failed to appeal to.
This demonstrates an area of the market that we have not fully tapped into and recommend the marketing teams to begin looking into ways in which we can appeal to more high end customers.

</body>

