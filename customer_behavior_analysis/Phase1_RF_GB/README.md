# Phase 1 - Stacked RF+GB Model 

📂 Overview
This phase focuses on customer behavior analysis using a Stacked Model that combines Random Forest (RF) and Gradient Boosting (GB). The goal is to enhance prediction accuracy for customer behavior patterns in an e-commerce setting.

📊 Dataset
The dataset consists of customer transactions, including purchasing behavior, browsing activity, and demographic details.
Data preprocessing includes handling missing values, feature engineering, and encoding categorical variables.

🏗 Model Architecture
A Stacked Model is implemented, where predictions from Random Forest (RF) and Gradient Boosting (GB) are combined using a meta-classifier.
Random Forest (RF) captures feature importance and reduces overfitting.
Gradient Boosting (GB) enhances predictive power by sequentially correcting weak learners.

🚀 Performance
Final Accuracy: 96.13%
Evaluation Metrics: Precision, Recall, F1-score
Feature Importance Analysis: Identifies key features influencing customer behavior

🔧 Implementation
The model is developed in Python using scikit-learn.
