# Advanced Regression Assignment

> This assignment is a programming assignment where in we have to build a multiple linear regression model for the prediction of price of houses.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know: Which variables are significant in predicting the price of a house, and How well those variables describe the price of a house. Also, to determine the optimal value of lambda for ridge and lasso regression.

- What is the business probem that your project is trying to solve?
  Required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- What is the dataset that is being used?
  https://raw.githubusercontent.com/DevalapalleJaswanth/housingData/main/train.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- For Alpha = 0.001 both Ridge and Lasso Regression models have good R-Squared values.
- The most important predictor variables after changing alpha =0.001 are :
  -Ridge Regression : OverallQual, GrLivArea, LotArea, 2ndFlrSF, 1stFlrSF
  -Lasso Regression: OverallQual, GrLivArea, GarageCars, FirePlaces, Neighborhood_NoRidge

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Pandas - version 1.3.5
- seaborn - version 0.11.2
- sklearn
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact

Created by [@DevalapalleJaswanth] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
