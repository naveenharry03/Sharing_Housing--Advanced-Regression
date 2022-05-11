# Sharing_Housing--Advanced-Regression

# What is BoomBikes ?

- A US-based housing company named Surprise Housing has decided to enter the Australian market. 
- The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
- For the same purpose, the company has collected a data set from the sale of houses in Australia. 
- The data is provided in the CSV file.
- The company is looking at prospective properties to buy to enter the market
- You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

# Business objective: 

- You are required to model the price of houses with the available independent variables
- This model will then be used by the management to understand how exactly the prices vary with the variables
-  They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
- Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
## Requirements

1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.

## Business Understanding
- Understand the requirements of the Assignment

## Data Understanding
- Understand the datasets provided

## Data Cleaning and Manipulation
- Clean the data and perform some manipulation

## Data Visualization
- Perform EDA to understand various variables.
- Check the correlation between the variables.

## Data Preparation
- Create dummy variables for all the categorical features.
- Divide the data to train & Test.
- Perform Scaling.
- Divide data into dependent & Independent variables.

## Data Modelling & Evaluation
- Create Linear Regression model using mixed approach (RFE & VIF/p-value).
- Check the various assumptions.
- Check the Adjusted R-Square for both train & Test data.
- Report the final model.

## Technologies Used
- Jupyter Notebooks
- Anaconda Navigator
- Github
- Matplot lib
- Seaborn
- numpy
- pandas
- Statsmodels
- sklearn
- Cross Gridsearch sv
- Lasso
- Ridge

# Conclusions
## from EDA Process

- The Bike Sharing Bookings are high during FALL Season.
- The Bike Sharing Bookings are high in the year 2019 and low in 2018.
- The Bike Sharing Bookings are high in the middle of the year (may to oct).
- At start of the year tends to increase and at the end of the year it decreases
- The Bike Sharing Bookings are high in Weekends and holidays
- The Bike Sharing Bookings are high when they slightly moving towards weekends.
- The Bike Sharing Bookings are high in the clear weather compared to mist and light snow

## Model Building and Evaluation
### So The Variables which are significant in predicting the demand for shared bikes

# Which variables are significant in predicting the price of a house

1. GrLivArea
2. OverallQual
3. GarageArea
4. BsmtFinSF1
5. TotalBsmtSF
6. NridgHt
7. DmKitchenQual
8. Crawfor
9. DmExterQual
10. OverallCond

# It can be concluded that Ridge is better performing than Lasso interms of R2 Score
# Also concluded that Lasso is better than Ridge interms of Feature Selection


## Acknowledgements
Give credit here.
- This project was inspired by the Bike sharing companies where i came to know the process about how the bike is being shared for a rental purposes.
- Got many references from the internet for the bike sharing terminologies
- Thanks to upgrad on giving me this opportunity to work on this analysis

## Contact
Created by [@naveenharry03] - feel free to contact me! naveenharry03@gmail.com


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
