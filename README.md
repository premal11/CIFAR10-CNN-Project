# CIFAR-10 Image Classification using CNN

This project implements a Convolutional Neural Network (CNN) from scratch for image classification on the CIFAR-10 dataset. It uses techniques such as hyperparameter tuning, Batch Normalization, and data augmentation to improve model performance.

## Key Features:
- Base accuracy improved from **53% to 80%**
- Trained on **50,000 training samples**
- Applied **data augmentation** (random flips, rotations, zooms)
- Used **Batch Normalization** and **Dropout** for regularization

## Model Architecture:
- Multiple convolutional layers with max-pooling
- Batch Normalization between Conv/Dense and Activation layers
- Dropout for preventing overfitting
- Fully connected layers for final classification

## Requirements:
- Python 3.x
- TensorFlow 2.x
- Keras
- Numpy
- Matplotlib
