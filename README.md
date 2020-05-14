# Diabetes-Diagnostic-Prediction

Use supervised machine learning models to predict if patient have diabetes or not with diagnostic measurements. 

Data Source: [**Kaggle**](https://www.kaggle.com/uciml/pima-indians-diabetes-database)

Prediction Method: Logistic Regression, SVM, Random Forest.

Model Evaluation: 
In this classification task where we would like to correctly predict the result of diabete diagnostic, the result of false negative is more severe than false positives because informing patients of no disease can result in delayed medical treatment and damage their health. Thus, we should give more emphasis to the metrics on the false negative rate, or the recall which is the proportion of correctly identified positive out of all actual positives. Precision here indicates the proportion of correctly predicted positive observations out of all predicted psitive indentifications which is of less importance than the recall because higher recall lead to more severe outcome on the patients. Based on the tuned model of Logistic Regression, Random Forest and Support Vector Machine, we can clearly see that the SVC model performace is better. Thus, we can use this trained model to predict the diabetes diagnostic in the future.



