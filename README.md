# Image Captioning with Deep Learning
This project implements an image captioning system using deep learning techniques. Given an image, the model generates a descriptive caption that describes the contents of the image.

## Overview
The image captioning system consists of two main components:

Image Feature Extraction: The features of the input image are extracted using a pre-trained Convolutional Neural Network (CNN). In this project, the VGG16 model is used to extract features from images.

Caption Generation: The extracted image features are then fed into a Recurrent Neural Network (RNN), specifically a Long Short-Term Memory (LSTM) network, which generates captions based on the visual content.

## Requirements
Python 3.x
TensorFlow 2.x
tqdm
numpy

## References
VGG16 Paper: Very Deep Convolutional Networks for Large-Scale Image Recognition

LSTM Paper: Long Short-Term Memory
