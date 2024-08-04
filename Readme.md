# Face Mask Detection

## Overview

The Face Mask Detection project is a computer vision application designed to classify images of people into three categories: "with mask," "mask worn incorrectly," and "without mask." This project uses a Convolutional Neural Network (CNN) built with Keras and TensorFlow to achieve this classification. The project involves several key steps, including data preparation, model training, and evaluation.

## Features

- **Data Preparation**: Parses XML annotations and prepares image data by cropping faces and organizing them into training, validation, and test sets.
- **Model Architecture**: Utilizes a CNN with layers for convolution, max-pooling, dropout, and dense connections to classify images.
- **Data Augmentation**: Applies image augmentation techniques such as horizontal flipping, zoom, and shifting to improve model generalization.
- **Model Evaluation**: Evaluates the model's performance on test data and visualizes results using confusion matrices and accuracy/loss plots.

