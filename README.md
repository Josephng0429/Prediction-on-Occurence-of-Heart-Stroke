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
* heart_dis_cln_ohe_up: heart_dis_cln_ohe after resampling (upsampling) the sample size of those with the occurrence of HEART_STROKE to the size of those without the occurrence of HEART_STROKE.

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
* The data indicates that men and people with lower levels of education are at a higher risk for experiencing positive heart strokes. As such, it is crucial to promote health education and awareness, particularly among males, in order to mitigate the risk of heart stroke.
* AFter exploring various ML models and tools to utilise them, we compared their test accuracies in predicting the response variable as well as the balance of accuracy between the various categories. We eventually came to a conclusion that BalancedBaggingClassifier is the best model as it has a more evenly distributed balance of accuracy as well as the highest numerical accuracy value out of all the models explored.
* This raises the possibility that the BalancedBaggingClassifier can perhaps be used in medical industry to predict the occurrence of Heart Stroke within a patient, given the other variables.

## What did we learn from this project?
* Scikit-learn:
    * Regression: Logistic Regression
    * Classification: Decision Tree Classifier, Random Forest Classifier
* ImbLearn:
    * Classification: Balanced Bagging Classifier, Balanced Random Forest Classifier
* Others:
    * Utility models: One Hot Encoder, Resample, Grid Search CV, Eli5
* Tableau:
    * Visualization: Tableau desktop, Tableau public
* Collaborating on Github

## References
* The National Institute for Occupational Safety and Health (NIOSH). (2022, May 13). Heat stress related illness. Centers for Disease Control and Prevention.  https://www.cdc.gov/niosh/topics/heatstress/heatrelillness.html#:~:text=Heat%20Stroke,-Heat%20stroke%20is&amp;text=It%20occurs%20when%20the%20body,within%2010%20to%2015%20minutes.    
* World Health Organization. Cardiovascular diseases. World Health Organization. https://www.who.int/health-topics/cardiovascular-diseases 
* Pedregosa et al. (2011). Scikit-learn: Machine Learning in Python. JMLR 12, pp. 2825-2830.‌​   
* What is Cross Validation in Machine Learning? Types of Cross Validation. (2020, September 24). GreatLearning Blog: Free Resources What Matters to Shape Your Career! https://www.mygreatlearning.com/blog/cross-validation/ ​   
* Imbalanced Data | Data Preparation and Feature Engineering for Machine Learning | Google Developers. (2021). Google Developers. https://developers.google.com/machine-learning/data-prep/construct/sampling-splitting/imbalanced-data ​   
* Bento, C. (2021, June 28). Decision Tree Classifier explained in real-life: picking a vacation destination. Medium; Towards Data Science. https://towardsdatascience.com/decision-tree-classifier-explained-in-real-life-picking-a-vacation-destination-6226b2b60575 ​      
* Yadav, D. (2019, December 6). Categorical encoding using Label-Encoding and One-Hot-Encoder. Medium; Towards Data Science. https://towardsdatascience.com/categorical-encoding-using-label-encoding-and-one-hot-encoder-911ef77fb5bd ​   
* Lemaître, G., Nogueira, F., & Aridas, C. K. (2017). Imbalanced-learn: A Python Toolbox to Tackle the Curse of Imbalanced Datasets in Machine Learning. Journal of Machine Learning Research, 18(17), 1–5. https://jmlr.org/papers/v18/16-365.html ​    
* IBM Cloud Education. (2021, May 11). What is Bagging? Ibm.com. https://www.ibm.com/cloud/learn/bagging#:~:text=Bagging%2C%20also%20known%20as%20bootstrap,be%20chosen%20more%20than%20once ​   

