❤️ Heart Disease Prediction Using Ensemble Learning — Capstone Project (TNSIF)

This project predicts heart disease using supervised machine learning. It uses an ensemble of three classifiers to improve predictive performance.

📌 Objective

Classify patients as either Heart Disease Present or Not Present

Use clinical features and engineered features to improve accuracy

Build a soft-voting ensemble model

📊 Dataset Overview

Target: heart_disease (0 = No, 1 = Yes)

Feature Count: Multiple clinical attributes

🧩 Feature Engineering

age_chol = age × cholesterol

thalach_age = thalassemia / (age + 1)

🛠 Data Preprocessing

Loaded dataset

Created engineered features

Performed train-test split (80-20) with stratification

Applied StandardScaler to all features

No one-hot encoding performed

🤖 Models Used

RandomForestClassifier

GradientBoostingClassifier

LogisticRegression

Final Model

Soft Voting Classifier combining all three models

📈 Saved Artifacts

HeartDisease_Ensemble.pkl

scaler.pkl

▶️ Run Training Script
python train_model.py


🧰 Technologies Used

Python

Pandas, NumPy

Scikit-learn

Joblib

Ensemble Learning
