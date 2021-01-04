# Credit-Card-Fraud-Detection

### Objective
The aim of this project is to predict fraudulent credit card transactions using machine learning models. 
The data set that you will be working on during this project was obtained from Kaggle. It contains thousands of individual transactions that took place over a course of two days and their respective labels.
Link of the dataset : https://www.kaggle.com/mlg-ulb/creditcardfraud


### Data Understanding
The data set includes credit card transactions made by European cardholders over a period of two days in September 2013. Out of a total of 2,84,807 transactions, 492 were fraudulent. This data set is highly unbalanced, with the positive class (frauds) accounting for just 0.172% of the total transactions. The data set has also been modified with Principal Component Analysis (PCA) to maintain confidentiality. Apart from ‘time’ and ‘amount’, all the other features (V1, V2, V3, up to V28) are the principal components obtained using PCA. The feature 'time' contains the seconds elapsed between the first transaction in the data set and the subsequent transactions. The feature 'amount' is the transaction amount. The feature 'class' represents class labelling, and it takes the value 1 in cases of fraud and 0 in others.


### Project Pipeline
1) Data Understanding
2) Exploratory data analytics (EDA)
3) Train/Test Split
4) Model-Building/Hyperparameter Tuning

### Model Evaluation
1) Accuracy – Correctly predicted labels
2) Sensitivity – Correctly predicted Yes
3) Specificity – Correctly predicted Nos
4) ROC Curve – TPR vs FPR.(The ROC curve is used to understand the strength of the model by evaluating the performance of the model at all the classification thresholds.)


#### Note :
The objective is to build a model having a high recall in order to detect actual fraudulent transactions to save banks from high-value fraudulent transactions.
