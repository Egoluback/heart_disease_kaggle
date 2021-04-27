# heart_disease_kaggle
A model classifying whether a person has heart problems <br />
Data: https://www.kaggle.com/ronitf/heart-disease-uci <br />
The general model is a catboost classifier. It contains 6 regression and 7 categorical features. <br />
Categorial features were encoded with one-hot-encoding method; <code>age</code> feature was divided on <code>age_40</code>, <code>age_50</code>, <code>age_60</code> and <code>age_70</code>. <br />
Also there is k-fold cross validation and grid search to find best hyperparameters. <br />
Result - 0.92(ROC_AUC). <br />
Also was made a SHAP explanation - you can watch and see, how model features influence on result.
