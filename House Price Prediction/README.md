# House Price Prediction

## Overview

The House Price Prediction project is a comprehensive data analytics initiative aimed at predicting house prices based on various features and factors. This README.md file serves as a guide to understanding the project's structure, objectives, and how to use it.

![1_D6s2K1y7kjE14swcgITB1w](https://github.com/Atharvak29/Data_Analysis_py/assets/70752461/631c8dc5-1dbf-4ae4-831a-6dd2b47f9cd5)

## Table of Contents

- [Project Description](#project-description)
- [Results](#results)
- [Project Steps](#project-steps)

## Project Description

The House Price Prediction project focuses on developing predictive models for estimating house prices. The key goals of this project are as follows:

- **Data Exploration**: Exploring and understanding the dataset, including features, data distribution, and relationships.

- **Feature Engineering**: Selecting and engineering relevant features for accurate price predictions.

- **Model Building**: Building machine learning models to predict house prices based on historical data.

- **Model Evaluation**: Assessing the model's performance through various evaluation metrics.

This project leverages data preprocessing, feature selection, regression techniques, and model evaluation to achieve its objectives.

## Results

The results of the analysis, including model performance metrics, feature importance, and house price predictions, are available in the House Price Prediction .ipynb file.

## Project Steps

Here are the detailed steps followed in this project:

1. **Read the Data**
2. **Drop Unnecessary Columns**: Remove columns with no statistical importance.
3. **Missing Data Treatment**
4. **Exploratory Data Analysis**
   - 4.1 Check for Skew in X columns
   - 4.2 Remove Skew
   - 4.3 Correlation
   - 4.4 Drop columns from X having very minute or no correlation
5. **Preprocessing**
   - 5.1 Standardization of continuous columns
   - 5.2 One-Hot Encoding of categorical columns
6. **Divide Data in Training & Testing Set**: Use a random state of 31 and split the data into an 80% training set and a 20% testing set.
7. **Create a Backward Elimination OLS Model**
8. **Remove Unnecessary Columns Based on p-value**
9. **Create a Linear Regression Model on the Basis of Selected Columns**
10. **Find Training and Testing Error**: Check for Overfitting or Not
11. **Check for Collinearity and Multicollinearity**
12. **Ridge and Lasso Regression**
13. **Create a Tuning Grid**
14. **GridSearchCV Model to Find Best Penalty Value for Ridge and Lasso**
15. **Using the Best Value, Create a Ridge or Lasso Model**
16. **Check for Overfitting**
17. **Using the Best Model, Make Final Predictions** (This step will be explained in class)

Feel free to explore each step in detail within the project's Jupyter Notebook.
