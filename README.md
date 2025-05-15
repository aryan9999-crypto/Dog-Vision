# Dog Vision Classifier

This project implements a convolutional neural network (CNN) to classify different breeds of dogs from images. The model uses transfer learning from a pre-trained model to improve accuracy and performance on the dataset.

This project is part of the [Kaggle Dog Breed Identification Challenge](https://www.kaggle.com/competitions/dog-breed-identification/leaderboard#), where the objective is to correctly identify the breed of dogs in an image dataset.

## Features
- Dog breed image classification
- Image preprocessing with rescaling and augmentation
- Transfer learning using a pre-trained model (e.g., ResNet, EfficientNet)
- Training, validation, and test accuracy monitoring
- Saving and loading models for reuse

## Dataset
The dataset consists of multiple images of different dog breeds, which are preprocessed and augmented to improve model performance. The dataset can be found as part of the [Kaggle Dog Breed Identification Challenge](https://www.kaggle.com/competitions/dog-breed-identification/data).

## Installation
To run the notebook locally, ensure you have the following installed:
- Python 3.x
- TensorFlow 2.x
- Keras
- Matplotlib
- NumPy

Install the required packages using:
```bash
pip install tensorflow keras matplotlib numpy
