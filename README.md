# Prediction on Occurence of Heart Stroke

## Repository Description

This repository is submitted to Nanyang Technological University as part of a graded assignment for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on Occurence of Heart Stroke.

<img width="430" alt="2023-04-14 (42)" src="https://user-images.githubusercontent.com/96024308/231941543-67a53f90-0e1d-4c4a-a4f9-3667efdbc91e.png">

## Contributors
School of Computer Science and Engineering, NTU Singapore
AY2022/23 SC1015 Y127 Group 1

NG YAO HONG NGYA0021@E.NTU.EDU.SG (Data Preparation, Exploratory Data Analysis, Machine Learning)    
TAN KAI JIE DARYL TANK0301@E.NTU.EDU.SG (Machine Learning)    
LAU ETHAN LAUE0006@E.NTU.EDU.SG (Machine Learning)    

## Folders
### Datasets Folder
* heart_disease_data: original dataset from kaggle
* heart_dis_cln: original dataset cleaned with 17 columns, no NULL, removed outliers
* heart_dis_cln_ohe: heart_dis_cln with categorical variables being one hot encoded

## Jupyter Notebook Folder
For detailed walkthrough, please view the source code in order from:

1. Complete Data Cleaning & Visualization
2. Data Visualization via Tableau
3. Machine Learning 1 (DecisionTreeClassifier, RandomForestClassifier)
4. Machine Learning 2 (BalancedBaggingClassifier, BalancedRandomForestClassifier)
5. Machine Learning 3 (LogisticRegression)

## Others Folder
* SC1015 Mini Project - Presentation: The slides provide a quick summary of our project.

## Problem Definition
* How do different factors affect occurence of Heart Stroke?
* Which model would be the best to predict occurence of Heart Stroke?

## Models Used
1. OneHotEncoder
2. Grid Search Cross-Validation
3. Decision Tree Classifier
4. Random Forest Classifier
5. Balanced Bagging Classifier
6. Balanced Random Forest Classifier
7. Logistic Regression

## Conclusion
* No linear relationship between the numerical variables and Heart Stroke.

## What did we learn from this project?
* Scikit-learn:
    * Regression: Logistic Regression
    * Classification: Decision Tree Classifier, Random Forest Classifier
* ImbLearn:
    * Classification: Balanced Bagging Classifier, Balanced Random Forest Classifier
* Others:
    * Utility models: Simple Imputer, Standard Scalar, One Hot Encoder, Resample, Grid Search CV, Eli5
* Tableau:
    * Visualization: Tableau desktop, Tableau public
* Collaborating on Github
