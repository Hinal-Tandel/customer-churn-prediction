# Customer Churn Prediction

This repository contains a machine learning project for predicting customer churn using a telecom dataset. The workflow includes data preprocessing, exploratory data analysis, feature selection, model training, and evaluation.

## Project Structure

- notebooks/ - Jupyter notebook with the full analysis and modeling workflow
- data/processed/ - processed dataset used for training and evaluation
- requirements.txt - Python dependencies required to run the project
- README.md - project overview and usage guide

## Dataset

The project uses a telecom customer dataset with features such as tenure, monthly charges, contract type, service usage, and churn status. The processed file is stored in:

- data/processed/Telco_Customer_Processed.csv

## Setup

1. Create a Python environment.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook in notebooks/customer_churn_prediction.ipynb to explore the workflow.

## Workflow

- Load and inspect the dataset
- Clean and preprocess features
- Perform exploratory analysis
- Train and evaluate classification models
- Compare model performance and select the best approach

## Notes

This project is intended as a practical machine learning example for churn prediction and can be expanded with additional models, hyperparameter tuning, and deployment steps.
