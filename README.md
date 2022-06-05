## Anomaly detection using pyspark

### EDA
After creating the spark session, the data is loaded and an analysis on the class imbalance is performed. 
Additional visualizations are provided to have an idea of the relationship between some of the variables.

### Feature extraction
In this section, the data is rebalanced to improve the performance of the models to be trained later. 
Feature selection is explained and the one-hot encoding is applied to the selected categorical variables. 
At the end, the correspondent pipeline is built using Gradient Boosted Tree model (and decision tree for comparison).

### Training and evaluation of model
After training the model, AUC curve, accuracy, recall and precision are evaluated.
