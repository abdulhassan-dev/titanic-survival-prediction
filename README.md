# 🚢 Titanic Survival Prediction

This project is a classic binary classification task based on the Titanic dataset provided by Kaggle. The objective is to predict whether a passenger survived the Titanic shipwreck using key attributes like age, sex, class, fare, and more.

---

## 📊 Problem Statement

The Titanic dataset is a well-known challenge for beginners in machine learning. It involves:

- Cleaning and preprocessing raw passenger data  
- Performing exploratory data analysis (EDA)  
- Building a machine learning model to classify survival outcomes  

---

## 🧠 Techniques Used

- Data Cleaning & Missing Value Imputation  
- Feature Engineering (e.g., Title extraction, family size)  
- Exploratory Data Analysis (EDA)  
- Data Visualization (Seaborn, Matplotlib)  
- Model Building with Scikit-learn  
- Model Evaluation (Accuracy, Confusion Matrix, Cross-validation)  

---

## 🗂️ Project Structure & 🧰 Tools & Libraries

- **data/**  
  ├── train.csv  
  └── test.csv  

- **notebooks/**  
  └── titanic_eda_modeling.ipynb  

- **models/**  
  └── titanic_model.pkl  

- **results/**  
  ├── evaluation_metrics.png  
  └── submission.csv  

- **README.md**

**Tools & Libraries**:  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📈 Model Overview

The final model was trained using a **Random Forest Classifier** after tuning and feature selection. Achieved:

- ✅ ~80% accuracy on the validation set  
- ✅ ~77–78% accuracy on the Kaggle public leaderboard  

---

## 🧪 Key Features Engineered

- 🧑‍✈️ Title extraction from name (Mr, Miss, etc.)  
- 👨‍👩‍👧‍👦 Family size from SibSp + Parch  
- 👤 IsAlone flag  
- 🌍 Categorical encoding for Embarked, Sex  
- 💰 Fare and Age binning  

---

## 👥 Team

Built by **Abdul Hassan** as part of a personal learning and model deployment initiative in machine learning and Kaggle challenges.

---

> 🚀 *More features & deployment version (Streamlit/Flask) coming soon!*
