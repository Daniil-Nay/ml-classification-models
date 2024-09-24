# Notebooks
### 1-c-Credit_scoring (Give Me Some Credit)
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


### 2-с-Dogs_vs_Cats 
[ENG] This notebook contains a simple convolutional neural network (CNN) designed to classify images of dogs and cats.  
The model leverages multiple convolutional layers to extract features from the input images,   
followed by batch normalization and pooling layers to enhance stability and reduce overfitting.   
Dropout is applied to prevent overfitting during training. The architecture includes a flattening layer and dense  
layers to output the final classification results.  
As of epoch 19 out of 30 (with a preliminary stop), the model achieved a training accuracy of 88.73% and a validation accuracy of 90.30%.
