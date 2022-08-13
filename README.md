# Credit_Risk_Analysis
Machine Learning and Credit Risk
## Overview of the analysis:
In this challenge we are asked to use different methods to test and evaluate the data. Using different models some meathods such as BalancedRandomForestClassifier, EasyEnsembleClassifier, and SMOTE algorithms to test the data.
## Results:
### Naive Random Oversampling:
<img width="856" alt="Screen Shot 2022-08-13 at 1 33 22 PM" src="https://user-images.githubusercontent.com/99035696/184504726-8287631f-4fca-41a0-8444-d57fee0c2f47.png">
balanced accuracy: 0.6876489392618425, 
precision: The precision is low for High-risk and is high for Low-risk., 
recall: High risk = .57 , Low risk = .69

### SMOTE Oversampling:
<img width="856" alt="Screen Shot 2022-08-13 at 1 39 11 PM" src="https://user-images.githubusercontent.com/99035696/184504877-018485e6-2cb8-4a84-bb0f-0ea1e857b422.png">
balanced accuracy: 0.6314677834584286, 
precision: The precision is low for High-risk and is high for Low-risk., 
recall:High risk = .57 , Low risk = .69

### Undersampling:
<img width="856" alt="Screen Shot 2022-08-13 at 2 54 26 PM" src="https://user-images.githubusercontent.com/99035696/184507098-a92bb426-1f52-4ea8-852d-a05270c98f76.png">
balanced accuracy:0.6314677834584286, 
precision: The precision is low for High-risk and is high for Low-risk., 
recall:High risk = .57 , Low risk = .46

### Combination (Under and Over) Sampling:
<img width="856" alt="Screen Shot 2022-08-13 at 2 57 41 PM" src="https://user-images.githubusercontent.com/99035696/184507184-83fd3930-43c5-44cf-b289-62d24a6e06e0.png">
balanced accuracy: 0.516880798997627, 
precision: The precision is low  for High-risk and is high for Low-risk., 
recall:High risk = .70 , Low risk = .58

### Balanced Random Forest Classifier:
<img width="856" alt="Screen Shot 2022-08-13 at 3 01 21 PM" src="https://user-images.githubusercontent.com/99035696/184507327-7861dc00-962e-4593-aa88-2c2dcf3c1ced.png">
balanced accuracy: 0.7877672625306695, 
precision: The precision is low for High-risk and is high for Low-risk.,
recall:High risk = .67 , Low risk = .91

### Easy Ensemble AdaBoost Classifier:
<img width="856" alt="Screen Shot 2022-08-13 at 3 08 20 PM" src="https://user-images.githubusercontent.com/99035696/184507710-db06b1f8-c656-4d5a-b42b-415c6e2c68be.png">
balanced accuracy: 0.925427358175101,
precision: The precision is low for High-risk and is high for Low-risk.,
recall:High risk = .91 , Low risk = .94 

## Summary: 
From the results from all we can see that the precisiom for high-risk is low and for low-risk is high. The balanced accuracy they seem to all be over .5 being closer to 1 then 0. The recall for high risk are all over .5 with the average around .67. The low risk being over .4 and the average .72. The best machine learning to choose would be Easy Ensemble AdaBoost Classifier. This is because they have the highest recall value being the closest to 1. 

