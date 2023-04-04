# Credit Risk Analysis
This project focuses on using machine learning techniques to predict credit risk using imbalanced data. The credit card credit dataset from LendingClub, a peer-to-peer lending services company, is used for this analysis. Resampling techniques such as RandomOverSampler, SMOTE, ClusterCentroids, and SMOTEENN are employed, as well as ensemble classifiers such as BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Project Structure
## The project repository "Credit_Risk_Analysis" contains the following files:

* credit_risk_resampling.ipynb: Jupyter notebook containing the analysis and implementation of resampling techniques to predict credit risk.
* credit_risk_ensemble.ipynb: Jupyter notebook containing the analysis and implementation of ensemble classifiers to predict credit risk.
* README.md:  (this file) providing documentation and instructions for the credit risk analysis.
* Other necessary files and folders for the analysis.
## Deliverable 1: Use Resampling Models to Predict Credit Risk

#### In the credit_risk_resampling.ipynb notebook, the following steps are performed:

1. Data preprocessing: The training variables are created by converting the string values into numerical ones using the get_dummies() method. The target variables are also created.
2. Checking the balance of the target variables: The count of the target classes is visualized to check for class imbalance.
3.  Resampling techniques: RandomOverSampler, SMOTE, and ClusterCentroids algorithms are used to resample the training data.
4.  Model evaluation: LogisticRegression classifier is used to make predictions and evaluate the model's performance for each resampling technique.
5.  Model performance metrics: The accuracy score, confusion matrix, and imbalanced classification report are generated for each resampling technique.
## Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk

In the same credit_risk_resampling.ipynb notebook, the SMOTEENN algorithm is used for resampling the data. The following steps are performed:

1.  Resampling with SMOTEENN: The SMOTEENN algorithm is used to resample the training data.
2.  Model evaluation: LogisticRegression classifier is used to make predictions and evaluate the model's performance.
3.  Model performance metrics: The accuracy score, confusion matrix, and imbalanced classification report are generated for the SMOTEENN resampling technique.

## Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

In the credit_risk_ensemble.ipynb notebook, the following steps are performed:

1.  Data preprocessing: The training variables are created by converting the string values into numerical ones using the get_dummies() method. The target variables are also created.
2.  Checking the balance of the target variables: The count of the target classes is visualized to check for class imbalance.
3.  Resampling with ensemble classifiers: BalancedRandomForestClassifier and EasyEnsembleClassifier algorithms are used to resample the training data.
4.  Model evaluation: The ensemble classifiers are used to make predictions and evaluate the model's performance.
5.  Model performance metrics: The accuracy score, confusion matrix, and imbalanced classification report are generated for each ensemble classifier.

### Conclusion
Based on the analysis of various resampling techniques and ensemble classifiers, it is recommended to use the SMOTEENN algorithm for resampling the data and the BalancedRandomForestClassifier for predicting credit risk. These models have shown relatively better performance in terms of accuracy and imbalanced classification report compared to other techniques used in this analysis.
