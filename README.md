Dragon Real Estate - Price Predictor

This script builds a machine learning model to predict housing prices based on various features. 
It follows a structured workflow, including data preprocessing, model training, evaluation, and deployment.

Key Features:
Data Loading & Exploration:

Reads housing data from data.csv.
Displays summary statistics and visualizations.
Data Preprocessing:

Splits data into training and test sets using StratifiedShuffleSplit.
Handles missing values using SimpleImputer.
Computes correlations to find important features.
Feature Engineering & Scaling:

Creates new attributes (e.g., TAXRM = TAX / RM).
Standardizes data using StandardScaler.
Model Selection & Training:

Trains a RandomForestRegressor (with options for Linear Regression and Decision Trees).
Evaluates model using RMSE and cross-validation.
Model Persistence & Deployment:

Saves the trained model using joblib.
Loads the model for making predictions on new data.
Usage:

Convert this script into a .py file.
Run it in Visual Studio Code or any Python environment.
Use the trained model (Dragon.joblib) to predict housing prices.
