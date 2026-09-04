# EncoderX Task 1 — Image Classification

## Overview

This project implements a Convolutional Neural Network (CNN) for image classification using the CIFAR-10 dataset. The project was developed as part of the EncoderX AI/ML Internship — Task 1.

## Dataset

The CIFAR-10 dataset contains 60,000 color images divided into 10 classes:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

The dataset contains:

* 50,000 training images
* 10,000 test images
* Image size: 32 × 32 × 3

## Model

A CNN-based image classification model was developed using TensorFlow/Keras.

The workflow includes:

1. Loading the CIFAR-10 dataset
2. Preprocessing and normalization
3. Building the CNN architecture
4. Training the model
5. Evaluating model performance
6. Generating performance visualizations
7. Saving the trained model

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab
* Jupyter Notebook

## Project Structure

```text
EncoderX-Task1-Image-Classification/
│
├── EncoderX_Task1_Image_Classification.ipynb
│
├── model/
│   └── cifar10_cnn.keras
│
├── results/
│   ├── accuracy_curve.png
│   ├── loss_curve.png
│   ├── confusion_matrix.png
│   ├── training_history.csv
│   └── evaluation_results.csv
│
└── README.md
```

## Results

The project evaluates the CNN using classification accuracy and loss curves. A confusion matrix is also generated to analyze classification performance across the ten CIFAR-10 classes.

The trained model is saved in Keras format for future use.

## How to Run

The notebook can be opened and executed using Google Colab or Jupyter Notebook.

Run the notebook cells sequentially to:

* Load the dataset
* Preprocess the images
* Train the CNN
* Evaluate the model
* Generate results
* Save the trained model and evaluation files

## Author

**Saiqa Maliha**

AI/ML Internship — EncoderX

## Project

CNN-based image classification using the CIFAR-10 dataset.
