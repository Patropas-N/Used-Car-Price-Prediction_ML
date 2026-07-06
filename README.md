# Used Car Price Prediction using Machine Learning

## Project Overview

This project develops a machine learning model to predict the selling price of used cars based on vehicle characteristics such as present price, age, driven kilometres, fuel type, transmission, ownership history, and brand.

The project follows a complete data science workflow, beginning with data cleaning and feature engineering, followed by exploratory data analysis (EDA), machine learning model development, model evaluation, and prediction.

## Objectives

- Clean and preprocess the dataset.
- Engineer meaningful features from the original data.
- Explore relationships between vehicle characteristics and selling price.
- Train and compare multiple regression models.
- Evaluate model performance using MAE, RMSE, and R² Score.
- Identify the most influential features affecting used car prices.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models

- Linear Regression
- Decision Tree Regression
- Random Forest Regression

## Results

Among the three models, **Linear Regression** achieved the best overall performance:

| Model | MAE | RMSE | R² Score |
|-------|----:|-----:|---------:|
| Linear Regression | **1.51** | **2.54** | **0.7504** |
| Decision Tree | **1.36** | **3.02** | **0.6472** |
| Random Forest | **1.39** | **3.37** | **0.5601** |

The project also demonstrates feature engineering, feature importance analysis, model comparison, and sample prediction using the best-performing model.
