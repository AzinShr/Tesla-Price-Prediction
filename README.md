# Model Evaluation

We tested three machine learning classifiers for predicting Tesla stock price movement:

* Logistic Regression – simple linear baseline

* Support Vector Classifier (SVC) – nonlinear decision boundaries using a polynomial kernel

* XGBoost Classifier (XGBClassifier) – gradient-boosted trees for capturing complex patterns

# Workflow:

* Models were trained on historical Tesla stock data features.

* Predictions were evaluated using ROC-AUC, which measures how well the model distinguishes upward vs downward price movements.

* Training and validation ROC-AUC scores were recorded to check for overfitting.

* The confusion matrix was plotted for Logistic Regression to visualize correct and incorrect predictions.
