                                          🌸 Flower Classification using CNN

📌 Project Overview

This project demonstrates image classification on a flower dataset using Convolutional Neural Networks (CNNs) with TensorFlow/Keras.
The notebook explores:

Loading and preprocessing images

Data augmentation

Building CNN architectures

Hyperparameter tuning (filters, hidden layers, dropout)

Preventing overfitting with regularization and early stopping

Model evaluation and visualization

📂 Dataset

The dataset used is 5 Flower Types Classification Dataset
.
It contains images of 5 flower categories, used for training and validation.

Loaded via kagglehub into the notebook.

Preprocessing handled with ImageDataGenerator (rescaling, augmentation, train/validation split).

Main steps:

Data Preparation – Load and augment dataset

Model Building – Define CNN with tunable hyperparameters

Training – Train multiple configurations

Evaluation – Plot accuracy/loss curves, compare models

Prediction – Run inference on test images

🧠 Model Architectures

The notebook explores multiple CNN configurations:

Conv2D → MaxPooling → Dense layers

Variable filters: 32, 64

Variable hidden layers: 1, 2

Dropout rates tested: 0.3, 0.5

EarlyStopping callback used for overfitting control


