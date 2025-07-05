# Credit-Card-Fraud-Detection

🔐 Credit Card Fraud Detection 

A machine learning project to identify fraudulent credit card transactions using classification techniques, feature engineering, and model evaluation.  

📌 Objective 

Develop a classification model that can accurately detect fraudulent transactions with minimal false positives.

📊 Project Overview
Credit card fraud is a major concern in today's digital world. This project applies various machine learning techniques to analyze transaction patterns and identify potentially fraudulent activities.

🔍 Problem Statement
Detect fraudulent transactions using historical credit card transaction data. The dataset is highly imbalanced, with a small percentage of fraud cases, making it a good challenge for applying anomaly detection and classification models.

🧰 Tech Stack & Tools
Python 🐍

Jupyter Notebook 📓

Pandas, NumPy – data manipulation

Matplotlib, Seaborn – data visualization

Scikit-learn – machine learning models

Imbalanced-learn – handling class imbalance (SMOTE, etc.)

🗃️ Dataset
Source: Kaggle – Credit Card Fraud Detection

Contains transactions made by European cardholders in September 2013.

Total Records: 284,807

Fraudulent Cases: 492

Features:

Time, Amount, and 28 anonymized features (V1 to V28) obtained using PCA

Class: Target variable (0 = Genuine, 1 = Fraud)

🧪 Models Used
Logistic Regression

Decision Tree

Random Forest

XGBoost

Isolation Forest (Anomaly Detection)

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC

📈 Results & Insights
Handled imbalance using SMOTE

Achieved high Recall to ensure fraudulent transactions are not missed

ROC-AUC score used for model comparison

Visualized feature importance and correlation heatmaps

🚀 How to Run
bash
Copy
Edit
git clone https://github.com/shubham-05/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
open notebook.ipynb in Jupyter
📁 Folder Structure
kotlin
Copy
Edit
📦 Credit-Card-Fraudent
├── 📄 README.md
├── 📄 Anmoly Detection.ipynb
└── 📄license
👨‍💻 Author
Shubham Mahadik
Machine Learning Enthusiast | Data Science Learner