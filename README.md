# Diabetes Risk Prediction ML

**Description:**  
Diabetes risk classification using machine learning models in Python. This project predicts whether a patient has diabetes based on health-related features using Logistic Regression.

---

## 📊 Dataset
- Source: [Pima Indians Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- Features include: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age
- Target: `Outcome` (0 = No Diabetes, 1 = Diabetes)

---

## 🧪 Model Used
- Logistic Regression

---

## 🔧 Preprocessing
- Handle missing or zero values
- Feature scaling using StandardScaler
- Train-test split
- Optional threshold tuning for better precision/recall balance

---

## 📈 Evaluation Metrics
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC Curve and AUC

---

## 📌 How to Run
1. Clone the repository:
```bash
git clone https://github.com/seleenerk/Diabetes-Risk-Prediction.git
pip install -r requirements.txt
jupyter notebook notebooks/diabetes.ipynb
