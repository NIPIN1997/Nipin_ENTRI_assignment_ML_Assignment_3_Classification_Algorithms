# Classification
## Dataset
The Breast Cancer Dataset available in the sklearn library is used.
## Preprocessing
1. The dataset is loaded into a dataframe.
2. The dataset is checked for duplicate rows.
3. The dataset is checked for missing values.
4. The skewness of the columns is corrected using logarithmic and square root transformations.
5. The dataset is scaled using StandardScaler.
## Training 
The classification algorithms used are:
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifer
4. Support Vector Classifier
5. k-Nearest Neighbor

For each model the following parameters are calculated:
1. Accuracy
2. Precision
3. Recall
4. F1 Score
## Conclusion
Support Vector Classifier have been identified as the best performing algorithm. Decision Tree Classifier have been identified as the worst performing algorithm.