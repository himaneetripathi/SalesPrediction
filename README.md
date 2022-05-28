**Title - Predicting Sales based on products and outlets.**


Author: Himanee Tripathi

**Business problem** 

Business is interested in knowing factors affecting sales  of food items.


**DATA**

Sales Prediction-csv, ( Original data source)

This Data is about sales prediction for food items sold at various stores.

**Methods**

Performed a train test split.

Created a preprocessing object to prepare the dataset for Machine Learning.

Applied linear regression model to predict sales.

Applied a regression tree model to predict sales



**Results**

We have tried 2 different models on our data set,in order to determine which model to implement we need to compare the values,

linear Regression Model

Training R2 : 0.5101
Testing R2 : 0.5087

TrainingRMSE : 1204.0118
TestingRMSE : 1164.2406


Regression Tree Model

TrainingR2 : 0.60
TestingR2 : 0.59

TrainingRMSE : 1082.65
TestingRMSE : 1057.44

we can notice that in the Regression Tree Model the training and test results, especially RMSE are more closer to each other (a sign of reduced overfitting) so we can say that these values are more suitable for our model. 




<img width="616" alt="image" src="https://user-images.githubusercontent.com/104323109/170845379-83bcbb61-beb8-4111-ae32-edcdb1c24acc.png">




**For further information**

For any additional questions, please contact himaneetripathi30@gmail.com





