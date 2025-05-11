# Sonar-Rock-vs-Mine-Predictive-Model-

This project implements a machine learning model to classify sonar signals as either rocks or mines using logistic regression. The dataset used is the Sonar Dataset, a well-known benchmark in binary classification.
Project Overview

    Goal: Predict whether an object is a rock or a mine based on sonar signal readings.

    Model Used: Logistic Regression

    Accuracy Achieved: Reported accuracy on training and test sets using accuracy_score from scikit-learn.

Dataset

The dataset contains 208 samples and 60 features, each representing the energy of a sonar signal at a specific frequency. The target column R has two values:

    R: Rock

    M: Mine

Steps Performed

    Data Loading: Loaded using pandas from a CSV file.

    Exploratory Data Analysis (EDA): Shape, description, class distribution, and group statistics.

    Data Splitting: Train-test split with stratification to maintain class balance.

    Model Training: Logistic Regression model trained on the training set.

    Evaluation: Evaluated on both training and test sets using accuracy score.

    Prediction: Demonstrated with a manual input example.

Libraries Used 


    Numpy
    Pandas
    sk.learn
