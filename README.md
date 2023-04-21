# Machine-Learning-INT-354-Project

This is a project for the Machine Learning course (INT 354) at *Lovely Professional University*. The aim of this project is to apply various machine learning techniques to predict the energy output of a combined cycle power plant.

## Dataset

The dataset used for this project is from the UCI Machine Learning Repository: `https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant`

The dataset contains 9568 data points collected from a combined cycle power plant over 6 years (2006-2011), when the power plant was set to work with full load. Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (PE) of the plant.

## Methods

The project involves the following steps:

- Data exploration and visualization
- Data preprocessing and feature engineering
- Model selection and evaluation
- Hyperparameter tuning and optimization
- Model comparison and analysis

The models used for this project are:

- Linear Regression
- Polynomial Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression
- Support Vector Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression
- XGBoost Regression

## Results

The results of the project are summarized in the following table:

| Model | R2 Score | Mean Absolute Error | Root Mean Squared Error |
| --- | --- | --- | --- |
| Linear Regression | 0.9287 | 3.6280 | 4.5571 |
| Polynomial Regression | 0.9444 | 3.1969 | 4.0147 |
| Ridge Regression | 0.9287 | 3.6279 | 4.5571 |
| Lasso Regression | 0.9287 | 3.6278 | 4.5571 |
| Elastic Net Regression | 0.9287 | 3.6278 | 4.5571 |
| Support Vector Regression | 0.9481 | 2.9925 | 3.8479 |
| Decision Tree Regression | 0.9225 | 3.7138 | 4.7336 |
| Random Forest Regression | 0.9619 | 2.5799 | 3.2695 |
| Gradient Boosting Regression | 0.9615 | 2.5925 | 3.2826 |
| XGBoost Regression | 0.9638 | 2.5177 | 3.1979 |

The best performing model is XGBoost Regression, which achieves an R2 score of 0.9638, a mean absolute error of 2.5177 and a root mean squared error of 3.1979.

## Requirements

The project is implemented in Python using Jupyter Notebook. The following libraries are required to run the code:

- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- xgboost

## Usage

To run the code, simply open the `energy.ipynb` file in **Jupyter** Notebook and execute the cells in order.
