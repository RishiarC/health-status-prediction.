# health-status-prediction.
An ML-based health status prediction system that analyzes user health metrics to classify conditions as NORMAL or CRITICAL with probability scores, including dataset, training code, and test examples.

# Health Status Prediction (Normal vs Critical)

This project implements a machine learning model that predicts a person's
health status as **NORMAL** or **CRITICAL** based on essential health-related inputs.

## Features
- Binary classification (Normal / Critical)
- Clean and modular Python code
- Includes dataset, training script, preprocessing, and prediction script
- Test samples provided for quick verification

## Input Parameters
The model uses the following features:
- Age
- Sex
- Cholesterol
- Heart Rate
- Diabetes
- Smoking
- BMI
- Stress Level
- Exercise Hours
- Sedentary Hours
- Alcohol Consumption
- Previous Heart Problems
- Medication Use
- Physical Activity Days
- Triglycerides

## Output Format
The model returns:

{
"probability": 0.82,
"prediction": "CRITICAL"
}


