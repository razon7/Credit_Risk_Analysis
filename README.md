# Credit_Risk_Analysis
Credit Risk Analysis done using Supervised Machine Learning
In this project, we use Python to build and evaluate several machine learning models to predict credit risk.

Following steps were used
- oversample the data using the RandomOverSampler and SMOTE algorithms.
- Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
- Compare two machine learning models that reduce bias, BalancedRandomForestClassifier and   EasyEnsembleClassifier.

Results:
Naive Random Oversampling results: 
Our balanced accuracy test it 65%,
The precision for the high_risk has a very low positivity at 1% and the recall is 72%.

SMOTE oversampling results: 
The accuracy score is 66.2%, the precision for the high_risk loans has a low positvity again at 1% and recall is 69% overall smote.


Undersampling results: 
Balanced accuracy score is 66.2% overall, the precision is at 99% and the recall is 40% undersampling.


Combination(over and undersampling) results:
Balanced accuracy score is 54.4% the precision is 99% and the recall is 57% overall combination.



Balanced Random Forest Classifier results: 
The accuracy score is 78.7% the precision is 99% and the recall is 88% random forest.

