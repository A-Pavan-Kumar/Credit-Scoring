# Credit-Scoring
Prediction using RandomForestClassifier for credit scoring starts with data preprocessing, including dataset import, shape review, and initial data exploration for insights into columns and missing values. Descriptive statistics like `df.describe()` provide an overview of numerical features such as income, debt levels, and credit history age.

Following data inspection, categorical variables like 'Credit_Mix' are encoded into numerical format for model compatibility. Relevant features such as income, credit cards, loans, and credit utilization ratio are selected for their impact on credit score prediction.

The dataset is split into training and testing sets using `train_test_split`, ensuring the model can generalize well. RandomForestClassifier is then fitted to the training data with parameters like `n_estimators` and `class_weight`.

Predictions are generated using `model.predict(X_test)` and compared with `y_test` to evaluate model performance using metrics like accuracy and confusion matrix from `sklearn.metrics`.

In conclusion, RandomForestClassifier facilitates accurate credit scoring through robust data preparation, feature selection, model training, and performance evaluation, enhancing risk management and customer service in financial institutions.
