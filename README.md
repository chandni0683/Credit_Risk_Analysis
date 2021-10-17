# Credit_Risk_Analysis
## Overview of the analysis
The purpose of this analysis is to employ different techniques to train and evaluate models with unbalanced classes. Imbalanced-learn and scikit-learn libraries has been used to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we have oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we have used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Lastly we evaluated the performance of these models and made a written recommendation on whether they should be used to predict credit risk.

## Results

After the data is resampled we use LogisticRegression classifier to make predictions and evaluate the model’s performance. We have calculated the accuracy score of the model, generated a confusion matrix, and then print out the imbalanced classification report. The balanced accuracy score, the recall score and accuracy score were calculated for each sample using six machine learning models.









