# Linear-Regression-Housing-Price-Prediction
# California Housing Price Prediction using Linear Regression

## Project Overview

This project implements a complete Linear Regression pipeline using the California Housing dataset. The objective is to predict the median house value based on several housing-related features.


## Dataset

The dataset used is the California Housing dataset, which contains information about housing districts in California.

Target Variable:
- median_house_value

Features include:
- longitude
- latitude
- housing_median_age
- total_rooms
- total_bedrooms
- population
- households
- median_income
- ocean_proximity



## Project Steps

1. Load the dataset.
2. Explore and understand the data.
3. Handle missing values.
4. Encode categorical features.
5. Perform Exploratory Data Analysis (EDA).
6. Split the dataset into training and testing sets.
7. Train a Linear Regression model.
8. Predict house prices.
9. Evaluate the model using:
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - Mean Absolute Error (MAE)
10. Visualize Actual vs Predicted values.


## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn



## Machine Learning Model

- Linear Regression


## Evaluation Metrics

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)


## Conclusion

The Linear Regression model was successfully trained to estimate California house prices. Data preprocessing, feature encoding, model training, prediction, and evaluation were completed successfully. The project demonstrates a complete end-to-end machine learning workflow using Scikit-learn.

## Results

The Linear Regression model achieved the following evaluation results:

- Mean Squared Error (MSE): 4,982,595,974.25
- Root Mean Squared Error (RMSE): 70,587.51
- Mean Absolute Error (MAE): 50,670.50

These results indicate that the model was able to learn the relationship between the housing features and the target variable. Although the predictions are not perfect, the model provides a reasonable estimate of house prices and demonstrates the effectiveness of Linear Regression for this dataset.
