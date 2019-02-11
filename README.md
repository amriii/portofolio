# Projects Portfolio  
by: Hilfi Amri

## 1. Recency Frequency Monetary Analysis  
Process an anonymous UK Retailer dataset from Kagle to understand customer segmentation, based on the well-known RFM framework.
In RFM, 'R' stands for 'Recency' which represents the difference of last purchased date and a predefined date; 'F' stands for 'Frequency'
which describes the amount of transactions that has been conducted by a customer on a specific period; lastly, while 'M' tells the amount
of financial transactions for a specific user in a specific period. After completion, we will understood who are our 'Best Customers', 
'Loyal Customers', and even 'Almost Lost', 'Lost', and 'Lost Cheap Customers'.  
  
Link: https://github.com/amriii/portofolio/tree/master/RFM_Analysis

## 2. Machine Learning - Predicting Customer Subscription for Premium Feature
The goal of the project is to be able to predict which customer will subscribe to the premium feature after 48 hours. The avaialable data are customer data with features including: user id, first access date, accessed-screen list, premium enrolled date, and the number of likes. The approach is to use a Logistic Regression, since we are faced with a binary classification problem. The model yields an accuracy of 0.767 (+/- 0.013). 
Accuracy is the sum of True Positive and True Negative over the sum of total amount of predicted data.  
  
Link: https://github.com/amriii/portofolio/tree/master/Directing_Customer_Subcription

## 3. Machine Learning - Predicting the Number of Hourly Rentals (Time Series Modeling)
Bike sharing systems are new generation of traditional bike rentals where the whole process from membership, 
rental and return back has become automated. Intuitively, its business process relies heavily on customer behavior, which is also effected by other external values such as the environmental conditions. Furthermore, the number of bike rentals follow certain patterns that are heavily correlated with time, e.g. at 08.00 the number of bike rented will be higher than at 23.00 because most people do their activities in the morning compared to the latter, which makes this a time-series case. The dataset contains hourly values of number of bike rentals and other external factors which spans from 2011 to 2013. Management are invested in knowing when will be the best time to do bike maintenance at Q1 2014. Model uses XGB Regressor, with some evaluation metrics: R2 is 0.96, MAPE is 23.38 units, and RMSE 31.528 units.  
  
EDA Dashboard:  
ML Repository:
