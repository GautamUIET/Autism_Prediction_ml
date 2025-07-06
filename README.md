# Autism Spectrum Disorder (ASD) Prediction Model

![ASD Prediction](https://img.shields.io/badge/Python-3.8%2B-blue) 
![License](https://img.shields.io/badge/License-MIT-green) 
![ML](https://img.shields.io/badge/Machine%20Learning-RandomForest-orange)

A machine learning model to predict Autism Spectrum Disorder (ASD) based on behavioral and demographic features. Built with `scikit-learn`, `XGBoost`, and `imbalanced-learn`.

---

## 📌 Table of Contents
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Dataset](#-dataset)
- [Model Training](#-model-training)
- [Results](#-results)
- [License](#-license)
- [Contributing](#-contributing)

---

## 🌟 Features
- **Data Preprocessing**: Handles missing values, categorical encoding (`LabelEncoder`), and class imbalance (`SMOTE`).
- **Multiple Models**: Compares `RandomForest`, `XGBoost`, and `DecisionTree`.
- **Model Persistence**: Saved encoders (`encoders.pkl`) and trained model (`model.pkl`) for reuse.
- **Evaluation Metrics**: Accuracy, precision, recall, and confusion matrix.

---

## 🛠 Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/asd-prediction.git
   cd asd-prediction
