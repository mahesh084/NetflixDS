Netflix Data Classification
This project implements a binary classification model using a dataset related to Netflix. The goal is to predict the type of content based on various features using logistic regression.
The project includes data preprocessing steps like handling class imbalance, scaling features, and evaluating the model's performance.

Project Overview
The purpose of this project is to create a logistic regression model that predicts whether a Netflix show is of type 0 or 1. The model addresses issues like class imbalance and scales the features for effective learning. 
The project also evaluates the model's precision, recall, and F1-score.
Dataset
Netflix1.csv: contain the information about the Movie, Type of Movie, Date, Director etc. 


Class Imbalance Handling:The dataset is highly imbalanced, with the majority class having significantly more samples than the minority class.
To address this, we upsample the minority class using the resample function from scikit-learn.
Feature Scaling:We apply StandardScaler to normalize the feature values to ensure all features are on the same scale for the logistic regression model.
Train-Test Split:The dataset is split into training and test sets using an 80-20 split.

Evaluation
We evaluate the model using precision, recall, and F1-score to assess its performance, especially in imbalanced datasets.
