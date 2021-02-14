# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to evaluate credit card risk using 6 different models to determine which model is better at predicting credit risk. For each model, we first import our data, create the training and target variables, and then evaluate the models by resampling. 

## Results

- RandomOverSampler (oversample)
  - balance accuracy score = 0.6347321432168598
  - precision & recall score:
  
  ![randomoversampler](https://user-images.githubusercontent.com/71397190/107890426-b269b800-6ede-11eb-932e-6dd283c5d307.PNG)
  
- SMOTE (oversample)
  - balanced accuracy score = 0.6473010865755344
   - precision & recall score:
   
   ![smote](https://user-images.githubusercontent.com/71397190/107890427-b3024e80-6ede-11eb-8827-3559d53ec5c1.PNG)

- ClusterCentroids (undersample)
  - balanced accuracy score = 0.5145088251527934
   - precision & recall score: 
   
   ![clustercentroids](https://user-images.githubusercontent.com/71397190/107891232-d4fdd000-6ee2-11eb-9bc8-4f0568646733.PNG)

- SMOTEENN (over- & undersample)
  - balanced accuracy score = 0.6375825406609699
  - precision & recall score:
  
  ![smoteenn](https://user-images.githubusercontent.com/71397190/107891230-d3cca300-6ee2-11eb-9d32-72e0113db8f1.PNG)

- BalancedRandomForestClassifier (ensemble)
  - balanced accuracy score = 0.7877672625306695
  - precision & recall score: 
  
  ![brfc](https://user-images.githubusercontent.com/71397190/107890423-b269b800-6ede-11eb-9e3f-e7041973a009.PNG)
  
- EasyEnsembleClassifier (ensemble)
  - balanced accuracy score = 0.925427358175101
  - precision & recall score:
  
  ![eec](https://user-images.githubusercontent.com/71397190/107890425-b269b800-6ede-11eb-9041-2fecd066912c.PNG)
  
## Summary
The balanced accuracy score is a metric used to evaluate how good a binary classifier is. It is the average of sensitivity (true positive rate, or recall) and specificity (true negative rate). The closer to 1, the better a classifier. The F1 score, or harmonic mean, is a weighted average of precision and recall. The closer to 1, the better the score. Precision is the proportion of positive identifications that were actually correct. Recall is the proportion of positive identifications that were actually correct. 

The EasyEnsembleClassifier model has the highest accuracy score, followed by the BalancedRandomForestClassifier model, the oversampling models, then SMOTEENN and finally ClusterCentroids. The EasyEnsembleClassifier model also has the highest F1 score, with ClusterCentroids at the lowest again.

### Recommendation
Of the 6 models evaluated, the EasyEnsembleClassifier model would be our recommendation for this particular dataset due to its high accuracy and F1 scores. 



