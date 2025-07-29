# fraud-financial-transaction

Detect fraud financial transactions

Comparison study of 5 models:

- Random Forest
- Ada Boost
- XG Boost
- Isolation Forest
- Local Outlier Factor

First go through the data_exploration notebook, since the data .csv file and the metadata .json file, needs to be downloaded.
Then, go through the classifier_experiment notebook for the model study/comparison.

This data set is highly imbalanced, fraud transactions are very rare as compared to normal transactions.
Our main motive is to detect and flag a fraud/anomaly in our system, so we look to maximize the RECALL value over PRECISION.

We could use SMOTE technique to balance out the minority class, but that is a different topic altogether.
