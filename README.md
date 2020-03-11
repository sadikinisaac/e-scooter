Predicting-e-scooter-rental-demand
Jupyter notebook for forecasting the e-scooter active users (guest-users and registered-users) in a city

Requirements
Install conda for python, which has all the necessary packages for data manipulation and machine learning.

Libraries Used
1.Pandas 2.Numpy 3.Matplotlib 4.Seaborn

Regressor Used for Prediction
1.Linear Regression
2.Decision Tree Regressor
3.Gradient Boosting Regressor
4.XGBRegressor
5.AdaBoost Regressor

Evaluation Metric Used
1.R2 Score 
2.Mean Absolute Error
3.Mean Squared Error

Procedure
Step 1:
Data cleaning - Check for any missing values in the dataset and try to get rid off it either by deleting it or replacing it with values appropriate to the feature. Also get to know the types of each feature in the dataset and make the data ready for EDA.

Step 2:
EDA - Exploratory Data Analysis, visualizing the important features in the dataset, so that some outliers can be found.
In addition, to find correlation between the different features in the dataset.

Step 3:
Now Split the dataset into train and test to predict the e-scooter rental demand

Step 4:
Use the 5 different Regressors to train the model

Step 5:
Using the trained model for forecasting the demand using the test number of value.
