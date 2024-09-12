# CardiGuard: Heart Disease Prediction Model

## Overview

**CardiGuard** is a heart disease prediction tool that leverages machine learning to assess the likelihood of heart disease based on various health metrics. The model is trained using a dataset of heart disease cases and is designed to provide predictions based on user input through an interactive web interface.

## Features

- **Interactive Web Interface**: User-friendly interface built with Gradio to input health metrics and receive predictions.
- **Model**: Trained using a Random Forest Classifier, optimized with GridSearchCV for hyperparameter tuning.

## Requirements

Ensure you have the following Python packages installed:

- `pandas`
- `scikit-learn`
- `joblib`
- `gradio`

You can install these packages using pip:

```bash
pip install pandas scikit-learn joblib gradio
