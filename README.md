📘 Loan Approval Prediction using Machine Learning

This project predicts whether a loan application should be **approved** or **rejected** based on applicant data using different Machine Learning models.
The notebook **loan.ipynb** covers everything from data cleaning to model evaluation.

---

## 🚀 Project Overview

Loan approval is one of the most important decisions for banks and financial institutions.
Using machine learning, we can **automatically predict** loan eligibility with high accuracy.

This project includes:

* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training
* Model Comparison
* Final Prediction

---

## 🎯 Objectives

✔ Preprocess loan dataset
✔ Handle missing values & noisy data
✔ Explore patterns using EDA
✔ Apply multiple ML classification algorithms
✔ Compare accuracy & performance metrics
✔ Build a reliable model for predicting loan approval

---

## 📂 Dataset Description

Common features used in loan predictions:

| Feature               | Description                |
| --------------------- | -------------------------- |
| **Gender**            | Male/Female                |
| **Married**           | Yes/No                     |
| **Dependents**        | Number of dependents       |
| **Education**         | Graduate/Not Graduate      |
| **Self_Employed**     | Yes/No                     |
| **ApplicantIncome**   | Income of the applicant    |
| **CoapplicantIncome** | Income of the co-applicant |
| **LoanAmount**        | Requested loan amount      |
| **Loan_Amount_Term**  | Duration of loan           |
| **Credit_History**    | Past credit record (0/1)   |
| **Property_Area**     | Urban/Rural/Semi-urban     |
| **Loan_Status**       | Target variable (Y/N)      |

---

## 🧼 Data Preprocessing

✔ Handling missing values
✔ Label Encoding
✔ Outlier removal
✔ Feature selection
✔ Train-Test split

---

## 📊 Exploratory Data Analysis (EDA)

Includes visualisation and insights:

* Distribution of income
* Loan amount analysis
* Relationship between credit history & loan status
* Correlation heatmap
* Loan approval trends

---

## 🤖 Machine Learning Models Used

The notebook compares multiple models such as:

* **Logistic Regression**
* **Decision Tree Classifier**
* **Random Forest Classifier**
* **Support Vector Machine (SVM)**
* **K-Nearest Neighbors (KNN)**

Each model is evaluated using:

✔ Accuracy
✔ Precision
✔ Recall
✔ Confusion Matrix
✔ Classification Report

---

## 🏆 Best Model

After evaluation, the model with the highest accuracy & best metrics is selected as the **Final Model**.
(Your notebook identifies the winner automatically.)

---

## 📈 Results Summary

* Achieved strong prediction accuracy
* Credit History was one of the most important factors
* Ensemble models (like Random Forest) performed best
* Clean data significantly improved model performance

---

## 🔧 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/your-repository.git
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Open the Notebook

```bash
jupyter notebook loan.ipynb
```

---

## 🗂 Project Structure

```
.
├── loan.ipynb
├── README.md
└── data/
    └── loan.csv (optional)
```

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
```

---

## ✨ Future Improvements

* Hyperparameter tuning
* Deployment using Flask/Streamlit
* Adding more features
* Using advanced models (XGBoost, LightGBM)

---

## 👨‍💻 Author

**Satvendra Singh**

Machine Learning & Data Science Enthusiast

