# ❤️ Heart Failure Clinical Records - Mortality Risk Prediction

This project aims to build a machine learning-based predictive model using heart failure clinical records to assist in early detection and risk assessment of mortality in patients suffering from heart disease. The dataset used contains real clinical data of patients collected during follow-up medical appointments, including attributes such as age, anaemia status, ejection fraction, serum creatinine, and more.

The project focuses on extracting meaningful patterns from the data, dealing with imbalanced classes, and evaluating the effectiveness of multiple classification algorithms in predicting patient survival.

---

## 📂 Dataset Overview

- **Source:** [UCI Machine Learning Repository – Heart Failure Clinical Records](https://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records)
- **Records:** 299 patient records
- **Features:** 13 clinical attributes
- **Target Variable:** DEATH_EVENT (1 = died during follow-up, 0 = survived)

---

## 🎯 Project Objectives

- Perform **exploratory data analysis (EDA)** to uncover patterns and correlations.
- Handle **data imbalance** using re-sampling techniques like SMOTE and Random Over/Under Sampling.
- Train and evaluate multiple **classification algorithms**.
- Identify the most important features affecting heart failure mortality.
- Provide visual and metric-based insights to compare model performance.

---

## 🛠️ Tools and Technologies

| Category              | Tools/Technologies                          |
|----------------------|---------------------------------------------|
| Programming Language | Python                                      |
| Data Handling        | pandas, NumPy                               |
| Visualization        | matplotlib, seaborn                         |
| ML Models            | scikit-learn (Logistic Regression, KNN, SVM, Decision Tree, Random Forest) |
| Re-sampling          | imbalanced-learn (SMOTE, Random Sampling)   |
| Metrics              | Accuracy, Precision, Recall, F1 Score, ROC-AUC |

---

## 🔍 Exploratory Data Analysis (EDA)

- Analyzed distribution of clinical features such as age, serum creatinine, and ejection fraction.
- Visualized class imbalance between survival and death events.
- Correlation heatmaps to understand inter-feature relationships.
- Boxplots and histograms for visual comparison.

---

## ⚙️ Machine Learning Models

The following models were trained and evaluated:

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **Random Forest**

Each model was trained using both original and balanced datasets to observe improvements in performance metrics.

---

## 📈 Model Evaluation Metrics

For each model, the following were computed:

- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curve & AUC

Example snippet:

```plaintext
Model: Random Forest
Accuracy: 0.87
Precision: 0.80
Recall: 0.83
F1 Score: 0.81
AUC Score: 0.88
