# Credit_Risk_Analysis

## Project Overview
The goal of this project is to employ machine learning with the aim of predicting credit risk. The following discusses whether the several models run should be used to predict credit risk. 

## Results
* Although the recall and balanced accuracy scores for first four models below (Naive Random Oversampling, SMOTE Oversampling, Undersampling, Combination Sampling) show promise, the extremes of the precision scores suggest that another approach may be needed to account for an imbalanced data set.

### Naive Random Oversampling
![Naive_Random_Oversampling](/Naive_Random_Oversampling.png).

### SMOTE Oversampling
![SMOTE_Oversampling](/SMOTE_Oversampling.png).

### Undersampling
![Undersampling](/Undersampling.png).

### Combination Sampling
![Combination_Sampling](/Combination_Sampling.png).

* The ensemble classifiers (Easy, Balanced Random Forest) seem to perform better than the previous sampling approaches in precision, sensitivity, and F1 terms (sometimes substantially better), suggesting a more random approach may better fit the imbalanced data set.

### Easy Ensemble
![Easy_Ensemble_AdaBoost](/Easy_Ensemble_AdaBoost.png).

### Balanced Random Forest
![Balanced_Random_Forest](/Balanced_Random_Forest.png).

## Summary
*Although all of the models has promise in one aspect, the model I would feel comfortable recommending going forward - with perhaps one more round of testing to confirm -  would be Easy Ensemble AdaBoost Classifier. The results for this model have a relatively high balanced accuracy score plus the more ideal balance of accurate precision and sensitivity results.
