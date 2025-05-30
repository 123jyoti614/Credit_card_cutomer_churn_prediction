
# 💳 Credit Card Customer Churn Prediction

This project focuses on predicting customer churn for a bank's credit card services using machine learning techniques. Churn prediction is crucial for customer retention and profitability in the financial sector. By analyzing customer behavior and demographics, this project helps identify customers who are likely to leave the service.

---

## 📌 Problem Statement

Customer churn is a key business challenge in the banking domain. Identifying potential churners can help the company take proactive measures to retain them. The goal is to build a predictive model that accurately classifies whether a customer will churn or not.

---

## 📂 Files and Structure


---

## 📊 Dataset

- **Source**: [Kaggle - Credit Card Customers](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)
- **Target Variable**: `Attrition_Flag` — Indicates whether the customer has churned.

### Key Features:
| Feature | Description |
|--------|-------------|
| Customer_Age | Age of the customer |
| Gender | Gender of the customer |
| Dependent_count | Number of dependents |
| Education_Level | Education background |
| Marital_Status | Marital status |
| Income_Category | Income category of customer |
| Credit_Limit | Credit limit on the card |
| Total_Revolving_Bal | Revolving balance on the card |
| Total_Trans_Amt | Total transaction amount in last 12 months |
| Total_Trans_Ct | Number of transactions in last 12 months |
| Avg_Utilization_Ratio | Utilization ratio of the credit limit |

---

## 🧠 Models Used

The following machine learning models were implemented and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier
- K-Nearest Neighbors (KNN)

---

## ⚙️ Methodology

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
   - Balancing the dataset

2. **Exploratory Data Analysis**
   - Visualizing distributions
   - Analyzing correlation between features
   - Identifying feature importance

3. **Model Training and Evaluation**
   - Splitting the data (train/test)
   - Evaluating models using:
     - Accuracy
     - Precision
     - Recall
     - F1 Score
     - ROC-AUC

---

## 📈 Results

- XGBoost and Random Forest delivered the highest performance.
- Features like `Total_Trans_Ct`, `Total_Trans_Amt`, and `Avg_Utilization_Ratio` had the greatest impact on churn prediction.
- Class imbalance was handled to improve recall on minority (churned) class.

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/credit-card-churn-prediction.git
   cd credit-card-churn-prediction
