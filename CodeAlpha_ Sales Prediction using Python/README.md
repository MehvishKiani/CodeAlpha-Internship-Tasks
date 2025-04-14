# Sales Prediction Using Python

This project demonstrates how to use machine learning for sales prediction using Python. The goal is to predict product sales based on advertising expenditures in different media: TV, Radio, and Newspaper. The simple model implemented uses Linear Regression from scikit-learn to illustrate a basic approach to forecasting.

## Overview

Sales forecasting is essential for businesses to understand the impact of advertising on their product sales. In this project, a dataset with advertising spend on TV, Radio, and Newspaper is used to predict sales. The following steps are taken:

- **Data Loading and Preprocessing:** The dataset is loaded, inspected for missing values, and cleaned.
- **Feature Selection:** The features include advertising spend on TV, Radio, and Newspaper, while the target variable is Sales.
- **Model Training:** A Linear Regression model is trained on a training subset of the data.
- **Evaluation:** The model is evaluated using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared.
- **Visualization:** The predicted sales vs. actual sales are visualized in a scatter plot.

## Dataset

The dataset `sales_data.csv` is expected to have the following structure:

| Unnamed: 0 | TV    | Radio | Newspaper | Sales |
|------------|-------|-------|-----------|-------|
| 1          | 230.1 | 37.8  | 69.2      | 22.1  |
| 2          | 44.5  | 39.3  | 45.1      | 10.4  |
| 3          | 17.2  | 45.9  | 69.3      | 9.3   |
| 4          | 151.5 | 41.3  | 58.5      | 18.5  |
| 5          | 180.8 | 10.8  | 58.4      | 12.9  |

**Note:** The first column (`Unnamed: 0`) is an index and can be ignored or dropped as needed.
