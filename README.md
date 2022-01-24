# Neural_Network_Charity_Analysis

## Overview

The purpose of this analysis is to use deep-learning neural networks with the TensorFlow platform in Python, in order to classify the success of charitable donations. To achieve this, I preprocess the data for the neural network model, compile, train and evaluate the model, and optimize the model.

Data Sources:
- charity_data.csv
- Software: Python, Jupyter Notebook

## Results

- This deep-learning neural network model is made of two hidden layers with 80 and 30 neurons respectively.
- The input data has 43 features and 25,724 samples.
-The output layer is made of a unique neuron as it is a binary classification.
-To speed up the training process, we are using the activation function ReLU for the hidden layers. As our output is a binary classification, Sigmoid is used on the output layer.
- For the compilation, the optimizer is adam and the loss function is binary_crossentropy.
- The model accuracy is under 75%. This is not a satisfying performance to help predict the outcome of the charity donations.

## Summary

The model did not reach the target of 75% accuracy, meaning that the model is not outperforming.
With a binary classification, we can use a supervised machine learning model, such as the random forest classifier, to combine a multitude of decision trees. Thus we can generate a classified output and evaluate its performance against our deep learning model.
