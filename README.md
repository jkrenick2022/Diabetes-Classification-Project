# Diabetes Classification Project

## Problem Statement
Predict whether a person has diabetes using various health-related features.

## Dataset
The project uses the [Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset) from Kaggle.

## Features
- Demographic: gender, age
- Medical: hypertension, heart_disease, smoking_history, bmi, HbA1c_level, blood_glucose_level

## Evaluation Metrics
- Primary: Accuracy Score
- Additional: F1 Score, Precision, Recall, ROC_AUC, Confusion Matrix

## Goal
Train a model with an accuracy score of at least 93% (subject to evaluation of metric appropriateness).

## Project Structure
- `main.ipynb`: Jupyter notebook containing the main analysis and model development
- `requirements.txt`: List of required Python packages
- `data.csv` : The data file downloaded from Kaggle.
- `model.joblib` : The exported model, anyone can load it in and make predictions with it automatically.

## Setup and Installation
1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook main.ipynb`

