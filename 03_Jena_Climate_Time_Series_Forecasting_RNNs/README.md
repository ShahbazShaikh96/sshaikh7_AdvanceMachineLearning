# Jena Climate Forecasting: RNN, GRU, LSTM, and Conv1D-GRU Comparison

This assignment uses the Jena Climate dataset to forecast temperature 24 hours ahead with deep learning time-series models.

## Objective

The goal is to compare recurrent and sequence-based architectures for weather forecasting and identify the model with the best validation and test mean absolute error.

## Main Work

- downloads and loads the Jena Climate dataset
- performs chronological train, validation, and test splitting
- normalizes features using the training set
- builds sliding-window sequence datasets
- trains multiple forecasting architectures
- compares validation MAE and test MAE
- visualizes training curves and prediction results

## Models Compared

- Dense baseline
- Simple GRU
- Stacked GRU
- Stacked LSTM
- Conv1D-GRU hybrid model

## Key Result

The Stacked GRU model performs best in the reported experiment, achieving the lowest validation MAE and strong test MAE compared with the other architectures.

## Files

- `Jena_Climate_Time_Series_Forecasting_RNNs.ipynb`: full notebook with model training and evaluation
- `Jena_Climate_Time_Series_Forecasting_RNNs_Report.pdf`: rendered report
