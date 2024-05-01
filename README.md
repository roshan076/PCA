# PCA on Random Gaussian Distribution, Iris dataset and Diabetes dataset

## Contents

- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Dataset Description](#dataset-description)
- [Result & Analysis](#result--analysis)

## Introduction

Principal Component Analysis (PCA) is a widely used statistical technique for the dimensionality reduction and data analysis. This study explores the application of PCA on distinct datasets: a random Gaussian distribution, iris dataset and the diabetes datasets. By using PCA, a new set of variables known as principal components is derived from the original dataset, capturing maximum variance in the data. The analysis reveals the dominance of certain principal components in capturing data variability and explores the challenges of effectively separating target columns using the extracted components.

## Dependencies

To run the code, you need to have the following dependencies installed:
- Python 3.x
- NumPy
- Matplotlib

## Dataset Description
The random Gaussian distribution is generated using the random function in NumPy library, the iris dataset is collected from the scikit-learn library. It contains the 4 attributes and 150 instances with the target column containing the information of the three different flowers setosa, versicolor and virginica.

The diabetes dataset is collected from the Kaggle. The dataset contains the 768 instances and 8 attributes with a target class denoting the patient has diabetes or not. The original source for the diabetes dataset is The National Institute of Diabetes and Kidney Diseases. These instances were chosen from a bigger database under a number of restrictions. Particularly, all patients at this facility are Pima Indian women who are at least 21 years old.

## Result & Analysis

### Random Gaussian Distribution
The variance
explained by each principal component of the random
Gaussian distribution dataset are 99.10% and 0.90%. The
first principal component captures the majority of the data
variability whereas the second principal component captures
the negligible amount of the information.


