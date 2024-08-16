# MNIST Digits Classification Project

This project focuses on building a machine learning pipeline to classify handwritten digits using the MNIST dataset. The MNIST dataset is a well-known benchmark in the field of machine learning and computer vision.

## Project Overview

The MNIST dataset consists of 70,000 28x28 grayscale images of handwritten digits, split into a training set of 60,000 images and a test set of 10,000 images. The goal of this project is to develop a model that can accurately classify these images into one of ten classes (0-9).

## Key Features

- **Data Handling**: The dataset is loaded and preprocessed using TensorFlow, with the training and test sets prepared for model training and evaluation.
- **Model Training**: The notebook includes the training of a neural network using TensorFlow/Keras.
- **Evaluation**: The trained model is evaluated on the test set to determine its accuracy and performance.
- **Visualization**: Matplotlib is used to visualize sample images from the dataset, as well as the model’s performance metrics.

## Dependencies

To run this notebook, you need the following Python packages:
- `tensorflow`
- `matplotlib`
- `numpy`

These can be installed via pip:

```bash
pip install tensorflow matplotlib numpy
```