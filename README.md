## Project Overview

This project was completed as part of a recruitment task. The goal was to build a predictive model based on a provided dataset.

## Notebooks Overview

### data-exploration.ipynb

In this notebook, I performed an initial exploration of the dataset to better understand the structure and quality of the data.

### experiments.ipynb

Here I conducted various experiments, including:

*   Testing different strategies for imputing missing values
*   Comparing different types of models
*   Trying out ideas for new features and analyzing how they affect model performance (feature engineering)

The tested models included Random Forest, LightGBM, Linear Regression, and Gradient Boosting.

For missing data imputation, I evaluated several techniques such as mean, median, KNN, and MICE.

### train_final_model.ipynb

This notebook contains the training pipeline for the final model, which is an ensemble of two models: Random Forest and LightGBM.

### predictions directory
This folder contains predictions for the test set.