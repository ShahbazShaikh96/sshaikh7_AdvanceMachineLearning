# IMDB Sentiment Classification: Neural Network Architecture and Regularization Comparison

This assignment compares dense neural network designs for binary sentiment classification using the IMDB movie review dataset.

## Objective

The goal is to understand how changes in neural network architecture and training choices affect validation and test performance.

## Main Work

- loads the IMDB movie review dataset with the top 10,000 words
- converts reviews into multi-hot bag-of-words vectors
- trains multiple dense neural network models
- compares depth, width, activation functions, and loss functions
- tests regularization using dropout and L2 penalties
- reports validation and test accuracy for each model

## Methods and Models

The notebook compares models such as:

- one-layer, two-layer, and three-layer dense networks
- 16, 32, 64, and 128 hidden units
- ReLU vs Tanh activation
- binary crossentropy vs mean squared error
- dropout and L2 regularization variants

## Key Result

The strongest model in the notebook is the 16-unit ReLU network with dropout and binary crossentropy, which achieved the best validation and test performance among the tested configurations.

## Files

- `IMDB_Sentiment_Neural_Network_Architecture_Comparison.ipynb`: full notebook with model experiments and results
