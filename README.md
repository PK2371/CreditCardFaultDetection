# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning. The dataset used is highly imbalanced, with most transactions being legitimate. The primary algorithm implemented is **Logistic Regression**, which predicts whether a transaction is fraudulent or not.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)

---

## Overview

Fraud detection is a critical application of machine learning in the finance industry. This project aims to provide a clear and efficient way to identify fraudulent transactions in a dataset with imbalanced data, ensuring high accuracy without overfitting.

---

## Dataset

The dataset used in this project, `creditcard.csv`, contains **284,807 transactions**, with 30 feature columns including:

- **Time**: Time elapsed since the first transaction.
- **Amount**: Transaction amount.
- **Class**: Binary classification (0 = Legitimate, 1 = Fraudulent).

### Dataset Summary

| Class | Count      | Percentage |
|-------|------------|------------|
| 0     | 284,315    | 99.83%     |
| 1     | 492        | 0.17%      |

The dataset is available for download via the link below.

https://drive.google.com/drive/folders/1kE-VPu0KM271YKJeI4TPAb-j1RrrCh0H?usp=sharing

---

## Dependencies

The following libraries are required to run the project:

- **Python 3.x**
- **Numpy**
- **Pandas**
- **Scikit-learn**

---

## Usage

Ensure you have the dataset file creditcard.csv in the project directory.

Run the script to train and evaluate the model:

```bash
python fraud_detection.py
```

The script will:

- Load and preprocess the dataset.
- Balance the dataset using under-sampling.
- Split the dataset into training and testing sets.
- Train a Logistic Regression model.
- Evaluate the model on both training and testing sets.

---

## Results

The script will output the following results:

- **Training Data Accuracy**: The accuracy of the model on the training set.
- **Test Data Accuracy**: The accuracy of the model on the testing set.
- **Training data accuracy**: 0.94
- **Test data accuracy**: 0.939
