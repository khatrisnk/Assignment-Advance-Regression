# Assignment - Advance Regression

## Problem Statement

A US-based housing company named **Surprise Housing** has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company is looking at prospective properties to buy to enter the market.

## Objective

The company wants to know:
 - Which variables are significant in predicting the price of a house, and
 - How well those variables describe the price of a house.

## Business Goal

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Data Sourcing

The company has collected and given a data set from the sale of houses in Australia. For this case study we need to focus only on provided dataset given by company. Data dfinition is also given in the link below to understand the data.

Link to the [Data definition](./Data_definition.pdf)

## Instructions

1. Build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
2. Determine the optimal value of lambda for ridge and lasso regression

## Platform Used

    - Jupyter notbook

## Library Used

    - Pandas
    - Numpy
    - Matplotlib
    - Seaborn
    - sklearn

## Recomendations

1. R2 Score for Lasso Regression is 9.266148e-01(train) and 8.803521e-01(test). Lasso Regression Model is best for interpretation.
2. Top 10 feature from Lasso comes out as below:

    2.1. Living area on ground floor, overall quality of material and finish, basement area, lot area are the significant factory for sale price of peoperty.

    2.2. Specific Neighborhood also play a critical role (Northridge, Northridge Heights, Stone Brook and Crawford)

    2.3. Basement full bathroom and good basement exposure are also critical to predict sale price.


## Contact
Created by [@khatrisnk](https://www.github.com/khatrisnk) - feel free to contact me!
