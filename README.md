# 🔬 Breast Cancer Prediction with Machine Learning

A simple yet powerful project to predict whether a breast tumor is malignant or benign using real medical data and machine learning models.

## 📊 Dataset
- Source: `sklearn.datasets.load_breast_cancer`
- 569 samples × 30 features (radius, texture, perimeter, etc.)
- Labels: 0 = Malignant, 1 = Benign

## 🧠 Models Used
- Logistic Regression ✅ (Best performance)
- Random Forest
- SVM
- XGBoost

## 🎯 Best Result
- Logistic Regression
  - Accuracy: 97.3%
  - Precision: 97.2%
  - Recall: 98.6%

## 💾 Files Included
- `notebook.ipynb`: full training & evaluation code
- `app.py`: Streamlit app for predictions
- `logistic_model.pkl` + `scaler.pkl`: trained model and scaler
- `example_prediction.py`: test prediction on new patient data

## 🚀 How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
