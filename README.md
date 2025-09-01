# Ensemble-Learning-for-DDoS-Classification
Ensemble Stacking Model for Distributed Denial of Service Attacks Classification using dataset CIC-DDoS2019

📌 Project Overview: 
The goal of this project is to develop and evaluate a heterogeneous ensemble stacking model for detecting and classifying Distributed Denial of Service (DDoS) attacks using the CIC-DDoS2019 dataset.

🔍 Key Features: 
Implementation of multiple base learners: Random Forest, XGBoost, AdaBoost, and Decision Tree. A Logistic Regression meta-learner to combine base model predictions. Multiclass classification across 12 different attack categories. Comprehensive evaluation using multiple metrics:
- Accuracy
- Precision, Recall, F1-Score
- ROC-AUC (macro-averaged One-vs-Rest)
- Confusion Matrix
- Inference Time

📂 Dataset: 
Source: CIC-DDoS2019 https://www.unb.ca/cic/datasets/ddos-2019.html 
Preprocessing steps include scaling and feature selection.
