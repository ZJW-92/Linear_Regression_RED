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

## Data analysis 
### Index explanation 
* purchasing_amount: the amount user purchases
* gender: male->1, female->0, U= unknown 
* age 
* 3rd_party_store: user puchases from the third party merchant
* comulative_purchase_amount: comulative amount user purchases
* days_since_last_order
* last_month_engage: activity user engages in the past month
* lifecycle: A: registered within 6 month, B: registered within one year, C: registered within two years
