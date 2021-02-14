# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to evaluate credit card risk using 6 different models to determine which model is better at predicting credit risk. For each model, we first import our data, create the training and target variables, and then evaluate the models by resampling. 

## Results

- RandomOverSampler (oversample)
  - balance accuracy score = 0.6347321432168598
  - insert image
  
- SMOTE (oversample)
  - balanced accuracy score = 0.6473010865755344
  - insert image

- ClusterCentroids (undersample)
  - balanced accuracy score = 0.519685872100753
  - insert image

- SMOTEENN (over- & undersample)
  - balanced accuracy score = 0.519685872100753
  - insert image

- BalancedRandomForestClassifier (ensemble)
  - balanced accuracy score = 0.7877672625306695
  - insert image
  
- EasyEnsembleClassifier (ensemble)
  - balanced accuracy score = 0.925427358175101
  - insert image
  
## Summary
