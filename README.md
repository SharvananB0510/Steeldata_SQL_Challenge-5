# Pub Pricing Analysis
This contribution is part of the 6 challenges presented by Steel Data.

Get the dataset [link](https://www.steeldata.org.uk/sql5.html)

## Challenge Overview
As a Pricing Analyst at 'Pubs "R" Us,' my objective was to delve into the drinks prices and sales data, unraveling key insights to enhance our understanding of the performance across our pub chain.By employing analytical techniques and leveraging sales data, the analysis aims to draw meaningful conclusions about pricing strategies, sales trends, and overall business performance.

## Tables
To tackle the challenge, I worked with the following tables:
1. pubs: Contains information about our pubs, including pub_id, pub_name, city, state, and country.
2. beverages: Stores details about our beverages, such as beverage_id, beverage_name, category, alcohol_content, and price_per_unit.
3. sales: Tracks the sales transactions, including sale_id, pub_id, beverage_id, quantity, and transaction_date.
4. ratings: Stores customer ratings and reviews, with rating_id, pub_id, customer_name, rating, and review.

### Schema
![image](https://github.com/SharvananB0510/Steel_challenge-5/assets/69303949/3ff196c5-f872-404e-927f-b091c36a1f21)

## Questions Answered

1.	How many pubs are located in each country?
2.	What is the total sales amount for each pub, including the beverage price and quantity sold?
3.	Which pub has the highest average rating?
4.	What are the top 5 beverages by sales quantity across all pubs?
5.	How many sales transactions occurred on each date?
6.	Find the name of someone that had cocktails and which pub they had it in.
7.	What is the average price per unit for each category of beverages, excluding the category 'Spirit'?
8.	Which pubs have a rating higher than the average rating of all pubs?
9.	What is the running total of sales amount for each pub, ordered by the transaction date?
10.	For each country, what is the average price per unit of beverages in each category, and what is the overall average price per unit of beverages across all categories?
11.	For each pub, what is the percentage contribution of each category of beverages to the total sales amount, and what is the pub's overall sales amount?
