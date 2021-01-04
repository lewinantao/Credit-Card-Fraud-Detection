# Credit-Card-Fraud-Detection

### Objective
The aim of this project is to predict fraudulent credit card transactions using machine learning models. 
The data set that you will be working on during this project was obtained from Kaggle. It contains thousands of individual transactions that took place over a course of two days and their respective labels.
Link of the dataset : https://www.kaggle.com/mlg-ulb/creditcardfraud


### Project Pipeline
1) Data Understanding
2) Exploratory data analytics (EDA)
3) Train/Test Split
4) Model-Building/Hyperparameter Tuning


### Data Understanding
1) The data set includes credit card transactions made by European cardholders over a period of two days in September 2013. 
2) Out of a total of 2,84,807 transactions, 492 were fraudulent. Fraudulent class percentage : 99.827% and Non-Fraudukent class percetage : 0.172%
3) The data set is highly unbalanced.Also all the columns have been modified with Principal Component Analysis (PCA) to maintain confidentiality apart from ‘time’ and ‘amount’ columns.
4) The feature 'class' represents class labelling, and it takes the value 1 in cases of fraud and 0 in others.


### EDA and Class Imbalance
The data shows a high class imbalance. Over 2,00,000 cases are mapped to 0, but hardly 500 cases are mapped to 1.
Methods to mitigate minority class problem:-
1) Undersampling - Selecting fewer data points from the majority class so the fraud and non-fraud data points are somewhat balanced.
2) Oversampling - Assigning weights to randomly chosen data points from the minority class(i.e duplicating the data points from the minority class)
3) Synthetic Minority Over-Sampling Technique (SMOTE) - Generating new data points which lie vectorically between 2 data points that belong to minority class.
4) ADAptive SYNthetic (ADASYN) - Similar to SMOTE except that the data points are generated to the less/low density occurance of minority class.


### Model Building and Training
1) This is a classification based machine learning problem.
2) The below are the models build in this project
- KNN 
- Decision Tree 
- Random Forest 
- XGBoost
3) The above models are build on both balanced and inbalanced data to understand impact of class imbalance.
4) The model is evaluated with a range of  hyper parameter tuning  using grid search CV and k-fold cross-validation.


### Model Evaluation
1) Accuracy – Correctly predicted labels
2) Sensitivity – Correctly predicted Yes
3) Specificity – Correctly predicted Nos
4) ROC Curve – TPR vs FPR.(The ROC curve is used to understand the strength of the model by evaluating the performance of the model at all the classification thresholds.)


#### Note :
The objective is to build a model having a high recall in order to detect actual fraudulent transactions to save banks from high-value fraudulent transactions.
