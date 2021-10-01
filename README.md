# Breast_cancer_prediction

## Problem statment
**Classification problem, to classify the Breast cancer type based on given features**

## Approach
- Using ttest statistical technique we select the features(if feature related to target)
- To avoid multicollinearity among independent features we used **Principle Component Analysis(PCA)** , here we took those many principle components which explain 99% variation of the data
- With the selected Principle components we build the claassification model

## Model building
- We tried with<br>
a) Logistic regression<br>
b)KNN classifier<br>
c)Decision tree<br>
d)Random forest<br>
e)Adaboostclassifier<br>
f)gradient boost classifier<br>
g)xgboost classifier<br>
h) Lighgbm<br>
i)catboost<br>

These all models we fitted and check for the accuracy, based on accuracy performance we select Logistic regression as the final model

## Final model(Logistic Regression) performance

- Confusion matrix

![image](https://github.com/Basavaraj100/Breast_cancer_prediction/blob/main/images/confussion_matrix.PNG)

- Classification report

![image](https://github.com/Basavaraj100/Breast_cancer_prediction/blob/main/images/classification_report.PNG)
