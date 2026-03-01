# ML X-Ray Pneumonia Detection (CNN-Based)

## Overview
This project implements a convolutional neural network (CNN) for automated pneumonia detection using chest X-ray images.

## Objective
To evaluate deep learning performance on medical image classification using real-world labelled datasets.

## Dataset
- 5,800+ labelled chest X-ray images
- Binary classification: Pneumonia vs Normal
- Preprocessing: normalization and augmentation techniques

## Model Architecture
- Convolutional Neural Network (CNN)
- ReLU activations
- Dropout regularisation
- Cross-entropy loss
- Adam optimizer

## Results
- Achieved 90%+ validation accuracy
- Evaluated using confusion matrix, precision, recall, and F1-score
- Compared performance against baseline KNN model

## Key Learnings
- Dropout significantly reduced overfitting.
- Class imbalance impacts sensitivity.
- Medical imaging tasks require careful preprocessing and validation.
