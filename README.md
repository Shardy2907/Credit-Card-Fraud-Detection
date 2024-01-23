# Isolation Forest for Credit Card Fraud Detection

## Overview

This repository contains code for implementing an Isolation Forest model for anomaly detection in credit card fraud. The model is trained on the "Credit Card Fraud Detection" dataset available on Kaggle. The Isolation Forest algorithm is a powerful technique for identifying anomalies or outliers in a dataset, making it particularly well-suited for detecting fraudulent transactions in credit card data.

## Dataset

- **Dataset Description:** The dataset contains a mixture of legitimate and fraudulent transactions, and the goal is to build a model that can accurately identify fraudulent transactions based on various features.

- **Dataset Link:** [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Dataset Structure:**
  - `creditcard.csv`: CSV file containing the data and corresponding labels.

## Model
The Isolation Forets Model is implemented.
- The algorithm builds isolation trees, which are binary trees recursively built by randomly selecting a feature and then randomly selecting a split value for that feature within the range of its values.
- The process continues until each instance in the dataset is isolated in a leaf node.
- Multiple isolation trees are created, and their predictions are combined to form an ensemble.
- Anomalies are expected to have shorter average path lengths across the trees and lower scores.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.
