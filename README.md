### Module-17-Challenge

ANALYSIS

Dataset contains information on loan application.

Refer to credit_risk_resampling_N.ipynb file. 

## 1.1 Oversampling on the dataset using two oversampling algorithms - naive random oversampling algorithm and the SMOTE algorithm.
As illustrated in the table below the balanced_accuracy_score of random oversampling algorithm equals to 0.682 and it is better than the score of SMOTE algorithm of 0.663.
The high risk precision of 0.01 is very law in both models and recall is better for naive random oversampling algorithm.

![Table1](Capture1.1.PNG)



## 2 ClusterCentroids resampling moduleI has lower metrics in comparison to oversampling algorithms as shown in the table below: 
the balanced_accuracy_score of 0.544, high risk recall of 0.67 (slightly better than in SMOTE algorithm) and the same high risk precision of 0.01.

![Table2](Capture2.PNG)

##1.3 gfhj

##1.4


While resampling can attempt to address imbalance, it does not guarantee better results.
