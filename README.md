# Number_Recognition_Using_Python

Number Recognition is  Handwritten Digit Classification using MNIST dataset with TensorFlow This repository contains a simple implementation of a neural network for handwritten digit classification using the popular MNIST dataset.

# Overview

The provided code demonstrates a step-by-step process of creating and training a neural network to classify handwritten digits. The goal is to achieve high accuracy in recognizing digits from 0 to 9. Here's a breakdown of the key components and steps in the code:

1. Importing Libraries: The required libraries, including NumPy for numerical operations, Matplotlib for data visualization, and TensorFlow for deep learning, are imported.

2.Loading the Dataset: The MNIST dataset, consisting of handwritten digit images and corresponding labels, is loaded and split into training and testing sets.

3.Build the neural network model: A simple neural network architecture is defined using the Sequential API from Keras.
The model consists of:

A Flatten layer to convert the 28x28 pixel images into a 1D array.
A fully connected Dense layer with ReLU activation for feature extraction.
A final fully connected Dense layer with softmax activation to output class probabilities.

4.Compiling the Model: The model is compiled with the Adam optimizer and the sparse categorical cross-entropy loss function, which is suitable for multi-class classification problems.

5.Model Training: The model is trained on the training data for a specified number of epochs. During training, the model adjusts its internal parameters to minimize the loss function.

6.Model Evaluation: The trained model's performance is evaluated using the test dataset. Test loss and accuracy are computed to assess how well the model generalizes to new, unseen data.

7.Making Predictions: The trained model is used to predict the digit classes of images from the test dataset. The resulting predictions provide insight into the model's classification capabilities.

The presented code showcases the development and training of a neural network model designed to classify handwritten digits from the renowned MNIST dataset. This example employs TensorFlow and the Keras API, which streamline the creation of deep learning models.


