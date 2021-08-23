# Credit Risk Analysis Challenge

## Overview
For this challenge I am applying different Artificial Intelligence methods of supervised learning to predict credit card risk. Oversampling, undersampling, SMOTE, clustercentroids, SMOTEEN are some algorithims I am using in this exercise. Balanced random forest classifier and Easy ensemble classifier will also be used to predict risk. Once the analysis is complete I am assesing the applied prediction methods - how accurate are they? Can they safely be used to make predictions for fraud? Let's find out!

## Results

### Naive Random Oversampling
- Balanced Accuracy Score:0.995
- Precision Score:1.0

### Smote Oversampling
- Balanced Accuracy Score:0.643 
- Precision Score:.99

### Undersampling
- Balanced Accuracy Score:0.643 
- Precision Score:.99

### Combination Sampling
- Balanced Accuracy Score:0.53
- Precision Score:.99

### Balanced Random Forest Classifier
- Balanced Accuracy Score: 0.79
- Precision Score:.99

### Easy Ensemble AdaBoost Classifier
- Balanced Accuracy Score: 0.93
- Precision Score:.99

## Summary
In conclusion, I believe more research needs to be done before deciding if these testing methods are accurate enough to predict credit card risk. Concerning the precision score, only one method has a precision score of 1, and all the others have a score of 99%. This means that for every 1 million people, there is room for reporting error up to 10,000 people.

I also have a lack of experience concerning which report numbers and percentages are acceptable for the credit card industry. Is a 99% precision score excellent, or is it unacceptable? If this were a real life situation, I would need to speak to a credit card fraud industry specialist in order to conclude what numbers are acceptable or not. The same goes for the balanced accuracy score. The closer the balanced accuracy score number is to 1 the better - but once again, what is an acceptable baseline number for this industry?

Besides speaking to an industy expert, I also recommend that more types of testing be incorporated into this process. Adding  sensitivity/recall analysis and calculating the F1/harmonic mean into the entire analysis will help form a more well rounded conclusion.



























