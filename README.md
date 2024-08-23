# Customer Churn Prediction

## Project Overview

This project involves analyzing customer data to predict churn behavior for a telecom company. The primary goal is to develop predictive models that can identify customers at risk of leaving, thereby enabling targeted retention strategies.

## Dataset

The project utilizes the "WA_Fn-UseC_-Telco-Customer-Churn" dataset, which contains customer information with the following features:

- **Services**: Phone, multiple lines, internet, online security, online backup, device protection, tech support, streaming TV, and movies.
- **Account Information**: Duration as a customer, contract type, payment method, paperless billing, monthly charges, and total charges.
- **Demographics**: Gender, age range, and presence of partners and dependents.
- **Target Variable**: Churn (indicating whether a customer has left within the last month).

## Tools and Technologies

- **Programming Language**: Python
- **Libraries**: Pandas, Scikit-Learn, Matplotlib, Seaborn
- **Development Environment**: Jupyter Notebook
- **Data Analysis**: Microsoft Excel

## Files

- **Dataset**: WA_Fn-UseC_-Telco-Customer-Churn.csv
- **Jupyter Notebook**: Customer_Churn_Prediction.ipynb
- **Excel File**: Data_Exploration.xlsx

## Implementation

1. **Data Exploration**: Analyzed the dataset to understand customer attributes and the distribution of the target variable.
2. **Data Preprocessing**: Cleaned and prepared the data for modeling, including handling missing values and encoding categorical variables.
3. **Model Building**: Implemented various machine learning models to predict customer churn, including logistic regression, decision trees, and random forests.
4. **Evaluation**: Assessed model performance using metrics such as accuracy, precision, recall, and F1 score.

## Results

The project demonstrated the effectiveness of machine learning techniques in predicting customer churn. The models provided insights into the factors contributing to customer attrition and suggested strategies for improving retention.

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Customer_Churn_Prediction.ipynb
   ```

## Acknowledgements

- Dataset source: IBM Sample Data Sets
- Tools and libraries: Python, Pandas, Scikit-Learn, Jupyter Notebook

---
