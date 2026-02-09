# Customer Churn Prediction

## 📌 Project Overview
This project focuses on predicting customer churn using supervised machine learning techniques.  
The goal is to identify customers who are likely to leave a telecom service provider based on their usage patterns and subscription details.

Understanding churn helps businesses take proactive retention actions and reduce customer loss.

---

## 📊 Dataset
- **Dataset Name:** Telco Customer Churn
- **Source:** Kaggle
- **Type:** Structured tabular data
- **Target Variable:** `Churn` (Yes / No)

### Key Features:
- tenure
- MonthlyCharges
- TotalCharges
- Contract
- InternetService
- PaymentMethod
- OnlineSecurity
- TechSupport

---

## ⚙️ Data Preprocessing
The following preprocessing steps were performed:
- Checked and handled missing values
- Converted `TotalCharges` from object to numeric
- Encoded the target variable (`Churn`) into binary form
- One-hot encoded categorical features
- Dropped non-informative identifier columns
- Scaled numerical features using `StandardScaler`

---

## 🤖 Machine Learning Model
- **Algorithm Used:** Logistic Regression
- **Reason:** Simple, interpretable, and well-suited for binary classification problems like churn prediction
- **Train-Test Split:** 80% training, 20% testing

---

## 📈 Model Evaluation
The model was evaluated using multiple metrics:

- **Accuracy:** ~79%
- **Confusion Matrix**
- **Precision, Recall, and F1-score**

### Key Observation:
- The model performs well in identifying non-churn customers
- Recall for churned customers is moderate, which is common in churn prediction problems
- Recall is prioritized since missing a churned customer is more costly than a false alarm

---

## 🔍 Key Insights
- Customers with **month-to-month contracts** are more likely to churn
- **Higher monthly charges** increase churn probability
- Customers with **shorter tenure** show a higher risk of churning

These insights can help businesses design targeted retention strategies.

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📎 Author
This project was created as a hands-on machine learning exercise to understand real-world customer churn prediction and business-focused model evaluation.
