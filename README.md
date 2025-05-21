# 🧬 Fertility Predictor
A machine learning-based project to predict fertility-related health outcomes using patient data. This solution leverages logistic regression with preprocessing techniques and class balancing to address data imbalance and improve prediction accuracy.

📌 Project Overview
This notebook implements a Fertility Prediction Model trained on health-related features. The pipeline includes:
1. Data loading and preprocessing
2. One-hot encoding of categorical features
3. Balancing the dataset using SMOTE
4. Training a Logistic Regression model
5. Model evaluation using classification metrics
6. Visualization of performance

🚀 Features
1. Handles imbalanced data using SMOTE (Synthetic Minority Over-sampling Technique)
2. Performs one-hot encoding for categorical variables
3. Uses StandardScaler for feature normalization
4. Evaluates model with:
-Accuracy
-Confusion Matrix
-Classification Report

🛠️ Tech Stack
Python 3
pandas, numpy
scikit-learn
imbalanced-learn (SMOTE)
seaborn, matplotlib (for visualization)

📁 Dataset
The dataset is uploaded via Google Colab's file upload interface. It should contain health-related features and a target column labeled Diagnosis indicating fertility condition.
Make sure the data:
-Is in CSV format
-Has clean, meaningful column names
-Contains categorical features for encoding and a binary/multiclass target

📌 Future Improvements
Integrate other models (e.g., Random Forest, XGBoost)
Add support for multi-class classification
Develop a web or mobile interface for input and prediction
Perform hyperparameter tuning and cross-validation
