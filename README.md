# Sampling


This repository contains solution to sampling assignment for UCS654.

List of tasks:

 - Download the [dataset](https://github.com/priyajotgill2003/Sampling/blob/main/Creditcard_data.csv)
 
 - Convert it into balanced dataset
 
 - Create 5 samples
 
 - Apply 5 different sampling techniques on five different ML models
 
## Discussion:

The dataset used is highly imbalanced. The number of samples in the minority class is only 1.167% of the total number of samples. I used the SMOTE algorithm to oversample the minority class.


For sampling, I have used the following different techniques:

1. Random Sampling
2. Stratified Sampling
3. Systematic Sampling
4. Smote Sampling
5. Convience Sampling

All five samples were then trained on the following ML models:

1. Logistic Regression
2. Gradient Boosting Clasifier
3. Naive Bayes Classifier
4. Decision Tree
5. Random Forest Classifier

## Performace Evaluation:

The accuracy of these models on test set is as follows:

<img width="767" alt="image" src="https://user-images.githubusercontent.com/72308930/219965320-b8c5add3-6c2e-4425-8e12-55b1e0f34d58.png">

## Conclusion:

Clearly, Random Forest Classifier consistently yields the highest accuracy across all sampling techniques.
