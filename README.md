# Binary-Classification-APS


# Air-Pressure-System-Analysis-and-Prediction
Prediction of Failures in the Air Pressure System of Scania Trucks using Machine Learning and Deep Learning Model.
Problem Statement: To reduce the maintenance cost of the vehicle we have know whether the failure of the part is because of APS or not. Which will help to proper inspection of vehicle if someone know about the cause of failure. Negative:0 and positive:1.Negative cases mean the failure is not because of APS, where as Positive cases are failure due to APS.


Implemenated Machine Learning Approach:
1. Logistic Regression
2. Support Vector Machine
3. Random Forest Classificer
4. Adaptive Boosting
5. Deep Learnign Neural Network

Parameters used for Performance Evaluation
1. Validation loss
2. Classification Report
3. Confusion Matrix
4. Precision-Recall Curve
5. ROC


There are three files 
1. Approach_First.ipynb

2. Approach_Second.ipynb

3. Approach_Third.ipynb

Training Datasets contains training and test datasets. Training Dataset shape 60000 * 171 and Test Dataset 16000 * 171. This dataset is unbalanced, it has around 88% cases are negrative and 12% cases are positive.

About Files
1. Approach_First.ipynb: Removed all the null values from dataset, training the model and evaluated the model performance without applying the PCA.

2. Approach_Second.ipynb: Removed all the null values from dataset, training the model and evaluated the model performance with applying the PCA.

3. Approach_Third.ipynb: Removed the columns which has more than 70% Null values, filling the remaining data with median values and trained on above mentioned machine learning models.

