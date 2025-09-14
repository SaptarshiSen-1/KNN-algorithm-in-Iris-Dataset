# K-Nearest Neighbors (KNN) on Iris Dataset

This repository contains a Python implementation of the **K-Nearest Neighbors (KNN)** algorithm using the classic **Iris dataset**. The project explores different aspects of the dataset, trains a KNN classifier, evaluates its performance, and visualizes the results through various graphs.

# Project Structure

- `knn_iris.py` – Python script implementing the KNN algorithm with data visualization.
- `README.md` – This file, providing details about the project.

# Dataset

The Iris dataset is a popular dataset in machine learning, which consists of 150 samples from three species of Iris flowers:  
- *Iris Setosa*  
- *Iris Versicolor*  
- *Iris Virginica*

Each sample has four features:  
1. Sepal length (cm)  
2. Sepal width (cm)  
3. Petal length (cm)  
4. Petal width (cm)

The goal is to classify the iris species based on these features.

# Features Implemented

- Data loading and preprocessing using `pandas` and `scikit-learn`.
- Splitting the dataset into training and testing sets.
- Implementation of the KNN classifier.
- Model evaluation using:
  - Accuracy score
  - Classification report
  - Confusion matrix
- Cross-validation for determining optimal value of `k`.
- Visualization of results using `matplotlib` and `seaborn`:
  - Pairplots of features
  - Boxplots of features grouped by species
  - Histograms of feature distributions
  - Confusion matrix plot
  - Accuracy vs. `k` graph
  - Decision boundary plots for all pairs of features

# Requirements

The following Python libraries are required:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
