# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to evaluate credit card risk using 6 different models to determine which model is better at predicting credit risk. For each model, we first import our data, create the training and target variables, and then evaluate the models by resampling. 

## Results

- RandomOverSampler (oversample)
  - balance accuracy score = 0.6347321432168598
  - ![randomoversampler](https://user-images.githubusercontent.com/71397190/107890426-b269b800-6ede-11eb-932e-6dd283c5d307.PNG)
  
- SMOTE (oversample)
  - balanced accuracy score = 0.6473010865755344
  - ![smote](https://user-images.githubusercontent.com/71397190/107890427-b3024e80-6ede-11eb-8827-3559d53ec5c1.PNG)

- ClusterCentroids (undersample)
  - balanced accuracy score = 0.519685872100753
  - ![clustercentroids](https://user-images.githubusercontent.com/71397190/107890424-b269b800-6ede-11eb-84bf-90051c158803.PNG)

- SMOTEENN (over- & undersample)
  - balanced accuracy score = 0.519685872100753
  - ![smoteenn](https://user-images.githubusercontent.com/71397190/107890428-b3024e80-6ede-11eb-9261-58baacab7417.PNG)

- BalancedRandomForestClassifier (ensemble)
  - balanced accuracy score = 0.7877672625306695
  - ![brfc](https://user-images.githubusercontent.com/71397190/107890423-b269b800-6ede-11eb-9e3f-e7041973a009.PNG)
  
- EasyEnsembleClassifier (ensemble)
  - balanced accuracy score = 0.925427358175101
  - ![eec](https://user-images.githubusercontent.com/71397190/107890425-b269b800-6ede-11eb-9041-2fecd066912c.PNG)
  
## Summary
