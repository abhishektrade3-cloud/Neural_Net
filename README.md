# Handwritten Digit Recognition using MLP (Neural Network)

## Overview

This project implements a **Multi-Layer Perceptron (MLP)** model to classify handwritten digits (0–9).
The workflow includes data preprocessing, visualization, hyperparameter tuning, and model evaluation.

---

## Key Features

* Data normalization for stable training
* Train-test split using best practices
* Hyperparameter tuning with Randomized Search
* Visualization of digit samples and predictions
* Performance evaluation using accuracy

---

## Tech Stack

* Python
* NumPy
* Matplotlib
* Scikit-learn

---

## Workflow

1. **Data Preprocessing**

   * Extract labels and features
   * Normalize pixel values (0–255 → 0–1)

2. **Visualization**

   * Display sample handwritten digits

3. **Model Training**

   * MLP Classifier (Neural Network)
   * Hyperparameter tuning using RandomizedSearchCV

4. **Evaluation**

   * Accuracy score on test dataset

5. **Prediction Visualization**

   * Display test images with predicted labels
