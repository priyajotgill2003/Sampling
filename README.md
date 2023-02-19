# Sampling


This repository contains solution to sampling assignment for UCS654.

List of tasks:
 Download the dataset
 Convert it into balanced dataset
 Create 5 samples
 Apply 5 different sampling techniques on five different ML models
Discussion:
The dataset used is highly imbalanced. The number of samples in the minority class is only 1.167% of the total number of samples. I used the SMOTE algorithm to oversample the minority class.

For sampling, I have used the following different techniques:

Random Sampling
Stratified Sampling
Systematic Sampling
Smote Sampling
Convience Sampling

All five samples were then trained on the following ML models:
1.Logistic Regression
2.Gradient Boosting Clasifier
3.Naive Bayes Classifier
4.Decision Tree
5.Random Forest Classifier

Performace Evaluation:
The accuracy of these models on test set is as follows:

