# Decision Trees and Random Forests for Heart Disease Prediction

## Project Overview

This project demonstrates the implementation of **Decision Tree** and **Random Forest** algorithms for predicting heart disease. It explores tree-based machine learning models, analyzes overfitting, evaluates performance using cross-validation, and identifies the most important features influencing predictions.

## Objective

* Build and visualize a Decision Tree Classifier.
* Analyze and control overfitting using tree depth.
* Train a Random Forest Classifier and compare performance.
* Interpret feature importance scores.
* Evaluate model performance using Cross-Validation.

## Tools and Libraries

* Python
* Pandas
* Matplotlib
* Scikit-learn

## Dataset

The Heart Disease dataset contains patient health information such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Maximum Heart Rate
* Exercise-Induced Angina
* ST Depression
* Other clinical attributes

### Target Variable

* **0** → No Heart Disease
* **1** → Heart Disease

## Project Workflow

### 1. Data Loading

Load the Heart Disease dataset using Pandas.

### 2. Data Preparation

* Separate features and target variable.
* Split data into training and testing sets.

### 3. Decision Tree Classifier

* Train a Decision Tree model.
* Visualize the tree structure.
* Evaluate classification performance.

### 4. Overfitting Analysis

* Compare a fully grown tree with a depth-limited tree.
* Use `max_depth` to improve generalization.

### 5. Random Forest Classifier

* Train an ensemble of decision trees.
* Compare performance with a single Decision Tree.
* Improve prediction accuracy and robustness.

### 6. Feature Importance Analysis

* Identify the most influential features.
* Visualize feature importance using bar charts.

### 7. Cross-Validation

* Perform 5-Fold Cross-Validation.
* Measure model consistency and reliability.

## Models Used

### Decision Tree

A supervised learning algorithm that splits data into branches based on feature values to make predictions.

**Advantages**

* Easy to understand and visualize.
* Handles both numerical and categorical data.
* Requires minimal data preprocessing.

### Random Forest

An ensemble learning technique that combines multiple decision trees.

**Advantages**

* Higher accuracy than a single decision tree.
* Reduces overfitting.
* Provides feature importance scores.

## Evaluation Metrics

* Accuracy Score
* Classification Report

  * Precision
  * Recall
  * F1-Score
* Cross-Validation Accuracy

## Feature Importance

Random Forest calculates importance scores for each feature, helping identify which patient attributes contribute most to heart disease prediction.

## Results

* Decision Tree provides interpretable classification rules.
* Random Forest achieves better generalization and accuracy.
* Cross-validation confirms model stability.
* Feature importance highlights key health indicators affecting predictions.

## Learning Outcomes

* Understanding tree-based machine learning algorithms.
* Visualizing and interpreting Decision Trees.
* Controlling overfitting through depth restriction.
* Using Random Forests for improved performance.
* Evaluating models using Cross-Validation.
* Interpreting feature importance in predictive modeling.

M.Sc. Data Science and Business Analytics
Machine Learning | Deep Learning | Data Analytics Enthusiast.
