# House Price Prediction

This project explores the relationship between housing features and unit area price using regression techniques. The dataset consists of real estate property attributes and aims to predict property prices based on various location and facility features.

## Dataset Overview

The dataset contains no missing values, and all columns are numerical. Key features include:

- Distance to the nearest MRT station  
- Number of nearby convenience stores  
- House age  
- Latitude and Longitude

The target variable is **house price of unit area**.

## Data Exploration Highlights

- The target variable (price per unit area) is **right-skewed** and includes significant **outliers**.
- Strong correlation identified between proximity to MRT and price.
- Higher number of convenience stores also correlates with higher prices.

## Techniques Used

- **Data Cleaning** & Outlier Detection  
- **Visualizations**: Histograms, Boxplots, Correlation Heatmaps  
- **Regression Models**:
  - Linear Regression  
  - Ridge Regression  
  - Lasso Regression  
  - Polynomial Regression  
- **Model Evaluation**:
  - MSE, MAE, R² score  
  - Learning Curves  
  - Hyperparameter Tuning with GridSearchCV

## 📈 Key Findings

- Outliers significantly impact model performance.
- Linear and Lasso regression performed well after handling skewness.
- MRT proximity and number of convenience stores are strong predictors of price.
