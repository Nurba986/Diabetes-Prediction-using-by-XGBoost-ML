# Diabetes Prediction using XGBoost

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Project Overview
A machine learning project focused on early diabetes detection, using by XGBoost algorithm. The model is optimized for recall, to prioritize identifying potential diabetes cases, achieving 93% recall, while maintaining good overall performance (ROC AUC: 0.97).


## Key Features

- Data Processing: Handle categorical and numerical features with proper encoding and scaling
- Model Optimization: XGBoost classifier, optimized, using by Optuna for hyperparameter tuning
- Safety-First Approach: Prioritizes catching potential diabetes cases (93% recall) over avoiding false alarms
- Comprehensive Analysis: Includes statistical analysis and visualizations of predictions
- Production Ready: Complete pipeline from data preprocessing to prediction

## Project Structure
```
Diabetes Prediction using by XGBoost ML/
├── artifact/                               # Directory for saving artifacts like models, encoders, scalers
│   ├── models/                             # Trained model files
│   └── scalers_and_encoders/               # Preprocessing components (e.g., encoders, scalers)
│
├── Dataset/                                # Directory for dataset
│   ├── diabetes_predictions.csv            # Predicted results file
│   ├── diabetes_test.csv                   # Testing dataset
│   ├── diabetes_train.csv                  # Training dataset
│   └── processed_data.csv                  # Preprocessed data file
│
├── notebook/                               # Jupyter Notebooks for project development
│   ├── diabetes_eda.ipynb                  # Exploratory Data Analysis (EDA)
│   ├── diabetes_model_training.ipynb       # Model training and hyperparameter tuning
│   └── diabetes_prediction_pipeline.ipynb  # Prediction pipeline
│
├── LICENSE                                 # License file for the project
├── README.md                               # Project README file
└── requirements.txt                        # File containing required Python libraries
```

## Model Performance

Recall: 93%
Precision: 42%
ROC AUC Score: 0.97