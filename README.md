❤️ Heart Failure Mortality Prediction
By Fathima Hiba C

📌 Project Overview

This project focuses on predicting mortality risk in heart failure patients using machine learning techniques. A key objective was to identify and correct data leakage to ensure realistic and deployable model performance.

Two models were developed:

Model A – Included follow-up time (contained leakage)

Model B – Leakage-free model (final selected model)

Model B was selected for deployment due to its realistic predictive capability.

📊 Dataset

The dataset contains 299 patient records with demographic and clinical variables including:

Age

Ejection fraction

Serum creatinine

Serum sodium

Creatinine phosphokinase

Comorbidities

Follow-up time

Target Variable:
DEATH_EVENT (0 = Survived, 1 = Died)

🧠 Machine Learning Approach

Data Cleaning & EDA

Log transformation of skewed features

Random Forest Classifier

ROC-AUC evaluation

Threshold tuning for recall optimization

Leakage detection and correction

📈 Results
Metric	Model A	Model B
ROC-AUC	0.87	0.78
Recall	High	Moderate
Leakage	Yes	No

Model B was selected as the final model.

📊 Power BI Dashboard

An interactive Power BI dashboard was developed to:

Visualize dataset insights

Compare model performance

Analyze clinical risk factors

Interpret high-risk patient profiles

🛠 Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

Power BI

🔍 Key Learning

This project highlights the importance of responsible machine learning, particularly in healthcare applications where data leakage can significantly inflate performance metrics.
