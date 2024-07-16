# CNN Model for MNIST Digit Classification
This repository features a Convolutional Neural Network(CNN) model implemented in Tensorflow and keras.This model is trained on the MNIST dataset to classify handwritten digits accurately

# MNIST CLASSIFICATION
# Dataset
The MNIST database (Modified National Institute of Standards and Technology database) is widely-used dataset for tarining and evaluting image processing systems.It contains a large collection of handwritten digit images, including a training set of 60,000 grayscale images, each sized at 28x28 pixels, representing the digit 0 to 9, and a test set of 10,000 images. This digits are a subset of a more extensive set provided by NIST, and have been preprocessed to be size-normalized and centered within a fixed-size image.
Sample images from MNIST test dataset:
![image](https://github.com/user-attachments/assets/7aec13bb-046e-446b-a235-7c4a631afdef)

# About CNN
A Convolutional Neural Network (CNN) is a type of deep learning model specifically designed for processing structred grid data, such as images.CNNs utilize convolutional layers to automatically and adaptively learn spatial hierarchies of features from input images.By employing techniques like pooling and dropout, CNNs effectively capture local and global patterns, making them highly effective for image recognition,classification, and other computer vision tasks.
# Image classification CNN model on MNIST dataset
The model is structured with two convolutional layers, each followed by max-pooling layers. The resulting output is flattened and passed through dense layers, ultimately producing the final classification output.
# Requirements
Python 3,
TensorFlow,
Keras,
Google colab (optional, for running the provided example notebook)

# Keras implementation accuracy
Train accuracy: 99.72%
Test accuracy: 99.23%
# Tensorflow implementation accuracy
Test accuracy: 97.62%
