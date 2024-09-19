# Car Price Prediction Project

This project focuses on predicting the prices of used cars using machine learning models. By analyzing features such as brand, model, year of manufacture, engine capacity, fuel type, and mileage, the model estimates the price of a car, helping sellers and buyers make informed decisions.

## Table of Contents

- [Project Overview](#project-overview)
- [Target Audience](#target-audience)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Modeling Techniques](#modeling-techniques)
- [Model Evaluation](#model-evaluation)
- [Results Summary](#results-summary)
- 

## Project Overview

This project predicts used car prices based on various features such as the car's make, model, year, fuel type, transmission type, and mileage. By leveraging machine learning models, we aim to provide accurate price predictions that assist users in buying and selling decisions.

## Target Audience

This project is useful for:
- **Car Buyers and Sellers:** Individuals looking for an accurate price estimate of used cars.
- **Data Science Practitioners:** Learning predictive modeling in real-world scenarios.
- **Automobile Businesses:** For insights into pricing strategies for used vehicles.
- **Researchers and Enthusiasts:** Exploring car pricing trends and prediction models.

## Dataset

The dataset used contains various features of used cars including:
- Car Make and Model
- Year of Manufacture
- Fuel Type (Petrol, Diesel, etc.)
- Transmission Type (Manual, Automatic)
- Mileage
- Engine Size
- Seller Type

The dataset is available from [Kaggle's Car Price Prediction dataset](https://www.kaggle.com/datasets/vijayaadithyanvg/car-price-predictionused-cars).

## Data Preprocessing

1. **Handling Missing Values:** Filled or removed missing values to ensure data quality.
2. **Encoding Categorical Variables:** Applied encoding techniques like one-hot encoding for non-numeric features.
3. **Feature Scaling:** Used standardization to ensure numeric features are scaled to the same range.
4. **Outlier Detection:** Detected and handled outliers to avoid model bias.

## Feature Engineering

The following feature engineering techniques were applied:
- **Age of the Car:** Calculated by subtracting the year of manufacture from the current year.
- **Mileage Per Year:** Estimated by dividing total mileage by the age of the car.

## Modeling Techniques

We implemented various machine learning algorithms for car price prediction, including:
- **Linear Regression**
- **Random Forest Regressor**
- **Decision Tree Regressor**
- **XGBoost Regressor**

## Model Evaluation

Models were evaluated using:
- **Mean Absolute Error (MAE):** Average of absolute differences between actual and predicted prices.
- **Mean Squared Error (MSE):** Square of the differences between actual and predicted values.
- **R-squared (R²):** Explains the variance in the price predictions.

## Results Summary

- The **Random Forest Regressor** showed the best performance with the lowest MAE and highest R².
- Feature importance analysis revealed that mileage, engine size, and car age had the highest impact on price predictions.

