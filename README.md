# Ensemble-classifier
codes related to machine learning

The folder consists of the 3 files among which lab4_train.csv is the training data used to train the model
lab4_test.csv is used for checking the performance of the trained models.

While training the individual models different hyper parameters have been used and tuned to get better approach.

This code contains 7 different individual models such as 
Neural Network (NN), KNN, Logistic Regression (LR), Naive Bayes (NB), Decision Tree (DT), 
Random Forest (RF) and AdaBoost.M1 with decision stumps as base classifiers

Each models accuracy on test data and confusion matrix has been printed.

Then Ensemble model (weighted and unweighted) has been desgined over 5 and 7 models.
5 models include : Neural Network (NN), KNN, Logistic Regression (LR), Naive Bayes (NB), Decision Tree (DT)
7 models include all the mentioned model.

A majority vote method has been used to estimate the prediction of the ensemble classifier.
