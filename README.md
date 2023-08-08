# -Diabetes-Prediction-Data-Mining-SJSU

****Data from NHANES 2013-14 is used for diabetes classification. The focus is on selecting smallest subset of features (10 out of 37) using "Feature Importance" techniques

* CatBoostClassifier
* XGBClassifier
* RandomForestClassifier
* ExtraTreesClassifier
* LogisticRegression
* DecisionTreeClassifier_RFE
* chi-squared
* ANOVA
Machine learning models:
* SVM
* Logistic Regression
*  KNN
*  Random Forest.

* Diabetes_Cleaned_Data.csv - 37 features from NHANES 2013-14 (demographics, lab, examination, questionnaire, diet) are handpicked based on domain knowledge that affect the Glycohemoglobin levels.

* Data_Mining_DaiabetesClassification.ipynb - After cleaning the data, pre-processing and normalizing the data, various feaure importance techniques are used to identify the 10 most important features. The machine learning models are trained with data before and after feature selection to draw conclusions.
