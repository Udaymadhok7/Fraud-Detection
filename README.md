# Fraud Detection
I performed exploratory data analysis (EDA) and preprocessing on the fraud detection dataset, followed by feature engineering and handling multicollinearity. After scaling the transaction amount into a new NormalizedAmount feature, I prepared the data by splitting it into features and the target variable (isFraud). Using a stratified train-test split to maintain the imbalance ratio, I trained a Random Forest Classifier with class balancing to address the skewed distribution of fraud cases. The model was then evaluated using a confusion matrix and classification report to measure accuracy, precision, recall, and F1-score. Finally, I analyzed feature importances to identify the most influential variables in predicting fraud, gaining insights into which transaction characteristics contribute most to fraudulent activity.


## **Dataset Link-https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset?resource=download**
