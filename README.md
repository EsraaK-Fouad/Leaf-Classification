# Leaf-Classification
The project aims to train a robust neural network model for classifying leaf types and offers an opportunity to explore various hyperparameter settings and optimization techniques for enhancing model performance.


# Project Overview:
This project involves the utilization of the Leaf Classification dataset to build and train a neural network model for leaf classification. The project is divided into two main parts: Data Preparation and Training a Neural Network. Below, we provide an overview of each part:

- Part I: Data Preparation
In the initial phase of the project, you will be tasked with preparing the Leaf Classification dataset for use in a neural network architecture.

- Part II: Training a Neural Network
In the second part of the project, you will create a 3-layer Multi-Layer Perceptron (MLP) model for the classification of leaf types. The key tasks in this part are as follows:

  - Model Architecture:
  
    Build a 3-layer MLP model with one input layer, one hidden layer using the hyperbolic tangent (tanh) activation function, and one output layer.
  - Training Function:
  
    Implement the training function, which includes the neural network training process.
  - Hyperparameter Exploration:
    Experiment with various hyperparameter settings, including:
      - Batch size: Number of examples per training iteration.
      - Hidden size: Different numbers of hidden nodes in the hidden layer to compare performances.
      - Dropout: Implement dropout layers to mitigate overfitting, with varying dropout rates.
      - Optimizer: Try different optimization algorithms, such as SGD, Adam, and RMSProp.
      - Regularization: Apply L2 regularization with different regularization factors.
      - Learning rate and learning rate scheduler: Adjust the learning rate and explore different learning rate scheduling techniques.
  - Performance Evaluation:
  
    Develop an evaluation function to assess the performance of the trained model. This function should load the trained model and evaluate its accuracy and other relevant metrics.
