# Tiktok

In this parctice I have downloaded the Tiktok dataset from Kaggle.

I used different ML techniques to acheive the best result.

I have droped the NAs and the unuseful columns from the dataset.

I chose verified_status as my target and predicted its values after categorizing the outcome 0 and 1

From there I used the Logistic Regression techinique the model was giving high preformance on the majority set (non active) and

0 for the active set.

To fix this I used SMOTE to resample my data but the performance was not impressive, so I used the Random Forest technique with SMOTE and without.

The best result acheive was with SMOTE where my model was able to give greater than 90% (presicion and recall) for both active and non active.

Note that scaling the data did not make any difference for the Logistic Regression.
