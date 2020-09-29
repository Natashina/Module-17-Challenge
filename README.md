### Module-17-Challenge

ANALYSIS

Dataset contains information on loan application.

Refer to credit_risk_resampling_N.ipynb file for implementation of over- and under- sampling techniques. 
A LogisticRegression model has been used to generate predictions.

## 1. Oversampling on the dataset - naive random oversampling algorithm and the SMOTE algorithm.
As illustrated in the table below the balanced_accuracy_score of random oversampling algorithm equals to 0.682 and it is better than the score of SMOTE algorithm of 0.663.
The high risk precision of 0.01 is very law in both models and recall is better for naive random oversampling algorithm.

![Table1](Capture1.1.PNG)



## 2. Cluster Centroids resampling
This undersampling model has lower metrics in comparison to oversampling algorithms as shown in the table below: 
the balanced_accuracy_score of 0.544, high risk recall of 0.67 (slightly better than in SMOTE algorithm) and the same high risk precision of 0.01.

![Table2](Capture2.PNG)

## 3. A combination over- and under-sampling algorithm (SMOTEENN) 

It was tested to determine if the algorithm results in the best performance compared to the other sampling algorithms above.

![Table3](Capture3.1.PNG)


Resampling with SMOTEENN results some better metrics than undersampling model.
While resampling can attempt to address imbalance, it does not provide better results.

To summarize, the resampling techniques such as SMOTE, Cluster Centroids and SMOTEENN do not have favourably distinguished outcome. The high risk precision resulting in every of these algorithms is equal to 0.01 which is not acceptable for  decision making.
