
# Neuroscience

## Inconsistency Prediction in Tradeoff Procedure using EEG and Machine Learning Algorithms
This project aims to analyze the inconsistencies of the Tradeoff Procedure with the help of EEG equipment and machine learning algorithms. The dataset used in this project is in CSV format and includes information from different users, such as the channel used, frequency band, and experiment stage.

## Data Preprocessing
To preprocess the data, the following steps were applied:

1. Conversion of the 'Valor' column to a float
2. Removal of irrelevant columns
3. One-hot encoding of categorical variables
4. The preprocessed data was then split into training and testing sets to train and evaluate different machine learning models.

## Machine Learning Models
The following machine learning models were used in this project:

* Decision Tree
* SVM
* Random Forest Classifier
* KNN KNeighborsClassifier
* Dense Neural Network (DNN)

## Evaluation Metrics
The following evaluation metrics were used to evaluate the models:

* Precision
* Recall
* F1 score
* ROC AUC score
* Accuracy score
* Confusion matrix
## Results
The results of the evaluation show that the Random Forest and KNN models achieved the highest precision, recall, and F1-score, with the Random Forest model having the highest AUC-ROC score. The Decision Tree model had the highest accuracy. The SVM models had lower accuracy and AUC-ROC scores, with the polynomial kernel achieving the highest accuracy among the different SVM kernels. The DNN model achieved the highest accuracy of all the models.

## Conclusion
This project demonstrates the use of machine learning algorithms in neuroscience experiments, specifically in predicting inconsistencies in the Tradeoff Procedure using EEG data. The findings could be valuable for future research in the field.
