# Credit_card_fraud_detection
This dataset consists of 1296675 rows in the training dataset and 555719 rows in the testing dataset with 23 features.
Since the dataset was huge a random sample of the dataset was taken and also since the datset has only 4-7% of fraud data removing the fraud data was greatly avoided.
The features contain both numeric and nominal data hence Onehotencoding was performed on the cloumns having nominal data.
Performing Onehotencoding increased the number of features to 600+ hence PCA was performed to reduce the features number to 33.
Smote sampling was used to produce fake frauds to balance the number of fraud and non fraud in the dataset to ratio of non fraud to fraud as 2:1.
No scaling was needed since the models used were RandomForest and XGBoost.
Both RandomForest and XGBoost were used as they are ensemble learning methods which help achieve more accurate predictions.
On top of that, stacking ensemble learning was used on both the above mentioned models.
Accuracy achieved was 98%.
Recall Achieved was 0.82.
