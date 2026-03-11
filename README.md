# MNIST Handwritten Digit Classification

This project builds a Deep Learning model to classify handwritten digits (0–9) from the MNIST dataset using a Fully Connected Neural Network (Dense Neural Network) implemented with TensorFlow/Keras.

# Dataset

The MNIST dataset is a widely used dataset for image classification and machine learning practice.

# Dataset details:

Total images: 70,000

Training images: 60,000

Test images: 10,000

Image size: 28 × 28 pixels

Color format: Grayscale

Each image represents a handwritten digit from 0 to 9.

# Model Architecture

This project uses a Sequential Neural Network model built using Keras.

Model structure:

Flatten → Dense(128, ReLU) → Dense(10, Softmax)

# Layer Explanation

## 1. Flatten Layer

Converts the 28×28 image into a 784 feature vector.

## 2. Dense Layer

128 neurons

Activation function: ReLU

This layer learns patterns and relationships in the input data.

## 3. Output Layer

10 neurons (one for each digit)

Activation function: Softmax

The model outputs probability scores for digits 0–9.

# Technologies Used

Python

TensorFlow

Keras

NumPy

Matplotlib

Google Colab

# Project Workflow

Load the MNIST dataset

Preprocess the image data

Normalize pixel values

Build the neural network model

Train the model

Evaluate the model performance

Predict handwritten digits
