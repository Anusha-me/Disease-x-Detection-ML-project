# Disease X Detection – Machine Learning Project

This project focuses on detecting Disease X based on physiological features using advanced supervised machine learning techniques.

## 📌 Project Summary
- **Samples**: ~110,000
- **Features**: 90 physiological measurements (X1–X90)
- **Target**: Binary classification – Infected (`1`) or Not Infected (`0`)
- **Data Format**: CSV with 90 predictors and a `Response` column

---

## 📁 Deliverables

### 📦 Deliverable 1 – SVM & XGBoost
- **Models Used**: 
  - Support Vector Machine (SVM)
  - XGBoost Classifier
- **Techniques**:
  - Standardization
  - Stratified K-Fold Cross Validation
- **Performance Metrics**:
  - Accuracy
  - Confusion Matrix
  - ROC-AUC Score
  - Classification Report

### 📦 Deliverable 2 – RNN & LightGBM
- **Models Used**: 
  - Recurrent Neural Network (RNN)
  - LightGBM
- **Techniques**:
  - Stratified K-Fold Cross Validation
- **Performance Metrics**:
  - Accuracy
  - Confusion Matrix
  - ROC-AUC Score
  - Sensitivity & Specificity
  - Classification Report

---

## 📈 Conclusion

- **Best Performing Model**: SVM (from Deliverable 1) demonstrated the highest accuracy and most balanced confusion matrix across folds.
- **Notable Consideration**: RNN showed strong performance and flexibility but at higher computational cost.

---

## 🔧 Getting Started

### 🐍 Requirements
Install dependencies using:

```bash
pip install -r requirements.txt
