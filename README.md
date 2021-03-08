# Predicting-House-Sales-Price

INTRODUCTION AND PROBLEM STATEMENT
We are given a dataset consisting of house details in Ames, Iowa . Our problem statement is to build a predictive model that can be used to guide our customers on where, when and how to build a property with minimum expense to maximize profit during resale

DESCRIPTION OF THE DATA
The dataset consists of the various features of the houses in AMES IOWA and the sales spread 2006-2010
The dataset consists of 3000 transactions that has happened at Ames and 80 features of the houses that has been sold. The columns consist of 36 numerical features and 43 categorical features . Few important features that has been collected are mainly Type of dwelling involved in the sales, building types, Zones of the household , Neighborhood, Basement Conditions, Garage maintenance, year the house was build, Year of the house sold etc. These features must be investigated individually and in-collaboration with other features to find out their influence on the marketplace and buying patterns so that it can help us in building a recommendation system for our customers based on their budget

CODE IMPLEMENTATION STEPS
Step 1 :
We Examine the data for Null or Missing values and found quite a few columns with them. We decided to keep a threshold of 40 % and any column that has more than 40% of their values as null was eliminated. We found that 5 columns had more than 40% Null or missing values and the 5 columns were removed from the data
For the columns which had less than 40 % missing values we chose to substitute the values with the mode of the column for categorical and mean for numerical.
Step 2 :
We also found the variance of the columns and decided to remove columns which don’t have much variance as they would not contribute much to our model and would not be of any significance in our analysis.
Step 3:
Exploratory Data Analysis (EDA)
Step 4 :
Feature Engineering
Step 5 :
Feature Selection
MODEL FITTING:
After all the preprocessing is done , the data is split into Train and Test and then we scale it.
We first choose a Multiple Linear Regression Model as we have done all the preprocessing required such as :
- linear relationship between the dependent and independent variables
- The independent variables are not highly correlated with each other
- The variance of the residuals is constant
- Independence of observations
Multiple Linear Regression Model is used to identify the strength of the effect that the independent variables have on a dependent variable. Multiple Regression Analysis helps us to understand how much will the dependent variables change when we change the independent variables. Multiple Linear Regression Analysis predicts trends and future values.
Thus, we select a Multiple Linear Regression model for our prediction.

Conclusion
From our above analysis we conclude that we have found a way to provide the clients with the information as to which property to invest in or purchase and when and how much returns can they expect on selling the property. We used a Multiple Linear Regression model with RMSE 0.1703 to predict the sales price value and provide our client with the necessary details.
