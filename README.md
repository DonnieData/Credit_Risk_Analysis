# Credit_Risk_Analysis
Using Resampling Models and Classifiers to Predict Credit Risk  

## Overview
The purpose of this analysis is to test how machine models are able to assess credit card risk. Included models are RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier.


## Results 

### Random Oversampling <br>
![randomover](https://github.com/DonnieData/Credit_Risk_Analysis/blob/main/img/randomoversampling%20.png) <br>
Balanced Accuracy Score: 0.6400925019439107 <br>
high risk performance: 
- precision is very low (0.0.1)
- recall is good (0.61)

low risk performance:
- precision is perfect (1.00)
- recall is good (0.67)

### SMOTE <br>
![smote](https://github.com/DonnieData/Credit_Risk_Analysis/blob/main/img/SMOTE.png) <br>
Balanced Accuracy Score: 0.6195656115160086 <br>
high risk performance: 
- precision is very low (0.0.1)
- recall is good (0.60)

low risk performance:
- precision is perfect (1.00)
- recall is good (0.64)

### Cluster Centroid 
![undersampling](https://github.com/DonnieData/Credit_Risk_Analysis/blob/main/img/undersampling%20.png) <br>
Balanced Accuracy Score: 0.6195656115160086 <br>
high risk performance: 
- precision is very low(0.01)
- recall is fairly good (0.61)

low risk performance:
- precision is perfect (1.00)
- recall is low (0.42)

### Smoteen <br>
![smoteenn](https://github.com/DonnieData/Credit_Risk_Analysis/blob/main/img/SMOTEENN.png) <br>
Balanced Accuracy Score: 0.6400726134353378
high risk performance: 
- precision is low (0.01)
- recall is great (0.70)

low risk performance:
- precision is perfect (1.00)
- recall is fair (0.57?

### Balanced Random Forest Classifier <br>
![random forest](https://github.com/DonnieData/Credit_Risk_Analysis/blob/main/img/random%20forest.png) <br>
Balanced Accuracy Score: 0.7877672625306695 <br>
high risk performance: 
- precision is low (0.04)
- recall is good (0.67)

low risk performance:
- precision is perfect (1.00)
- recall is great (0.91)


### Easy Ensemble Classifier <br>
![easy ensemble](https://github.com/DonnieData/Credit_Risk_Analysis/blob/main/img/Easy%20Ensemble.png) <br>
Balanced Accuracy Score: 0.925427358175101 <br>
high risk performance: 
- precision is low (0.09)
- recall is great (0.92)

low risk performance:
- precision is perfect (1.00)
- recall is great (0.94)

## Summary 
The F1 score can be characterized as a single summary statistic of precision and sensitivity(recall). Given this, the F1 score is a great measurement to gauge model performance. Based on F1 scores the best forming model is the Easy Ensemble Classifier with an average F1 score of 0.97. While the worst performing is Cluster Centroid with an average F1 score of 0.59. 

Based on performance the Easy Ensemble Classifier model is greatly recommended for assessing credit risk. 


