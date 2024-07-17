# Potato-Disease-Classification-using-CNN

In this project Convolutional Neural Network (CNN) is used to classify potato diseases. The model aims to identify various diseases affecting potatoes based on leaf images.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

Potatoes are one of the most important food crops but its production is often hindered by various diseases. Accurate detection of these diseases can significantly help in managing and controlling their spread. This project uses a CNN to analyze images of potato crops and predict presence of specific disease.

## Dataset

The dataset used in this project contains images of potato leaves categorized into the following classes:
- Early Blight
- Late Blight
- Healthy

The dataset consists of 2152 images and is organized in a directory structure suitable for image classification tasks. The dataset can be downloaded from Kaggle.

## Model Architecture

The model is a Convolutional Neural Network (CNN) built using TensorFlow and Keras. The architecture includes:
- Resizing and rescaling layers
- Data augmentation layers
- Multiple convolutional and max-pooling layers
- Flatten and dense layers

## Usage

1.  **Dataset Preparation**
  - Organize your dataset into training and test sets, containing images of healthy and diseased potato plants.
2.  **Model Training**
  - Use the provided script potato_disease_prediction.py to train the model.
  - Load and preprocesses the dataset, applies data augmentation techniques, defines and compiles the CNN model and trains the model.
  - Adjust hyperparameters as needed (e.g., number of epochs, batch size).
3.  **Evaluation**
  - The script outputs training and validation accuracy and loss plots, which indicate the model's performance over epochs.

## Dependencies
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenCV

## License

This project is licensed under the [MIT License](LICENSE).








