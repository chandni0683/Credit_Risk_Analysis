# Credit_Risk_Analysis
## Overview of the analysis
The purpose of this analysis is to employ different techniques to train and evaluate models with unbalanced classes. Imbalanced-learn and scikit-learn libraries has been used to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we have oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we have used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Lastly we evaluated the performance of these models and made a written recommendation on whether they should be used to predict credit risk.

## Results

After the data is resampled we use LogisticRegression classifier to make predictions and evaluate the model’s performance. We have calculated the accuracy score of the model, generated a confusion matrix, and then print out the imbalanced classification report. The balanced accuracy score, the recall score and accuracy score were calculated for each sample using six machine learning models.

1. Naive Random Result:

<img width="1135" alt="Screen Shot 2021-10-17 at 4 18 39 PM" src="https://user-images.githubusercontent.com/85711507/137645365-1fe26b10-cb2e-499a-b648-c14a5057d9ca.png">

2. Smote Oversampling results:

<img width="1117" alt="Screen Shot 2021-10-17 at 4 20 08 PM" src="https://user-images.githubusercontent.com/85711507/137645405-c4565b42-0090-4bc2-831f-2a88a3daadbe.png">

3. Undersampling Results:

<img width="1117" alt="Screen Shot 2021-10-17 at 4 20 08 PM" src="https://user-images.githubusercontent.com/85711507/137645669-ef3df640-32ea-4e36-8c7b-f9e8e9f645a9.png">

4. Combination (Over and Under) Sampling Results:

<img width="1113" alt="Screen Shot 2021-10-17 at 4 33 35 PM" src="https://user-images.githubusercontent.com/85711507/137645712-f744d36a-a783-4acd-a88d-f5829d2b44c8.png">

5. Balanced Random Forest Classifier:

<img width="1123" alt="Screen Shot 2021-10-17 at 4 34 41 PM" src="https://user-images.githubusercontent.com/85711507/137645732-637578b2-7f23-4917-94dc-36adf6c41c9e.png">

6. Easy Ensemble AdaBoost Classifier:

<img width="1119" alt="Screen Shot 2021-10-17 at 4 36 44 PM" src="https://user-images.githubusercontent.com/85711507/137645795-af448874-799f-4c0d-b11f-62a09abc37ed.png">

## Summary

We used six machine learning models. The first four models we used were Naive random, undersampling, oversampling and a combination of oversampling and undesampling. The other two models which we used to resample the data were Balanced random forest classifier and Easy ensemble Adaboost classifier. These models are used to predict which loans are high risk and low risk. The best machine learning model among the six models would be Easy Ensemble AdaBoost Classifier. The Easy Ensemble has teh highest accuracy score and a fair balance of precison and recall scores. 


