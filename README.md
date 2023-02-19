# Sampling

## Problem Statement:
Given an unbalanced dataset:  
1. Convert this dataset into a balanced one
2. Apply 5 different sampling techniques
3. Apply these sampling techniques on 5 different ML models


## Approach to solve the given problem:  
1. The given dataset is almost 98% imbalanced. Hence, SMOTE technique which stands for Synthetic Minority Over-sampling Technique is used to balance the given dataset.  

2. Five different techniques are used for sampling. These are:  
    1. Random Sampling
    2. Systematic Sampling
    3. Stratified Sampling
    4. Clustered Sampling
    5. Snowball Sampling

3. Five different ML models are used over these five sampling techniques:  
    1. Random Forest Classifier
    2. Bagging Classifier
    3. Decision Tree Classifier
    4. Logistic Regression
    5. KNN

## Accuracy Results
ML Model   | Simple Random Sampling | Stratified Sampling|Cluster Sampling|Systematic Sampling|Snowball Sampling|
------------- | -----------------------|--------------------|----------------|-----------------|-------------------|
Random Forest  | 0.9841|0.9940|0.9980|0.9880|0.9722|
Bagging | 0.9662|0.9821|0.9841|0.9682|0.9642|
Decision Tree | 0.9087|0.9047|0.9007|0.8988|0.9087|
Logistic Regression | 0.9107|0.9325|0.9305|0.9107|0.9107|
KNN | 0.7380|0.8234|0.7996|0.7738|0.7380|


Hence, Random Forest Classifier is the best model among all.  
Random Forest Classifier gives the highest accuracy for Cluster Sampling.


