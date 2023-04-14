# Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning
### Background
A company can develop rapidly when it knows its customer personality behavior, so it can provide better services and benefits to customers who have the potential to become loyal customers. By processing historical marketing campaign data to improve performance and target the right customers so they can transact on the company's platform, from this data insight our focus is to create a cluster prediction model to make it easier for companies to make decisions.

### Goal
Improve marketing campaign efficiency by targeting the right customers based on their personality

### Objective
Create a clustering machine learning to divide the customers based on their personality with accuracy min. 88%

##  Data
Dataset contains data purchasing from all shop’s resources, data accepted campaigns, and the data of shop’s customers with 2.240 rows and 30 features. There is one missing values on "Income" features

## Tools
The tools used for this project are python as programming languange, jupyter notebook, and several libraries such as: pandas, numpy, sklearn to do preprocessing and build machine learning, matplotlib and seaborn library to generate data visualization.

##  Contents
### Data Cleaning and Data Preprocessing
On this section, there are several actions that been made: Null values in "Income" features filled with median; Drop 183 duplicated data; Feature Selection using RFM Analysis (Recency, Frequency, and Monetary); and Feature Transformation using log transformation and normalization - MinMaxScaler

### Machine Learning Modelling
Using K-Means Clustering with cross-validation elbow method on inertia and silhoutte score as model evaluation.

### Insights
Based on Clustering, insights that we could get: <br>

---
Core Customers

- There are 28% of total customers from this group
- This customers have a high average spending in our platform (~ 1M/year). They contribute 45.27% income value to our platform. This customers also a frequent customers. Their conversion rate average pretty high (~ 8%) They are also a recent customers, which means they bought a product not too long ago (~ 22 days ago).
- Overall, this type customers giving high value and also a very loyal customers ~ 75 days ago in average. That means, they once a loyal and high value customers, but at some point they stopped to buy

---
Loyal Customers

- There are 30,3% of total customers from this group
- This customers have a high average spending on our platform (~ 1M/year). They contributed for 49.63% income value to our platform. They also identified as a frequent customers (~ 8% conversion rate). But, they are not a recent customers. They last bought was in ~ 75 days ago in average.
- Overall, this customers once a high value and frequent customers, but at some point they stopped to buy in our platform

---
New Customers
- There are 21.4% of total customers from this group
- This type customers are new customers. That means they didn't spent much in our platform yet (~70k/year in average). They also not frequent since they're still a new customers. They conversion rate only 1% but they are a recent new customers. That means they bought a product not long ago (25 days ago in average)
- Overall this customers are a new customers. They still spending not a lot but they can be a potential customers to be a core customers

---
Inactive Customer
- There are 20.32% of total customers from this group
- This type customers doesn't spent a lot in our website (~ 78k/year in average). They also not a frequent customers, they conversion rates only 1.3%. Last time they bought a product are 75 days ago in average. 
- Overall, for some point this customers like inactive customer, they don't spent a lot also not a frequent customers

---

###  Business Recommendation

---
Core Customers <br>
- This customer is loyal and not hesitant to spend money / buy products at a high price. Therefore, for this customer, **discounts should be put aside** and the **focus should be on customer service**, as well as on adding value through offers based on **product recommendations that are based on previous purchases.** <br>
- **Identify and engage with these customers** early on in their relationship with the platform to maintain their loyalty and increase their lifetime value. **Provide them with special offers or personalized attention and ensure that they have a seamless experience with the platform**

---

Loyal Customers <br>
- Maintain a strong relationship with these customers and continue to provide them with a high level of service and personalized attention. This might include loyalty programs, special discounts or offers, or exclusive access to new products or features.

---
New Customer <br>
- Engage with these customers early on in their relationship with the platform and **encourage them to continue engaging. Provide targeted offers or incentives to encourage repeat purchases or usage**

---
Inactive Customer <br>
- **Identify why these customers are not engaging with the platform and develop targeted strategies to re-engage them.** This might include personalized offers, improving the user experience, or providing better customer service.
---

By giving them the needed treatment, we can prevent their likely to churn and stay on our platform

### Business Impact
By applying the business recommendation to give a suitable treatment for particular customers, we could get 1.2B/year for approximation. And, if we prioritize the loyal customers and core customers, we could still get 94.5% from all the total revenue
