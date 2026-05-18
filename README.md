# 🧠 AI-based Stroke Detection

## 📌 Overview
This project focuses on early detection of Large Vessel Occlusion (LVO) stroke using EEG signals and clinical data.  
The goal is to support faster diagnosis in prehospital settings and improve patient outcomes.

---

## 🎯 Objective
To build and evaluate a machine learning pipeline for stroke classification using multimodal medical data, including EEG features and clinical variables.

---

## 📊 Dataset
- EEG recordings collected from ambulance-based monitoring systems (Stroke Pointer device)
- Clinical and patient history data
- CT scan results used as ground truth labels for validation

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Signal cleaning and artifact removal using an existing CNN-based preprocessing pipeline developed within the system
- Focused on optimization and evaluation of preprocessing performance to improve EEG signal quality for downstream machine learning models

---

### 2. Feature Engineering
- Extraction of statistical EEG features
- Integration of clinical variables with signal-based features
- Feature selection using correlation analysis (Cramer’s V)

---

### 3. Machine Learning Models
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- XGBoost

---

### 4. Model Optimization
- Hyperparameter tuning using GridSearchCV
- Cross-validation for robust model evaluation

---

## 📈 Results
- Achieved model performance up to **88–95% accuracy** depending on feature combinations
- Improved classification performance by combining EEG and clinical features
- Enhanced robustness through feature engineering and parameter optimization

---

## 📊 Visualization
- Designed a 6-page interactive Power BI dashboard for comprehensive analysis of EEG and clinical data
- Each page provides a different analytical perspective, including data overview, trends, and feature-level insights
- Supported interpretation of patterns and relationships to assist clinical decision-making.
### Summary
Overview of EEG and clinical dataset insights.

![Summary](images/summary.png)

---

## 🧠 Key Impact
- Supported early detection of LVO stroke in prehospital settings
- Contributed to reducing time-to-diagnosis by improving data-driven decision support
- Improved interpretability of ML predictions through visualization tools

---

## 🛠 Tools & Technologies
Python | Pandas | NumPy | Scikit-learn | XGBoost |CNN-based preprocessing (optimization)| Power BI | SQL | Matplotlib

---

## 👩‍💻 Role & Contribution
- Data preprocessing and pipeline optimization, including optimization of the CNN-based signal processing component.
- Feature engineering and statistical analysis
- Machine learning model training and evaluation
- Dashboard development for result visualization
- Collaboration with clinicians and engineers in an Agile environment
