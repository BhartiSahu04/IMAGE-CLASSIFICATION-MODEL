# IMAGE-CLASSIFICATION-MODEL

This Python script builds and trains an image classification model using TensorFlow and Keras. The model is a Convolutional Neural Network (CNN) designed to classify images from the CIFAR-10 dataset, which consists of 10 different object categories (such as airplanes, cars, and cats). Here's a breakdown of the code:

1. Importing Libraries

TensorFlow and Keras for deep learning.

Matplotlib for visualization.

NumPy for numerical operations

3. Loading and Preprocessing Data

The CIFAR-10 dataset is loaded and split into training and testing sets.

Pixel values are normalized to a range of 0 to 1 by dividing by 255.

4. Defining the CNN Model

Convolutional layers extract image features.

MaxPooling layers reduce spatial dimensions and computational cost.

A Flatten layer converts feature maps into a 1D array.

Fully connected layers classify the images.

The Softmax activation function is used in the output layer to predict one of 10 categories.
