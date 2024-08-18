Liver Health Classification Model
This repository contains a predictive model for classifying the risk of liver disease based on various health indicators. The model is designed to help identify individuals who may be at a higher risk of developing liver disease, using machine learning techniques.

Overview-
The Liver Health Classification model predicts the likelihood of liver disease by analyzing key health factors such as age, BMI, genetic predisposition, and lifestyle choices like smoking and alcohol consumption. This model can be used to assist healthcare providers in early diagnosis and intervention.

Features-
The dataset used in this project includes the following features:

Age: The age of the individual.
Gender: The gender of the individual (0 for male, 1 for female).
BMI: Body Mass Index, a measure of body fat based on height and weight.
AlcoholConsumption: Amount of alcohol consumed.
Smoking: Whether the individual smokes (0 for non-smoker, 1 for smoker).
GeneticRisk: Genetic predisposition to liver disease (0 for low risk, 1 for high risk).
PhysicalActivity: Level of physical activity.
Diabetes: Whether the individual has diabetes (0 for no, 1 for yes).
Hypertension: Whether the individual has hypertension (0 for no, 1 for yes).
LiverFunctionTest: A measure of liver function.
Diagnosis: The target variable indicating whether the individual is diagnosed with liver disease (0 for no, 1 for yes).

Model Performance-
The model was trained and evaluated using several machine learning algorithms. Below are the accuracies achieved by each model:

Model	Accuracy-

Logistic Regression:	0.8088
Decision Tree:	0.8529
Random Forest:	0.9029
Gradient Boosting:	0.9088
Support Vector Classifier:	0.7735
K-Nearest Neighbors:	0.7735
Naive Bayes:	0.8029
CatBoost:	0.9147
XGBoost:	0.8912
LightGBM:	0.8853
The CatBoost model achieved the highest accuracy, making it the best model for this classification task.

Tools Used-

Programming Language: Python
Libraries:
Pandas
Scikit-learn
CatBoost
XGBoost
LightGBM
Matplotlib (for visualizations)
