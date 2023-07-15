# Capstone-Project-4-Python-ML-Credit-Card-Fraud
**Contents/Agenda**
  * Introduction
    - Role
    - Business Problem Overview
    - Solution Approach
  * Data Overview
  * Data Analytics Results
  * Executive Summary 
    - Actionable Insights
    - Recommendations
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Introduction**
* Business Challenge Overview
Digital payments are evolving, but so are cyber criminals.
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
According to the Data Breach Index, more than 5 million records are being stolen on a daily basis, a concerning statistic that shows - fraud is still very common both for Card-Present and Card-not Present type of payments.
In today’s digital world where trillions of Card transaction happens per day, detection of fraud is challenging.

  [Credit Card Fraud | Kaggle](https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Role
  - Data Analyst for a credit card company
  - Reporting to Director of company
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Solution Approach
  - Extract, Transform, Load
  - Train and test machine learning models
  - Share insights and recommendations
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Data Overview**
  1. distance_from_home            : the distance from home where the transaction happened.
  2. distance_from_last_transaction: the distance from last transaction happened.
  3. ratio_to_median_purchase_price: Ratio of purchased price transaction to median purchase price.
  4. repeat_retailer               : Is the transaction happened from same retailer.
  5. used_chip                     : Is the transaction through chip (credit card).
  6. used_pin_number               : Is the transaction happened by using PIN number.
  7. online_order                  : Is the transaction an online order.
  8. Fraud                         : Is the transaction fraudulent.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Data Reprocessing**
  - There are no missing values or duplicates.
  - There are outliers observed for “distance_from_home”, “distance_from_last_transaction” & “ratio_to_median_purchase_price”.

    However, being proper value, they are not treated.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Insights**
https://i.imgur.com/7vEGgsd.png

https://i.imgur.com/UIz6Mcp.png

https://i.imgur.com/iS6w6iH.png

https://i.imgur.com/HNDn3eu.png

https://i.imgur.com/a98DBkL.png

https://i.imgur.com/hRztHfn.png

https://i.imgur.com/x02aJtX.png

https://i.imgur.com/vuoZ7FS.png

https://i.imgur.com/VxthtQs.png

https://i.imgur.com/ZxxFUoS.png

https://i.imgur.com/KoEkrx5.png

https://i.imgur.com/1Xtr3yi.png

https://i.imgur.com/kj0YnP4.png

https://i.imgur.com/6RqwAky.png

https://i.imgur.com/tTbWBxF.png

https://i.imgur.com/jD9cr9R.png

There us good performace and not much issue with overfitting for both machine learning models, since the results for testing are close to results for training.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Recommendations**

Random Forest is recommended for use, due to better performance, as compared to bagging.
