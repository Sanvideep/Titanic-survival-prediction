# 🛳️ Titanic Survival Prediction  
A complete end-to-end machine learning project predicting passenger survival on the RMS Titanic using Python, Pandas, Scikit-Learn, and Exploratory Data Analysis (EDA).

---

## 📌 Project Overview
This project builds a machine-learning model to predict whether a passenger survived the Titanic disaster based on demographic and ticket-related attributes.  
It follows a complete data-science workflow:

- Data cleaning  
- Handling missing values  
- Feature engineering  
- One-hot encoding  
- Exploratory Data Analysis (EDA)  
- Model training  
- Evaluation  
- Final prediction  

The notebook:  
`/titanic-survival-prediction.ipynb`  
contains the entire workflow.

---


---

## 🧠 Key Steps in This Project

### 1️⃣ Data Loading & Inspection
- Load the dataset using `pandas.read_csv()`
- Inspect data types, missing values, and structure
- Understand feature importance (e.g., Sex, Age, Pclass)

### 2️⃣ Data Cleaning & Missing Value Imputation
- Fill missing numerical features (Age, Fare) with median
- Fill missing categorical values (Embarked) with mode
- Drop columns with excessive missingness (Cabin), or extract useful info

### 3️⃣ Feature Engineering
- Convert categorical features to numeric using One-Hot Encoding  
  (Sex, Embarked, etc.)
- Optional derived features: FamilySize, IsAlone, Title extraction

### 4️⃣ Exploratory Data Analysis (EDA)
- Count plots, histograms, survival rate distributions
- Correlation heatmaps
- Analysis of categorical impacts (e.g., Sex vs Survived, Pclass vs Survived)

### 5️⃣ Model Training
- Train ML models such as:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting / XGBoost (optional)
- Use train-test split or cross-validation
- Evaluate using accuracy, confusion matrix, and classification metrics

### 6️⃣ Predictions & Output
- Generate predictions on test data  
- Prepare results CSV if submitting to Kaggle

---

## 🚀 Running the Project

### **Clone the repository**
```bash
git clone https://github.com/Sanvideep/Titanic-survival-prediction.git
cd Titanic-survival-prediction


