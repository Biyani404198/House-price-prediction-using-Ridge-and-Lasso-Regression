# House Price Prediction
> Surprise housing price prediction using lasso and ridge regression
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Steps:
- Read Data
- Data Understanding
- Data Exploration
- Data Cleaning
- EDA
- Data Preparation
- Model Bulding and Model Evaluation and Making Predictions
Background of this model is making a model robust and generalisable when overfitting using regularization techniques like ridge and lasso regression which penalise the model and amke it simpler if too complex by reducing the coefficients closer to zero.

Business Goal:
We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
We will use lasso for final model prediction since:
- The scores are higher and consistent
- Model is simpler than ridge (less number of variables)
Final score of model:
- Lasso regression train r2: 0.945
- Lasso regression test r2: 0.887

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- sklearn
- numpy
- pandas
- seaborn
- matplotlib

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@Biyani404198] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
