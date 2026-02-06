# ❤️ Heart Disease Prediction System (Machine Learning)

## 📌 Project Overview
This project is a machine learning–based system that predicts the presence of heart disease using patient health data.  
The goal is to assist in early risk assessment by analyzing medical attributes and providing probability-based predictions.

---

## 🧠 Problem Statement
Heart disease is one of the leading causes of death worldwide.  
Early detection can significantly improve treatment outcomes.  
This project uses supervised machine learning techniques to predict whether a patient is at risk of heart disease.

---

## 📊 Dataset
- **Source:** UCI Heart Disease Dataset (via Kaggle)
- **Total records:** 920
- **Target variable:**  
  - `0` → No heart disease  
  - `1` → Heart disease present

### Key Features:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol
- Maximum heart rate
- Exercise-induced angina
- ST depression (`oldpeak`)
- Other clinical indicators

---

## ⚙️ Data Preprocessing
- Dropped irrelevant columns (`id`, `dataset`)
- Converted target variable into binary classification
- Handled missing values:
  - Numerical features → Median imputation
  - Categorical features → Mode imputation
- Applied One-Hot Encoding to categorical variables
- Performed train-test split (80% training, 20% testing)

---

## 🤖 Machine Learning Models Used

### 1️⃣ Logistic Regression (Baseline Model)
- Used as a benchmark model
- Achieved **80% accuracy**

### 2️⃣ Random Forest Classifier (Final Model)
- Captures non-linear relationships
- Reduced false negatives (important in healthcare)
- Achieved **87% accuracy**

---

## 📈 Model Performance (Random Forest)

- **Accuracy:** 87%
- **Precision (Disease):** 90%
- **Recall (Disease):** 88%
- **F1-Score:** 89%

The model demonstrates strong performance in identifying patients with heart disease, which is critical for medical decision support.

---

## 🔍 Feature Importance
Random Forest feature importance was analyzed to understand which medical attributes most influence predictions.  
This improves model interpretability and medical insight.

---

## 🧪 Sample Prediction
The model provides both:
- Binary prediction (Disease / No Disease)
- Probability-based confidence score

This allows classification into:
- High risk
- Moderate risk
- Low risk

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Joblib
- Jupyter Notebook / Google Colab

---

## 🚀 Future Improvements
- Hyperparameter tuning
- Flask web application for live predictions
- Model deployment on cloud platform
- Cross-validation for robustness

---

## 👤 Author
**Pawan Singh Rajput**  
- LinkedIn: https://www.linkedin.com/in/pawan-rajput-1913b12b1
