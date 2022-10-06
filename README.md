# Credit_Risk_Analysis

## Overview

#### This analysis aims to evaluate credit card risk, an inherently unbalanced classification problem, by applying machine learning models. For Deliverable 1, the oversampling “RandomOverSampler” and “Smote” algorithms, as well as the undersampling “ClusterCentroids” algorithm will be used to determine which is better at predicting credit risk. Deliverable 2 includes a combined approach of over- and undersampling with the “SMOTEENN” algorithm to determine which method more accurately predicts risk. Finally, two different ensemble classifiers, “BalancedRandomForestClassifier” and “EasyEnsembleClassifier” will be used in Deliverable 3. 

## Results

-	RandomOverSampler: the RandomOverSampler results had a 66% accuracy rate. The F1 score, or the summary statistic of precision and sensitivity , is only .02% for the high-risk category.

![](https://github.com/AB3478/Credit_Risk_Analysis/blob/c46d8dacffaa59599d8f1b8243ad29fb6a7b941e/Resources/RandomOverSampler.png)

![](https://github.com/AB3478/Credit_Risk_Analysis/blob/c46d8dacffaa59599d8f1b8243ad29fb6a7b941e/Resources/RandomOverSampler_report.png)

-	SMOTE: the SMOTE results had a 65% accuracy rate. The F1 score for the high-risk category was also very low at .02.

![](https://github.com/AB3478/Credit_Risk_Analysis/blob/c46d8dacffaa59599d8f1b8243ad29fb6a7b941e/Resources/SMOTE.png)

![](https://github.com/AB3478/Credit_Risk_Analysis/blob/c46d8dacffaa59599d8f1b8243ad29fb6a7b941e/Resources/SMOTE_report.png)

-	ClusterCentroids: the ClusterCentroids results also had a 65% accuracy rate. The F1 score for the high-risk category was lowest overall with .01.

![](https://github.com/AB3478/Credit_Risk_Analysis/blob/c46d8dacffaa59599d8f1b8243ad29fb6a7b941e/Resources/Cluster.png)

![](https://github.com/AB3478/Credit_Risk_Analysis/blob/c46d8dacffaa59599d8f1b8243ad29fb6a7b941e/Resources/Cluster_report.png)

-	SMOTEENN: the SMOTEEN results had a 65% accuracy rate. The F1 score for the high-risk category was .02.
	
![](https://github.com/AB3478/Credit_Risk_Analysis/blob/c46d8dacffaa59599d8f1b8243ad29fb6a7b941e/Resources/SMOTEENN.png)

![](https://github.com/AB3478/Credit_Risk_Analysis/blob/c46d8dacffaa59599d8f1b8243ad29fb6a7b941e/Resources/SMOTEENN_report.png)

-	BalancedRandomForestClassifier: the BalancedRandomForestClassifier did slightly better overall with a 78% accuracy rate an F1 score for the high-risk category of .06. 

![](https://github.com/AB3478/Credit_Risk_Analysis/blob/c46d8dacffaa59599d8f1b8243ad29fb6a7b941e/Resources/BRFC.png)

![](https://github.com/AB3478/Credit_Risk_Analysis/blob/c46d8dacffaa59599d8f1b8243ad29fb6a7b941e/Resources/BRFC_report.png)

-	EasyEnsembleClassifier: the EasyEnsembleClassifer was the most accurate of the models at 93% and a F1 score for the high-risk category of .16.

![](https://github.com/AB3478/Credit_Risk_Analysis/blob/c46d8dacffaa59599d8f1b8243ad29fb6a7b941e/Resources/EEC.png)

![](https://github.com/AB3478/Credit_Risk_Analysis/blob/c46d8dacffaa59599d8f1b8243ad29fb6a7b941e/Resources/EEC_report.png)


## Summary

#### The EasyEnsembleClassifier model outperformed the others, however, I do not recommend using any of the models alone in evaluating credit risk. The machine learning models may be helpful in narrowing the pool of candidates that require further manual review. 

