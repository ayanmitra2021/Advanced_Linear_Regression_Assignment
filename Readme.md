# Advanced Regression for a Housing company company 
> The project generates different machine learning models for a hosing sharing company based on a variety of input data. The objective is to identify the best set of independent variables that can help determine Sales Price of the house which is our target variable. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project was about building linear regression models for a US-based housing company named Surprise Housing which has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. In the target datat set we got 80 predictor varibales of which almost 30 are categorical. The objective is to use various regression models (like linear regression, ridge and lasso) to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
We have performed the analysis using 8 different training models, of which we selected 3 best models.

- Model 4 that we derived using RFE technique - giving a 74% r-squared
- Model 6 that we derived from Ridge technique - giving a 81% r-squared
- Model 8 that we derived using Lasso techniqueue - giving a 87% r-squared

## Technologies Used
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- statsmodels
- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- https://wikipedia.org
- https://stats.stackexchange.com/
- https://math.stackexchange.com/

## Contact
Created by [@ayanmitra2021] - feel free to contact me!