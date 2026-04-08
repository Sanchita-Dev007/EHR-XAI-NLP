# EHR-XAI-NLP
# Explainable AI for EHR Information Extraction using NLP

## 📌 Project Overview
This project focuses on building a Machine Learning model to predict **30-day hospital readmission risk** using Electronic Health Records (EHR) data.

The model is designed with an Explainable AI (XAI) approach, where we not only predict outcomes but also understand which features influence the predictions.

---

## 🎯 Objectives
- Predict patient readmission risk
- Analyze important clinical features
- Improve decision-making in healthcare
- Demonstrate explainable AI using feature importance

---

## 🧠 Model Used
- XGBoost Classifier
- Gradient Boosted Decision Trees
- Handles tabular healthcare data efficiently

---

## ⚙️ Features Used
- Age
- Number of hospital visits (last 180 days)
- Length of hospital stay
- Charlson Comorbidity Index
- Number of medications prescribed
- Emergency visits count
- Hemoglobin level change
- Days since last discharge

---

## 📊 Performance Metrics
The model was evaluated using 5-fold cross-validation:

- Accuracy: ~84%
- Precision: ~38%
- Recall: ~63%
- Log Loss: ~0.38

---

## 📈 Explainability (XAI)
Feature importance analysis shows:

- **Days since last discharge** → most important feature
- Followed by:
  - Number of visits
  - Comorbidity index
  - Discharge disposition

This helps in understanding why the model predicts high-risk patients.

---

## 📁 Project File
- `EHR_Model_Pipeline.ipynb` → contains full implementation

---

## ▶️ How to Run
1. Open the notebook in Google Colab
2. Run all cells step-by-step
3. Observe results and graphs

---

## ⚠️ Note
Dataset is not included due to size/privacy constraints.  
All results and outputs are available in the notebook.

---

## 👩‍💻 Author
Sanchita Kumari
Prerna
Jhanvi Singh
Sankalp Rajput
[CSE(AI-ML)]

