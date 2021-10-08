# Case study: RED-小红书
![red-view](img/red.png)
## Background 

RED(小红书), established in June 2013, is an online shopping and social networking platform in Mainland China. 

The website claims to have 200 million users since January 2019.
In its community, users and celebrities can share product reviews and tourist destination introductions.

RED uses machine learning to accurately and efficiently match massive amounts of information with people. 
It has accumulated massive amounts of overseas shopping data, analyzed the most popular products and global shopping trends.
Based on this, RED provides good products to users with a shortest path and a most concise way. 


## Analysis goal 

Based on user data and consumer behavior data
* Use jupyter notebook to build a linear regression model
* Forecast changes of user's consumption amount
* Find the factors that have a greater impact on user consumption

## 1 Data analysis 
### Index explanation 
* purchasing_amount: the amount user purchases
* gender: male->1, female->0, U= unknown 
* age 
* 3rd_party_store: user puchases from the third party merchant
* comulative_purchase_amount: comulative amount user purchases
* days_since_last_order
* last_month_engage: activity user engages in the past month
* lifecycle: A: registered within 6 month, B: registered within one year, C: registered within two years


## 2 Univariate analysis
### 2.1 numerical variables
#### Conclusion: 

* According to the distplot of age and red['age'].describe(), we can see
- 1. the user age is distributed between 18-99 years old, 
- 2. the average user age is 60.39 years old, 
- 3. the median user age is 60.39 years old, 
- 4. the vast majority of users are between 58 - 63 years old.

* From the days since last order, we can see 
- 1. The number of days since the last time a user placed an order is distributed between 0 and 23 days. 
- 2. All users have made orders within this month.
- 3. The user will make an order again after an average of 7.7 days. 
- 4. The frequency of 0-1 days from the last time the user made an order is relatively higher. 


### 2.2 categorical variables



