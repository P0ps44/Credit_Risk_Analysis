# Credit_Risk_Analysis

## Overview of the analysis:

Credit risk is an inherently unbalanced classification problem and this analysis will use machine learning and a number of libraries to build and evaluate models using resampling. The main program I used was jupyter notebooks and the sklearn libraries. The data will be a credit card credit dataset from LendingClub.

## Results:

### Naive Random Oversampling
* Balanced Accuracy Score: 0.6400737711750595

* Precision Score: high_risk -> 0.01 low_risk -> 1.00 

* Recall Score: Average/Total -> 0.74

### SMOTE Oversampling
* Balanced Accuracy Score: 0.6611371087997481

* Precision Score: high_risk -> 0.01 low_risk -> 1.00 

* Recall Score: Average/Total -> 0.69

### Undersampling
* Balanced Accuracy Score: 0.5442369453268994

* Precision Score: high_risk -> 0.01 low_risk -> 1.00 

* Recall Score: Average/Total -> 0.40 

### Combination (Over and Under) Sampling
* Balanced Accuracy Score: 0.6408034366345896

* Precision Score: high_risk -> 0.01 low_risk -> 1.00 

* Recall Score: Average/Total -> 0.58

### Balanced Random Forest Classifier
* Balanced Accuracy Score: 0.7885466545953005

* Precision Score: high_risk -> 0.03 low_risk -> 1.00 

* Recall Score: Average/Total -> 0.87

### Easy Ensemble AdaBoost Classifier
* Balanced Accuracy Score: 0.9316600714093861

* Precision Score: high_risk -> 0.09 low_risk -> 1.00 

* Recall Score: Average/Total -> .094

## Summary:
After using all six models, the "Easy Ensemble AdaBoost Classifier" had the best results with a balanced accuarcy score of 93%. The model also have a .009 high risk precison score which was better than any other model. The second closest high risk precision score was using the Balanced Random Forest Classifier at .003.
Lastly, easy ensemble model recall score was at an average of .094, which was the best compared to the other models. So with this analysis, I would recommend using the Easy Ensemble AdaBoost Classifier model. 

