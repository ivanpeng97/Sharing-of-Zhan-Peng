# Project description:

Development of a model predicting the recovery rate of gold from gold ore.

The company develops solutions for the efficient operation of the gold mining industry. A model has been built that predicts the recovery rate of gold from gold-bearing ore. The data with the parameters of extraction and treatment are analyzed. A model has been built and trained to help optimize production in order not to launch an enterprise with unprofitable characteristics.

# Data description:

The data is stored in three files:

gold_recovery_train.csv

gold_recovery_test.csv

gold_recovery_full.csv

Data is indexed with the date and time of acquisition (date feature). Parameters that are next to each other in terms of time are often similar. Some parameters are not available because they were measured and/or calculated much later. That's why, some of the features that are present in the training set may be absent from the test set. The test set also doesn't contain targets. The source dataset contains the training and test sets with all the features.
