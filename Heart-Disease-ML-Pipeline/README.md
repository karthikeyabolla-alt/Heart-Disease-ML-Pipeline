# ❤️ Heart Disease ML Pipeline

> 🚀 Built as my first Machine Learning project during my first year as a Computer Science student specializing in Data Science.

This project focuses on building an end-to-end Machine Learning pipeline for heart disease prediction using preprocessing, feature engineering, outlier detection, feature selection, and model comparison techniques.

---

# 📌 Project Overview

This project implements a complete Machine Learning workflow for predicting heart disease using clinical healthcare data.

The primary focus of this project was understanding:

* Data preprocessing
* Data quality analysis
* Feature engineering
* Outlier detection
* Feature selection
* Model evaluation

rather than simply training ML models.

---

# 🚀 Features Implemented

## ✅ Data Quality & Preprocessing

* Missing value handling
* Duplicate checking
* Data cleaning
* Schema detection
* Invalid value detection
* Categorical feature handling

---

## ✅ Feature Engineering

* Label Encoding
* Numerical feature scaling
* Standardization using StandardScaler

---

## ✅ Outlier Detection

Implemented multiple outlier detection techniques:

* Local Outlier Factor (LOF)
* K-Nearest Neighbors (KNN)

---

## ✅ Feature Selection

Applied:

* Recursive Feature Elimination (RFE)
* Chi-Square Feature Selection

---

## ✅ Machine Learning Models

Compared multiple classification models:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

---

# 📊 Best Model Performance — Random Forest

## 🔹 Accuracy

75.4%

---

## 🔹 Classification Report

```text
              precision    recall  f1-score   support

           0       0.81      0.69      0.75        32
           1       0.71      0.83      0.76        29

    accuracy                           0.75        61
   macro avg       0.76      0.76      0.75        61
weighted avg       0.76      0.75      0.75        61
```

---

## 🔹 Confusion Matrix

```text
[[22 10]
 [ 5 24]]
```

---

# 📌 Result Analysis

* Random Forest achieved the best overall performance among the tested models.
* The model showed strong recall for detecting positive heart disease cases.
* Ensemble learning improved generalization compared to individual tree models.
* Data preprocessing and feature engineering significantly improved model quality.

---

# 🛠️ Technologies Used

## Programming Language

* Python

## Libraries

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

# 📂 Project Workflow

```text
Dataset Loading
       ↓
Data Inspection
       ↓
Data Quality Checks
       ↓
Missing Value Handling
       ↓
Encoding & Scaling
       ↓
Feature Engineering
       ↓
Outlier Detection
       ↓
Feature Selection
       ↓
Model Training
       ↓
Model Evaluation
```

---

# 📁 Project Structure

```bash
Heart-Disease-ML-Pipeline/
│
├── DataSet.csv
├── MyProject1.ipynb
├── requirements.txt
└── README.md
```

---

# ▶️ How to Run

## Clone the Repository

```bash
git clone https://github.com/your-username/heart-disease-ml-pipeline.git
```

---

## Navigate to Project Folder

```bash
cd heart-disease-ml-pipeline
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Notebook

Open:

```text
MyProject1.ipynb
```

using:

* Jupyter Notebook
* VS Code
* Google Colab

---

# 📚 Key Learning Outcomes

Through this project, I gained practical experience in:

* Building end-to-end ML pipelines
* Data preprocessing and cleaning
* Feature engineering
* Outlier detection methods
* Feature selection techniques
* ML model evaluation and comparison

---

# 🔮 Future Improvements

* Hyperparameter tuning using GridSearchCV
* Cross-validation techniques
* Experimenting with XGBoost and LightGBM
* Building a Streamlit web application
* Model explainability using SHAP and LIME
* SMOTE-based class balancing
* Cloud deployment using AWS or Render
* MLflow experiment tracking
* Docker containerization

---

# 👨‍💻 Author

Developed as part of my Machine Learning learning journey as a first-year Computer Science student specializing in Data Science.
