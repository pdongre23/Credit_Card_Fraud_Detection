# Credit_Card_Fraud_Detection
The data set used is downloaded from Kaggle. The dataset contain transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.<br>
First, exploratory data analysis is done to gain insights from data.<br>
In this project, anomaly detection techniques (Local outlier factor and isolation forest algorithm) of sklearn package have been explored to train a machine learning model to detect credict card fraud.<br>
Supervised learning models like KNN, SVC, Logistic Regression, Decision Tree is applied to detect fradulent transactions. The RUC_AUC score is used to compare these models. The best score of 0.886 is obtained using SVC.
