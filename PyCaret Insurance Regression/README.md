# PyCaret Insurance Regression

This repository contains code for regression analysis on the insurance dataset using PyCaret, an automated machine learning library.

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/lenni991/mini_ML/.git
   cd PyCaret Insurance Regression
   cd insurance
   ```

2. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Dataset

The 'insurance' dataset contains information about individuals and their health insurance charges.

## Code Overview

The `insurance_regression.ipynb` notebook covers:

1. Importing Libraries and Loading the Dataset.
2. Data Preprocessing and Setup.
3. Model Comparison using `compare_models`.
4. Building a Gradient Boosting Regressor with `create_model`.
5. Saving and Loading the Model with `save_model` and `load_model`.
6. Making Predictions with `predict_model`.

## How to Use

1. Open `insurance_regression.ipynb`.
2. Run each cell sequentially.

## Notes

- PyCaret simplifies machine learning workflows, making it easy to customize for different datasets and models.
- The dataset used here is for demonstration purposes; you can replace it with your own data.
- Experiment with various models and hyperparameters to improve performance.
