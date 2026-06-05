# Energy-Demand-Forecasting-Using-Deep-Learning
Time series forecasting of energy demand using LSTM networks | Tensorflow, Pandas, scikit-learn, matplotlib.pyplot
# Energy Demand Forecasting Using Deep Learning (LSTM)

## Overview

This project develops a Long Short-Term Memory (LSTM) deep learning model for short-term electricity demand forecasting. Accurate energy demand prediction is essential for power system operation, energy management, load balancing, and smart grid applications.

The model learns temporal patterns from historical energy consumption data and predicts future electricity demand over a 24-hour forecasting horizon.

## Objectives

* Develop an end-to-end deep learning pipeline for energy demand forecasting.
* Perform data preprocessing and feature engineering for time-series analysis.
* Train and evaluate an LSTM-based forecasting model.
* Visualize forecasting performance using prediction and error analysis plots.

## Dataset

The project utilizes historical electricity demand data containing time-dependent consumption patterns.

### Preprocessing Steps

* Missing value handling
* Feature scaling using Min-Max normalization
* Time-series sequence generation
* Train-test split
* Data reshaping for LSTM input requirements

## Methodology

### Data Preparation

The raw data was cleaned and transformed into supervised learning sequences suitable for deep learning models.

### LSTM Model Architecture

The forecasting model consists of:

* Input sequence layer
* LSTM hidden layers
* Dense output layer
* Mean Squared Error (MSE) loss function
* Adam optimizer

### Training

The model was trained using historical demand data to learn temporal dependencies and demand trends.

## Results

The model successfully captured electricity demand patterns and generated accurate short-term forecasts.

Key outputs include:

* Actual vs Predicted Demand plots
* Training and Validation Loss curves
* Forecast performance evaluation metrics
  ## Evaluation Metrics
  MAE: 399.07294860396814
  RMSE: 685.6663674469139
  MAPE: 1.324104286380138


## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn
* TensorFlow / Keras
* Jupyter Notebook / Google Colab



## Future Improvements


* Multi-step forecasting
* Attention-based LSTM architectures
* Transformer-based time-series forecasting
* Integration with real-time energy data streams
* Deployment as a web application using Hugging Face Spaces or Streamlit

Authored by
Umar Ibrahim Saleh

Electrical Engineering Graduate | Machine Learning and Intelligent Energy Systems Research Enthusiast

