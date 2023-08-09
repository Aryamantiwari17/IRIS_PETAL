# IRIS_PETAL
Iris Classification using Logistic and Softmax Regression
This repository contains a Python implementation of a classification task using two different techniques: Logistic Regression and Softmax Regression. The goal of this project is to demonstrate how to apply these classification algorithms to the well-known Iris dataset, which contains information about different species of iris flowers and their attributes.

# Project Overview
Iris Dataset: The Iris dataset is a popular dataset in the machine learning community, often used as a benchmark for classification algorithms. It includes measurements of sepal length, sepal width, petal length, and petal width for three different species of iris flowers: Iris setosa, Iris versicolor, and Iris virginica.

Logistic Regression: In this project, we utilize scikit-learn's LogisticRegression class to perform binary classification on the Iris dataset. We preprocess the dataset, split it into training and testing sets, and then train a logistic regression model. The trained model is evaluated on the testing set to assess its performance.

Softmax Regression (Multinomial Logistic Regression): Additionally, we delve into multiclass classification using the Softmax Regression technique, which is a generalization of logistic regression to handle multiple classes. We employ scikit-learn's LogisticRegression class with appropriate parameters to enable the Softmax activation function, allowing the model to predict the probabilities of each class for a given input.

# Results
The project demonstrates the effectiveness of both Logistic Regression and Softmax Regression for classifying iris flowers into different species based on their attributes. The classification accuracy and predicted class probabilities provide insights into how well the models generalize to new, unseen data.
