# Time Series Forecasting with AI Models

NOTE: The notebook was used for the whole of the project.
It includes all models tested as well as hyperparameter tuned models.
These models were compared against themselves and each other to determine the most optimal one.

results/summaries shows all model summaries found by the notebook
results/figures has all graphs plotted during our project
results/comparisons has all models compared with each other

## Smart Grid Dataset Analysis

### Project Overview

This project investigates time series data analysis and forecasting using a variety of classical statistical models and modern deep learning architectures. The Smart Grid Dataset from Kaggle is used as the primary data source. The goal is to evaluate and compare model performance before and after hyperparameter optimization.

### Dataset

Source: Smart Grid Dataset (Kaggle)

Type: Time series energy-related data

Purpose: Forecasting and performance comparison of multiple AI and statistical models

### Methodology
1. Exploratory Data Analysis (EDA)

Data cleaning and preprocessing

Trend, seasonality, and stationarity analysis

Visualization of time series behavior

2. Base Model Development

The following models were implemented as baseline models:

Naive Forecasting

ARIMA

SARIMA

RNN

LSTM

GRU

TCN

Transformer

3. Hyperparameter Optimization

Each base model was further optimized using:

Keras Tuner

Grid Search

Optimized models were evaluated and compared against their base versions.

4. Model Evaluation and Comparison

All models were compared:

Across different model types

Between base vs. optimized versions

Performance metrics and visual comparisons were used for evaluation.

### Results

All figures, model summaries, and comparison charts are stored in the results/ folder.

This includes:

Training and validation curves

Forecast vs. actual plots

Performance comparison charts

Model architecture summaries

Technologies Used

Python

NumPy, Pandas, Matplotlib

Scikit-learn

TensorFlow / Keras

Keras Tuner

Statsmodels (for ARIMA/SARIMA)
