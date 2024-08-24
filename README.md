# Notebooks
### 1-Credit_scoring (Give Me Some Credit)
[ENG] The goal achieved in the notebook was to build a model that predicts   
the probability of a person experiencing financial distress within the next two years.  
The missing data was imputed, and the features were scaled before fitting several models:
1. Logistic Regression
2. XGBClassifier
3. DecisionTreeClassifier
4. RandomForestClassifier
5. AdaBoostClassifier
6. CatBoostClassifier

| Model               | AUC - Validation |
|---------------------|------------------|
| Logistic Regression | 0.7057           |
| XGBClassifier       | 0.7521           |
| DecisionTree        | 0.7161           |
| RandomForest        | 0.8299           |
| AdaBoost            | 0.8282           |
| CatBoost            | 0.8370           |
From the results, it is evident that the CatBoost classifier performed quite well compared to the other models.  
However, there are still opportunities for improvement by further tuning the hyperparameters. 
