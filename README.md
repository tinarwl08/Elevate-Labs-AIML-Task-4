Logistic Regression Classification Project :


This project implements a binary classification model using Logistic Regression to predict whether a
tumor is malignant or benign using the Breast Cancer Wisconsin dataset.
Dataset
Dataset Source: Kaggle - Breast Cancer Wisconsin Dataset
Features include radius, texture, perimeter, area, smoothness, etc.
Objective
To build a machine learning model that accurately classifies tumors into malignant (1) or benign (0).
Tools & Libraries Used: 
Python, Pandas, NumPy, Matplotlib, Scikit-learn
Steps Performed:
1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Feature Scaling
4. Train-Test Split
5. Model Training using Logistic Regression
6. Model Evaluation using Confusion Matrix, Precision, Recall, ROC-AUC
7. ROC Curve Visualization
8. Threshold Tuning
Model Explanation:
Logistic Regression uses a sigmoid function to convert linear outputs into probabilities between 0
and 1.
Evaluation Metrics
Confusion Matrix: Shows correct and incorrect predictions.
Precision: Accuracy of positive predictions.
Recall: Ability to detect actual positives.
ROC-AUC: Measures overall model performance.
Results
The model performs well in distinguishing between malignant and benign tumors with high
ROC-AUC score.
Conclusion
Logistic Regression is an effective and interpretable model for binary classification problems like
cancer detection.
Future Improvements
Hyperparameter tuning, feature selection, trying advanced models like Random Forest or XGBoost.
