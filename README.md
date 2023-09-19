# Exploratory Data Analysis (EDA), Statistical Analysis in PySpark and building Predictive Models using Python

## Overview

This project focuses on analyzing weather data, performing exploratory data analysis (EDA), and building predictive models. The primary goals include:

1. Exploring the weather dataset and gaining insights into the relationships between variables.
2. Developing a linear regression model to predict average temperature.
3. Creating a logistic regression model to predict precipitation.
4. Implementing k-fold cross-validation for model evaluation.

## Files

The project consists of the following files:

1. **weather_EDA.ipynb**:
   - This Jupyter Notebook contains code and visualizations for Exploratory Data Analysis (EDA) of the weather dataset. It explores the relationships between different weather variables.

2. **weather_regression.ipynb**:
   - This notebook focuses on building a linear regression model to predict the average temperature. It also includes Box-Cox transformation and stepwise feature selection techniques.

3. **weather_pca.ipynb**:
   - In this notebook, Principal Component Analysis (PCA) is used to understand the relationships between variables in the weather dataset. This helps in dimensionality reduction and feature selection.

4. **weather_cross_validation.ipynb**:
   - This notebook covers the implementation of k-fold cross-validation for model evaluation. It includes train-test splitting and k-fold validation for both regression and logistic models.

## Libraries Used

The project utilizes several Python libraries for data analysis, visualization, and modeling:

- `pyspark.sql` and `pyspark.sql.functions`: Used for Spark DataFrame operations.
- `pandas`: Utilized for data manipulation and analysis.
- `matplotlib.pyplot`: Used for creating data visualizations.
- `factor_analyzer`: Employed for Factor Analysis to understand variable relationships.
- `pingouin`: Used for statistical analysis and hypothesis testing.
- `seaborn` and `numpy`: Additional libraries for data visualization and numerical operations.
- `statsmodels`: Used for regression analysis and model summaries.
- `scipy.stats`: Utilized for Pearson correlation calculation and statistical tests.
- `sklearn`: Includes various functions for model building, preprocessing, and evaluation.

## Target Variables

- **Average Temperature**: This is the target variable for linear regression modeling. The goal is to predict the average temperature based on other weather-related features.

- **Precipitation Dummy**: This is the target variable for logistic regression modeling and k-fold cross-validation. It is a binary variable indicating whether precipitation occurred on a given day.

## Usage

You can follow the order of the notebooks to understand the project flow:

1. Start with **weather_EDA.ipynb** to explore the dataset and gain insights into variable relationships.

2. Move on to **weather_regression.ipynb** to build a linear regression model for predicting average temperature.

3. Refer to **weather_pca.ipynb** to understand how Principal Component Analysis can help in feature selection and dimensionality reduction.

4. Lastly, review **weather_cross_validation.ipynb** to implement k-fold cross-validation for model evaluation.

Each notebook includes code, explanations, and visualizations to facilitate understanding.

---
