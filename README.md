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

