# Project-2-Housing-Prices-Prediction-using-Sklearn-and-LinearRegression

## Introduction
In this project, we will develop and evaluate the performance and the predictive power of a model trained and tested on data collected from houses in Boston’s suburbs.
Once we get a good fit, we will use this model to predict the monetary value of a house located at the Boston’s area.
A model like this would be very valuable for a real state agent who could make use of the information provided in a dayly basis.
![](https://miro.medium.com/max/1400/1*5stVxlz6EgnpqWarZvghoA.png)

## Problem Statement:
The dataset has house prices of the Boston residual areas. The expense of the house varies according to various factors like crime rate, number of rooms, etc. We have to predict prices on the basis of new data.

## Requirements:
- Jupyter Notebook

## Boston-Dataset:
The dataset used in this project comes from the UCI Machine Learning Repository. This data was collected in 1978 and each of the 506 entries represents aggregate information about 13 features of homes from various suburbs located in Boston.
The features can be summarized as follows:
- CRIM: This is the per capita crime rate by town
- ZN: This is the proportion of residential land zoned for lots larger than 25,000 sq.ft.
- INDUS: This is the proportion of non-retail business acres per town.
- CHAS: This is the Charles River dummy variable (this is equal to 1 if tract bounds river; 0 otherwise)
- NOX: This is the nitric oxides concentration (parts per 10 million)
- RM: This is the average number of rooms per dwelling
- AGE: This is the proportion of owner-occupied units built prior to 1940
- DIS: This is the weighted distances to five Boston employment centers
- RAD: This is the index of accessibility to radial highways
- TAX: This is the full-value property-tax rate per $10,000
- PTRATIO: This is the pupil-teacher ratio by town
- B: This is calculated as 1000(Bk — 0.63)², where Bk is the proportion of people of African American descent by town
- LSTAT: This is the percentage lower status of the population

## Importing the Modules:
- SkLearn
- Numpy
- Pandas

## LinearRegression:
Linear Regression is a machine learning algorithm based on supervised learning. It performs a regression task. Regression models a target prediction value based on independent variables. It is mostly used for finding out the relationship between variables and forecasting. Different regression models differ based on – the kind of relationship between dependent and independent variables, they are considering and the number of independent variables being used.
![](https://miro.medium.com/max/640/1*LEmBCYAttxS6uI6rEyPLMQ.png)

## Score:
For this model, the accuracy on the test set is **0.74**, which means the model made the right prediction for **74%** of the houses in the Boston dataset. We can expect the model to be correct **74%** of the time for predicting the new values from different clients.

## Summary:
The Boston Housing Prices Prediction problem (and our implementation) is a perfect example to illustrate how a machine learning problem should be approached and how useful the outcome can be to a potential client who wanted to buy a new house.
