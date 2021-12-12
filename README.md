# Customer-Personality-Analysis

Analysis of a given customer based on the below information about the customer:

Attributes
- People ID: Customer's unique identifier
- Year_Birth: Customer's birth year
- Education: Customer's education level 
- Marital_Status: Customer's marital status 
- Income: Customer's yearly household income 
- Kidhome: Number of children in customer's household 
- Teenhome: Number of teenagers in customer's household 
- Dt_Customer: Date of customer's enrollment with the company 
- Recency: Number of days since customer's last purchase 
- Complain: 1 if customer complained in the last 2 years, 0 otherwise

Products 
- MntWines: Amount spent on wine in last 2 years 
- MntFruits: Amount spent on fruits in last 2 years 
- MntMeatProducts: Amount spent on meat in last 2 years 
- MntFishProducts: Amount spent on fish in last 2 years 
- MntSweetProducts: Amount spent on sweets in last 2 years 
- MntGoldProds: Amount spent on gold in last 2 years

Promotion 
- NumDealsPurchases: Number of purchases made with a discount 
- AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise 
- AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise 
- AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise 
- AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise 
- AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise 
- Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

Place 
- NumWebPurchases: Number of purchases made through the company’s web site 
- NumCatalogPurchases: Number of purchases made using a catalogue NumStorePurchases: 
- Number of purchases made directly in stores 
- NumWebVisitsMonth: Number of visits to company’s web site in the last month

### Given the above information and different vizualisation after cleaning the data, below are the insights derived from the data:

- Using the correlation matrix, a lot of variables seem to be correlated to each other. Income seems to be a lot correlated to mean amount spent on differnt products. Also the   mean amount spent on different product seems to have a positive correlation with each other. The mean amount spent on wines has a high positive correlation with number of web purchases, catalog purchases and store purchases. The mean amount spent on meat products has a high positive correlation with number of catalog purchases. 

- Most of the customers fall under age 40-50 but there are three customers who have age more than 100.

- Customers with basic education have lowest income and PhD have highest income.

- Most of the customers are graduates among which many of them have income ranging from 40,000 - 50,000 while very few have basic education and have low incomes.

- Among the single people, customers with PhD or masters degree have the highest income. Among together or married people, customers with PhD have the highest income and among the widowed customers too, people with PhD have highest income.

- Most people having two teens are married and customers who are divorced or widowed have atleast one teen at home.  

- Most of the customers belong to 30,000 to 40,000 and 50,000-60,000 income group.

- Customers tend to spend more on wines and meat products in the past two years as per the given data.

- Most of the customers have not accepted the offer in any of the campaign. Customers who have incomes in the range of 90,000-100,000 seem to have accepted the offer in the 5th or last campaign.

- Under most of the income groups, majority of the customers are married and seem to have atleast 1 kid at home.

- Customers belonging to the income group 90,000-100,000 tend to have spent maximum for majority of the products.This income group also has majority of customers who accepted the offer in 5th or last campaign and they are mostly single with no kids or teens.

- The customers who have been the longest with company have spent the maximun on wines and meat products.

- Very few customers among the people who have been the longest with the company had complained in the last two years and they belong to the income group 20,000-30,000.

- Among the customers who have been the longest with the company the last purchase was 40-60 days ago.

- There are 144 customers who accepted the offer in the first campaign. Majority of customers belong to 45-50 and 60-65 age groups and majority of the customers have income around 80,000. These customers have spent maximum on wines and meat products and customers having 2nd Cycle education have purchased very recently.

- The customers who had accepted the offer in the last campaign seem to be spread across all income groups and more towards the higher income group.

- There were very few customers who have complained in the last two years from the given data. Most of the customers who complained have income 40,000-50,000 and 60,000-70,000 and are around 60 years of age. Among the customers who complained, majority who purchased before 40 or 60 days, are not among the oldest customers.Like any other grouped customers, these customers also seems to have been spending more on wines and meat products. Number of catalog purchases is maximum among the customers having income between 100,000-200,000. Number of deal purchases is maximum for those among 50,000-60,000 and 0-10,000 income. Number of store purchases is maximum for those among 80,000-90,000 income. Number of web purchases is maximum for those among 60,000-70,000 income. 

- Extracting the weekdays, days and month from the customer date enrolled, more number of customers enrolled towards the weekend or start of the month or in the month of August or October.

- Extracting weekdays, days and month from the last purchased date for the customers, the last purchased for most of the customers was towards the weekend or in the month of October which is also the month when most of the customers were enrolled. Very few people had their last purchased date as month end. 
