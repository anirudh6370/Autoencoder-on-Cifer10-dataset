# CIFAR-10 Autoencoder Project

## Overview
This project demonstrates the implementation of a simple autoencoder using the CIFAR-10 dataset. The main objective is to showcase the functionality and working principle of autoencoders. 

Autoencoders are neural networks designed for unsupervised learning tasks. They are composed of an encoder and a decoder, where the encoder compresses the input data into a latent representation, and the decoder reconstructs the original data from this representation. Autoencoders are commonly used for tasks like dimensionality reduction, data denoising, and feature learning.

## Code Description
The provided code performs the following steps:

1. **Data Loading**: The CIFAR-10 dataset is loaded using TensorFlow's built-in dataset loader.

2. **Data Preprocessing**: Pixel values of the images are normalized to the range [0, 1] and reshaped to flatten the images.

3. **Model Architecture**: The autoencoder model architecture is defined using Keras functional API. It consists of an encoder and a decoder, each containing several dense layers.

4. **Model Compilation and Training**: The model is compiled using the Adam optimizer and binary cross-entropy loss. It is trained on the training data while monitoring the validation loss.

5. **Model Evaluation**: After training, the model is evaluated on the test set, and the reconstructed images are generated.

6. **Visualization**: The original and reconstructed images are visualized for comparison, and a plot of training and validation loss is generated.

## Instructions for Running the Code
To run the code:

1. Ensure TensorFlow and Keras are installed. If not, you can install them via pip:

