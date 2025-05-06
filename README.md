# Optimizer Comparison in Neural Networks
### Overview
This project explores how different optimization algorithms affect the performance of a neural network in a multi-class classification task. Using a simple toy dataset, we demonstrate the behavior and effectiveness of several commonly used optimizers in training deep learning models.

### Objective
To compare the following optimizers in terms of training accuracy and convergence speed:

SGD (Stochastic Gradient Descent)

AdaGrad

Adam

AdaDelta

RMSprop

### Dataset
The dataset is a small, synthetic set of binary input features and corresponding multi-class targets. It is designed for simplicity and educational purposes, allowing clear visualization of the training behavior across optimizers.

### Model Architecture
The neural network consists of:

An input layer that accepts two features

A single hidden layer with five neurons and ReLU activation

An output layer with three neurons using softmax activation for multi-class classification

The model is compiled with categorical cross-entropy loss and accuracy as the evaluation metric.

### Training Process
Each optimizer is used to train the model for a fixed number of epochs. The training accuracy is tracked and stored for each optimizer to visualize and compare performance trends.

### Results
A line plot is generated showing the training accuracy over epochs for each optimizer. This allows visual assessment of how fast and how well each optimizer leads the model to converge.
