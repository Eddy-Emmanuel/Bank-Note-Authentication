# Bank Note Authentication Readme

## Overview

This project focuses on the authentication of bank notes using machine learning models. The dataset contains five columns: variance, skewness, curtosis, entropy, and class. The goal is to build and evaluate three different classification models: Logistic Regression, Random Forest Classifier, and MLP (Multi-Layer Perceptron) Classifier.

## Dataset

The dataset consists of the following columns:

1. **Variance:** Variance of the image wavelet transformed image (continuous).
2. **Skewness:** Skewness of the image wavelet transformed image (continuous).
3. **Curtosis:** Curtosis of the image wavelet transformed image (continuous).
4. **Entropy:** Entropy of the image wavelet transformed image (continuous).
5. **Class:** Binary label indicating the authenticity of the bank note (0 or 1).

## Models

Three different classification models are implemented:

1. **Logistic Regression:** A linear model for binary classification.
2. **Random Forest Classifier:** An ensemble model based on decision trees.
3. **MLP Classifier:** A Multi-Layer Perceptron neural network for classification.

## Cross Validation

Cross-validation is performed on all three models to assess their performance. This ensures that the models are robust and not overfitting to the training data.

## Model Evaluation

The following metrics are used for model evaluation:

1. **Confusion Matrix:** A table showing the true positive, true negative, false positive, and false negative counts.
2. **ROC Curve (Receiver Operating Characteristic Curve):** A graphical representation of the model's performance across different thresholds.
3. **Classification Report:** Provides precision, recall, F1-score, and support for each class.
4. **Interpret Results:** Review the generated confusion matrices, ROC curves, and classification reports to understand the performance of each model.
