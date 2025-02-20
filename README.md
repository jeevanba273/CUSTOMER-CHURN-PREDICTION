# 📉 Customer Churn Prediction 🚀

## 📌 Project Overview

Customer retention is a **major challenge** in the telecom industry. This project aims to **predict customer churn** using machine learning techniques, helping businesses identify **at-risk customers** and implement retention strategies.

By analyzing customer behavior and historical data, we develop predictive models to **understand why customers leave** and suggest data-driven actions to prevent churn.

---

## 📊 Dataset Overview

We use the **"WA_Fn-UseC_-Telco-Customer-Churn"** dataset, which contains details about telecom customers. The dataset consists of the following features:

- **🛠 Services**: Phone, multiple lines, internet, online security, online backup, device protection, tech support, streaming TV, and movies.
- **📜 Account Information**: Customer tenure, contract type, payment method, paperless billing, monthly charges, total charges.
- **👤 Demographics**: Gender, age range, presence of partners and dependents.
- **🎯 Target Variable**: **Churn** (Whether a customer left in the last month).

📌 The dataset is **structured** to allow **in-depth analysis** of customer behavior and churn patterns.

---

## 🛠 Tools & Technologies Used

| **Category**          | **Technology/Tools** |
|----------------------|---------------------|
| **Programming**       | Python  |
| **Data Processing**   | Pandas, NumPy |
| **Machine Learning**  | Scikit-Learn, XGBoost |
| **Visualization**     | Matplotlib, Seaborn 📊 |
| **Development**       | Jupyter Notebook 📓 |
| **Data Exploration**  | Microsoft Excel 📑 |

---

## 🚀 Implementation Steps

### 1️⃣ **Data Exploration**
- Loaded and analyzed the dataset.
- Identified missing values and handled data inconsistencies.
- Visualized key trends affecting customer retention.

### 2️⃣ **Data Preprocessing**
- Handled **missing values** and **outliers**.
- Encoded **categorical variables** for machine learning models.
- Scaled numerical features for better performance.

### 3️⃣ **Model Building**
- Implemented multiple machine learning models:
  - Logistic Regression
  - Decision Trees
  - Random Forest Classifier
  - XGBoost Classifier (Best Performing)
- Tuned hyperparameters to improve model performance.

### 4️⃣ **Model Evaluation**
- Used **accuracy, precision, recall, and F1-score** to evaluate models.
- Analyzed **feature importance** to determine the most significant factors affecting churn.

---

## 📊 Results & Insights

- The **XGBoost model** achieved the **best performance**, with high **accuracy and recall**.
- **Key churn factors** identified:
  - **Contract Type**: Customers with **monthly contracts** were more likely to leave.
  - **Monthly Charges**: Higher monthly charges correlated with increased churn.
  - **Tech Support & Online Security**: Customers **without** these services had higher churn rates.
- Suggested **retention strategies**:
  - **Encourage long-term contracts** with incentives.
  - **Offer personalized discounts** to high-churn-risk customers.
  - **Improve tech support & online security** services.

---

## 🏃 How to Run the Project

### **1️⃣ Clone the repository**
```bash
git clone https://github.com/jeevanba273/CUSTOMER-CHURN-PREDICTION.git


