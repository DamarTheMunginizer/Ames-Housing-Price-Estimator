# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) # Project 2 - Ames Housing Data and Kaggle Challenge

## Project 2 - Ames Housing Data and Kaggle Challenge

### Deatils
Name: Damar Shipp Jr

Class: DSB-10155


# Table of Contents

1. [Exective Summary](#exective-summary)
2. [Purpose](#purpose)
3. [Problem Statement](#problem_statement)
4. [Results](#results)
5. [Data Overview](#data_overview)
6. [Model Explanation](#model_explanation)
7. [Next Steps](#next_steps)
8. [Requirements](#requirements) 

## Executive Summary

- This project involved building a regression model to predict housing prices at the close of sell based on various features such as the year it was built, the number of full bathrooms, and more. The model I built was trained on a dataset containing housing related varibles, and the goal is to predict the house prices accurately aithout knowing the actual price. The project also explores model evaluation, feature engineering, and the use of regularization techniques like Lasso to improve the accuracy of your prediction.

## Purpose

- The purpose of this project is to develop a regression model that predicts the price of a house using a set of data about the variables of the house. This model can be used to assist in predicting the price of the houses included, understanding trends in the real estate market, or as a byproduct for investors or real estate professionals looking at an estimated value based on various varibles.

## Problem Statement

Housing prices are influenced by numerous factors such as the year it was built, the number of bedrooms, neighboorhoods, and more. The goal is to create a model that can predict the price of the houses based on these variables with high accuracy. Given the string of data and complexity to find the potential correlations between varibles, this problem involves both variable selection and the application of machine learning techniques to return accurate predictions.

## Results

The regression model, after preprocessing and feature engineering, was trained and tested on the housing data. The following results were obtained:

- **Mean Squared Error (MSE)**: [1534797270.1862338]
- **Mean Absolute Error (MAE)**: [28423.027612776878]
- **R-squared**: [28423.027612776878]
  
The model was able to make fairly accurate predictions, though some further improvements could be made by revamping the hyperparameters, or adding/removing more features.

## Data Overview 
#### Provided Data
---
The dataset used in this project contains multi-features related to the houses, including both continuous and categorical variables. Some of the key features are:

- **Year Built**: The year the house was built
- **Full Bath**: Number of full size bathrooms in the house
- **Garage Cars** Number of cars the garage can hold
- **Year Remod/Add**: The improve quality of the house
- **Garage Area**: Size of the garage in square feet

Additionally, the dataset contains missing values and categorical variables, which had to be filled or drop at your own suggested decision.

---

## Model Explanation
#### Methods

The model used in this project is a **Linear Regression** with **Lasso Regularization** to prevent overfitting and to improve the model's capability to generalize. Lasso regression was selected because it helps in selecting important variables.

Steps involved(Key steps):

- **Preprocessing**: Missing values were identified and filled, and categorical features were encoded.
- **Modeling**: Lasso regression was applied to predict house prices.
- **Evaluation**: Model performance was assessed using various metrics like MSE and MAE.
- 

## Next Steps

The following improvements and next steps can be considered to enhance the model:

To improve the model, we can:
1. **Tune the model**: Optimize the Lasso model by adjusting its parameters.
2. **Add more features**: Identify other relevant features that could enhance prediction accuracy.
3. **Test with other models**: Experiment with algorithms like scaling and squaring to compare performance.
   

## Requirements
To retrace my steps, ensure you have the following...

- Python
  
- Pandas
  
- Numpy
  
- Matplotlib
  
- Seaborn

- Scikit Learn(Linear Regression, MSE, MAE, R2, TTS, Dummy Regressor, Simple Inputer, One Hot Encoder, and Column Transformer)

- Statsmodels



#### Contact
- [LinkedIn](www.linkedin.com/in/damar-shipp-jr-614b71186)
