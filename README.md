# Fitness Anomaly Detection

## Overview

This project explores anomaly detection in fitness-related data using unsupervised machine learning techniques. The goal is to identify unusual patterns in fitness measurements and compare different approaches to detecting potential anomalies.

## Dataset

The dataset contains **500 observations and 5 features** related to fitness data.

## Methods

Three machine learning algorithms were explored:

- **Isolation Forest** — identifies observations that differ from typical patterns.
- **K-Means Clustering** — groups similar observations to help investigate unusual data points.
- **One-Class SVM** — learns the boundaries of typical observations and identifies potential outliers.

## Data Preprocessing and Visualization

- Applied `StandardScaler` to standardize the features.
- Used Principal Component Analysis (PCA) to reduce dimensionality for visualization and pattern exploration.
- Set the Isolation Forest contamination parameter to `0.05`, corresponding to an expected anomaly proportion of 5%.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- PCA and unsupervised machine learning

## Project Goals

- Explore different approaches to anomaly detection.
- Compare the behavior of multiple algorithms on the same dataset.
- Visualize patterns and investigate observations flagged as potential anomalies.

## Note

Anomalies detected by these models are statistical outliers and do not automatically indicate a health or medical problem.
