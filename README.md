# Kings County Housing Project

## Linear Regression Analysis of House Sales in a Northwestern County

This project focuses on performing a linear regression analysis on house sales in a northwestern county. The goal is to provide valuable insights and recommendations to stakeholders regarding the estimated value of homes and how renovations can impact their value.

## Project Overview

This project aims to analyze the factors that influence house prices in King's County and develop a linear regression model to predict the value of homes. By examining the dataset provided, we explore various features such as the number of bedrooms, square footage, location, and condition of the properties to determine their impact on house prices.

## Business Problem

The objective of this project is to build a model that can predict house prices based on the features of the house using the available King's County house selling records. The model can be used by both sellers and buyers in their business decisions. Sellers can predict the selling price of their house and determine if any renovations are necessary before selling. Buyers can receive suggestions on the type of house they can afford based on their budget.

The following objectives are set to achieve the final goal:

1. Analyze and clean the data by handling meaningless or null values.
2. Remove features that do not contribute to the house price.
3. Identify highly correlated features and potentially remove redundant ones.
4. Build a linear regression model.
5. Evaluate the impact of different features on house prices.

## Dataset

The project utilizes the King County House Sales dataset, which is available in the `kc_house_data.csv` file located in the `data` folder of this project's GitHub repository. The dataset contains information on house sales, including numerical and categorical variables such as price, number of bedrooms, number of bathrooms, square footage, location, and more. Please refer to the `column_names.md` file in the same folder for detailed descriptions of each column.

## Methodology

### Data Understanding

To gain insights into the dataset, I initially explored its contents and analyzed the distribution of available features. This process allowed me to understand the relationships between independent variables and the target variable, which is house prices.

### Data Preparation

To ensure data quality, I performed data cleaning procedures, addressing missing values, handling outliers, and transforming variables as necessary. Additionally, I conducted feature engineering, creating new features derived from existing ones to capture additional information and improve the predictive power of the model.

### Exploratory Data Analysis

Thorough analysis of the dataset was conducted, including visualizations and statistical tests to examine relationships between variables. The goal was to identify correlations and determine significant predictors that impact house prices. This analysis provided valuable insights into the underlying patterns and trends within the data.

### Modeling

A linear regression model was implemented to predict house prices based on the selected independent variables. The dataset was divided into training and testing sets, with the model trained on the training set and evaluated on the testing set. The goodness of fit of the model was assessed, and the coefficients were interpreted to understand the influence of each feature on house prices.

### Recommendations

Based on the results of the model, I provided recommendations to stakeholders regarding the impact of renovations and specific features on the estimated value of homes. By highlighting the most influential factors, homeowners can make informed decisions to increase their property's value and appeal in the market.

## Conclusion

This project provides valuable insights into the factors influencing house prices in King's County through a linear regression analysis. By analyzing the dataset, performing feature engineering, and building a regression model, we can predict house prices based on various features. The recommendations provided can guide stakeholders in making informed decisions when buying or selling properties.
