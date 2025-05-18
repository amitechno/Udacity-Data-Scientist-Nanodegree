# Udacity-Data-Scientist-Nanodegree

# Sparkify: Churn Prediction for a Music Streaming Platform

## Overview

This project focuses on identifying users likely to churn from **Sparkify**, a fictional digital music service. Using a subset of user activity logs, the goal is to build a machine learning model capable of predicting whether a user will cancel their subscription.

## Requirements

This project relies on the following Python libraries:

- NumPy  
- Pandas  
- Seaborn  
- Matplotlib  
- PySpark (SQL and MLlib)

> All dependencies are available within the Anaconda distribution. Jupyter Notebooks is used as the main development environment.

## Project Objectives

The project was structured around the following goals:

- Load and preprocess a 128MB sample from the full 12GB Sparkify event log dataset.
- Conduct exploratory data analysis (EDA) to uncover behavioral trends.
- Engineer relevant features that capture user engagement and activity.
- Train and evaluate several machine learning models using PySpark MLlib, including:
  - Logistic Regression
  - Random Forest
  - Gradient Boosted Trees
  - Linear SVM
  - Naive Bayes

## File Summary

This repository contains the following files:

- `Sparkify.ipynb`: The primary notebook containing code for data wrangling, feature engineering, model training, and evaluation.
- `Sparkify.html`: HTML export of the notebook for easy viewing.
- Inline markdown cells throughout the notebook explain each part of the analysis process.

## Results

Among the tested classifiers, the **Random Forest** model delivered the best performance, achieving an **F1 score and accuracy of 0.88** on the test set.

## Blog Post

You can read more about the methodology, insights, and challenges in the accompanying blog post (https://medium.com/@vit.amitsharma/predicting-user-churn-with-pyspark-a-comprehensive-guide-3fa23f879a6f).

## Credits

This project was developed as part of the [Udacity Data Scientist Nanodegree Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025). Thanks to Udacity for providing the dataset and learning platform.
