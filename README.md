# 🫀 Heart Failure Prediction with Machine Learning

## 📌 Project Overview

This project focuses on building a predictive model to estimate the probability of mortality among patients with heart failure. Using structured clinical data, the model aims to identify high-risk patients by analyzing physiological and laboratory features such as age, ejection fraction, creatinine levels, and blood pressure.

The goal is to enable early risk detection and support data-driven decisions in healthcare.

---

## 🗂️ Dataset

- **Source**: [Kaggle – Heart Failure Data](https://www.kaggle.com/datasets)
- **Total Records**: 299
- **Target Variable**: `DEATH_EVENT` (1 = Died, 0 = Survived)

**Key Features**:
- `age`
- `ejection_fraction`
- `serum_creatinine`
- `high_blood_pressure`
- `anaemia`, `diabetes`, `smoking`, etc.

---

## 🔍 Project Workflow

1. **Data Preprocessing**
   - Checked for nulls and datatypes
   - Normalized numerical features using `StandardScaler`

2. **Exploratory Data Analysis**
   - Histograms and pie charts for distribution of key features
   - Correlation heatmap for feature relationships

3. **Model Training**
   - Trained 3 models:
     - Decision Tree
     - K-Nearest Neighbors
     - Logistic Regression

4. **Model Evaluation**
   - Accuracy score
   - Confusion matrix
   - Classification report (Precision, Recall, F1-Score)

---

## 📈 Results Summary

| Model               | Accuracy |
|--------------------|----------|
| Decision Tree       | ~76%     |
| K-Nearest Neighbors | ~78%     |
| Logistic Regression | ~80%     |

> Logistic Regression outperformed other models slightly in terms of accuracy.

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- scikit-learn
- Pandas, NumPy, Seaborn, Matplotlib

---

## ▶️ How to Run

1. Clone this repository  
   ```bash
   git clone https://github.com/aanwaokolo/Personal-projects-and-assessments.git
