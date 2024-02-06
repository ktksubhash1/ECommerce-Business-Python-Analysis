# ECommerce Business Python Analysis

## Project Context
* Olist is an online market place that connects small businesses from all over Brazil
* It offers services like  cataloging, sales process management, market intelligence, etc.
* Merchants will list their products online and ship to the customers using Olist logistics
* After the product is delivered, customer gives a review of his experience
* Merchants benefit from better market presence and transparent reputation metrics
* For any business, understanding its customer behavior is vital to device their strategies
* This allows them to analyze the market effectively and make better decisions


## Data Description
8 different datasets have been used for the purpose of data analysis and customer segmentation
* Customer data
* Products data
* Orders data
* Geolocation data
* Order items data
* Payments data
* Seller data
* Product reviews data

Each dataset has about 100k records from 2016 to 2018.
Each dataset is linked to another one with a primary to foreign relationship.
Since the datasets are of a Brazilian company, some of the data is in Portuguese language.

## Process Flow
* Import libraries
* Data importing
* Data cleaning and merging
* Data insights
* Analyzing the customer behavior
* Customer segmentation
* Recommend business strategies

## Business Insights
### * Trend of Orders
![image](https://github.com/ktksubhash1/ECommerce-Business-Python-Analysis/assets/131713846/9d43321a-15a3-4804-b6f7-dcc08fc0156d)

### * Orders by Day of Week and Time of Day
![image](https://github.com/ktksubhash1/ECommerce-Business-Python-Analysis/assets/131713846/746d3406-7369-417d-bada-b46a74388ec4)

### * Trend of Sellers Joining the E-Commerce Platform
![image](https://github.com/ktksubhash1/ECommerce-Business-Python-Analysis/assets/131713846/0e3fc020-f787-4ffe-bffb-bd6c569db80c)

### * Preferred Modes of Payment
![image](https://github.com/ktksubhash1/ECommerce-Business-Python-Analysis/assets/131713846/31868ad2-b1da-4274-b719-a3758ef68d48)

### * Sentiment Analysis of Customers
![image](https://github.com/ktksubhash1/ECommerce-Business-Python-Analysis/assets/131713846/9db5887e-e4fd-483b-b621-2023ece882fc)

# Unsupervised Machine Learning - Clustering Model
## Customer Segmentation Analysis
### * K-Means Elbow Plot
![image](https://github.com/ktksubhash1/ECommerce-Business-Python-Analysis/assets/131713846/7a22f769-b86e-4ca0-96d6-e3dd2e867112)

### * Customer Segments
![image](https://github.com/ktksubhash1/ECommerce-Business-Python-Analysis/assets/131713846/e2b6f17d-a73a-40c6-8644-33e282e2ffcb)

### Cluster Descriptions:
* Cluster 0: New Customers -> Higher recency but lower spendings
* Cluster 1: High spenders -> High purchase value inspite of low recency
* Cluster 2: Low spenders -> Both low recency and low spending
* Cluster 3: Loyal customers -> Both higher spending and higher recency

# Conclusions
From the stacked bar graph, F_scores of the customers in each cluster is fairly similar. Hence F_score would be less important when deciding the clusters. The clusters can be seen as customer segments which are as follows
* Cluster 0: Early customers with low purchase value
* Cluster 1: High spenders
* Cluster 2: Hibernating customers with low purchase value
* Cluster 3: Loyal customers

The following strategies are recommended for each group
* Cluster 0: Giving them great offers and discounts so that they will gain confidence on Olist
* Cluster 1: Offering them priority access to promotional offers and discount sale days
* Cluster 2: Offering them quality products that are value for their money, so that they will want to buy more from Olist
* Cluster 3: Give them both priority access and additional loyalty reward programs as a token of appreciation for their continued trust in the business 
