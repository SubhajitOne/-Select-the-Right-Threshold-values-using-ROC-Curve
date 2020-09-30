# -Select-the-Right-Threshold-values
In classification problem selecting the right threshold is important while getting the right accuracy score.
Here with the use of a ROC curve we select the right threshold value by comparing with each accuracy score.
This is done by taking the means of the predictions obtained from four models of RandomForest, LogisticRegression, Adaboost and KNN classifiers
and stored in a series named as 'final_prediction'.
