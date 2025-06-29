# Used Cars Market in France — Analysis & Price Prediction

## Overview

The project consists of working on a dataset that came from scraping two major websites for used vehicles in France.
We will try through it to understand what happens in the used car market in France, through a deep EDA combining univariate and bivariate analysis.
Then, we will try to build a machine learning model using **XGBoost Regressor** to predict the price of a used car, taking into consideration the brand, the model, mileage, age of the car, and other features.

## Data Cleaning and Preparation

The data had to go through several steps before it was ready to use:

* Columns had unwanted characters such as `/` and `€`, so we removed all unnecessary symbols.
* We converted each column to its appropriate type.
* We also handled missing values and ensured consistency across the dataset.

## Exploratory Data Analysis

The topic is really exciting to explore.
Through the available data, we tried to understand the characteristics of the used cars market, including:

* Most represented brands and models
* How mileage and age influence the price
* Price variation by fuel type, gearbox, and other attributes

## Machine Learning Model

At the end, we used the **XGBoost Regressor** to build a regression model that predicts car prices.
We used OneHotEncoding for categorical variables such as brand and model.
Although the model is not perfect, it gives a reasonable idea of how different features affect price.



