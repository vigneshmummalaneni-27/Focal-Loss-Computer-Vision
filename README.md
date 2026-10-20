# Focal Loss for Computer Vision

## Overview

This project investigates the use of **Focal Loss** to address severe class imbalance in binary computer vision classification.

The experiments use chest X-ray images to classify **Normal** and **Pneumonia** cases using a **ResNet50** model.

## Objectives

- Investigate Focal Loss for imbalanced image classification.
- Study the effect of class imbalance on model performance.
- Explore numerical stability using prediction clipping.
- Evaluate model performance using accuracy, precision, and recall.

## Experiments

Two Jupyter notebooks are included:

### 1. diving-deep-into-focal-loss.ipynb
Main experiment with extended training and evaluation.

### 2. FocalLossImplement.ipynb
Additional implementation and experimental analysis of Focal Loss.

## Results

The main experiment achieved approximately:

- **Test Accuracy:** 89.74%
- **Precision:** 0.92
- **Recall:** 0.92

## Technologies

- Python
- TensorFlow / Keras
- ResNet50
- Jupyter Notebook
- Focal Loss
- Computer Vision

## Dataset

The experiments use chest X-ray images for binary classification between Normal and Pneumonia.

## Author

Vignesh Mummalaneni
