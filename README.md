---
title: 441 Kaggle Competition
---

## Stacking.ipynb
Stacks the best models for prediction using 5-fold cross validation and Logistic regression to combine predicted probabilitiies.

## SubmissionNeuralNet.ipynb
Creates a submission file for the best neural network.

## SimpleImputation.ipynb
Processes the data by seperating numerical and categorical features. <br />
Imputes numerical features using the mean and scales features using min-max. <br />
Imputes categorical features by treating NA as a seperate category and one hot encodes features. <br />
Tests parameters for neural network, KNN, and Random Forests.

## KNNImputation.ipynb
Processes the data by seperating numerical and categorical features. <br />
Imputes numerical features using KNN and scales features using min-max. <br />
Imputes categorical features by treating NA as a seperate category and one hot encodes features. <br />
Tests parameters for neural network.

## NaiveImputation.ipynb
Does not differentiate between numerical and categorical features when processing the data. <br />
Imputes features using mean and scales features using min-max. <br />
Tests parameters for neural network.

## Years.ipynb
Seperates data by year to be modeled individualy.
Does not differentiate between numerical and categorical features when processing the data. <br />
Imputes features using mean and scales features using min-max. <br />
Tests parameters for neural network.

codebook-reworked.csv - csv containing codebook and added feature to label numerical and categorical data. <br />
train.csv - training data. <br />
test.csv - provided test set.
