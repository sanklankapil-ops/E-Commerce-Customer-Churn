# 🧠 E-commerce Customer Churn Analysis and Prediction

An end-to-end Machine Learning project that predicts customer churn in an e-commerce platform using customer behaviour, purchase history, and engagement data. The project also includes an interactive CRM Dashboard built with Gradio for real-time customer churn prediction and analysis.

---

# 📌 Project Overview

Customer churn is one of the major challenges faced by e-commerce businesses. Identifying customers who are likely to leave helps companies improve customer retention and reduce revenue loss.

This project analyzes customer data, trains multiple machine learning models, compares their performance, and deploys the best-performing model through an interactive dashboard.

---

# 🚀 Project Workflow

## 1. Data Collection
- Imported customer dataset from Excel
- Loaded customer demographic and transaction data

## 2. Data Preprocessing
- Missing value handling
- Data cleaning
- Label Encoding
- Feature selection
- Train-Test Split

## 3. Exploratory Data Analysis (EDA)

Performed different visualizations to understand customer behaviour:

- Customer Churn Distribution
- Correlation Heatmap
- Histograms
- Count Plots
- Box Plots
- Confusion Matrix
- ROC Curve
- Feature Importance

---

# 🤖 Machine Learning Models

The following classification models were trained and compared:

- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier ✅

After performance comparison, **XGBoost** was selected as the final model because it achieved the best prediction performance.

---

# 📊 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Jaccard Score
- Confusion Matrix
- ROC Curve

## Final Model Accuracy

**XGBoost Accuracy: 98.13%**

---

# 🧩 Dataset

**Dataset File:** `E_comm.xlsx`

The dataset contains customer demographic information, shopping behaviour, application usage, payment preferences, order history, and customer engagement details.

## Features

| Feature | Description |
|----------|-------------|
| Tenure | Customer relationship duration |
| PreferredLoginDevice | Preferred login device |
| CityTier | Customer city category |
| WarehouseToHome | Distance from warehouse |
| PreferredPaymentMode | Preferred payment method |
| Gender | Customer gender |
| HourSpendOnApp | Daily time spent on app |
| NumberOfDeviceRegistered | Registered devices |
| PreferedOrderCat | Preferred order category |
| SatisfactionScore | Customer satisfaction rating |
| MaritalStatus | Customer marital status |
| NumberOfAddress | Saved addresses |
| Complain | Complaint status |
| OrderAmountHikeFromlastYear | Increase in yearly order amount |
| CouponUsed | Coupons used |
| OrderCount | Total orders |
| DaySinceLastOrder | Days since last order |
| CashbackAmount | Cashback received |
| Churn | Target Variable |

---

# 💻 CRM Dashboard

The project includes an interactive CRM Dashboard developed using **Gradio**.

### Dashboard Features

### 🔹 Predict Customer Churn
- Predict customer churn
- Display churn probability
- Display customer risk level
- Automatically generate Customer ID

### 🔹 Customer Database
- Store prediction records
- View all predicted customers

### 🔹 Search Customer
- Search customer details using Customer ID

### 🔹 Customer Filters
- High Risk Customers
- Medium Risk Customers
- Low Risk Customers
- Customers with Complaints
- Low Satisfaction Customers
- Newly Added Customers
- Today's Predictions

### 🔹 Records
- Training Dataset Records
- Predicted Customer Records

### 🔹 Graphs
- Customer-wise analysis
- Feature analysis
- Prediction insights

---

# 📈 Important Features Affecting Churn

The trained model identified the following features as highly influential:

- Tenure
- Satisfaction Score
- Complaint Status
- Cashback Amount
- Order Count
- Day Since Last Order
- Warehouse To Home Distance

---

# 🛠 Technologies Used

## Programming Language

- Python

## Libraries

- pandas
- numpy
- matplotlib
- scikit-learn
- xgboost
- gradio
- joblib

---

# 📂 Repository Structure

```
E-Commerce-Customer-Churn/
│
├── E_comm.xlsx
├── Untitled6.ipynb
├── README.md
├── Model Files
├── Label Encoder Files
├── Customer Database
└── Dashboard
```

---

# 🎯 Future Improvements

- Cloud Deployment
- User Authentication
- Real-Time Database Integration
- Customer Retention Recommendation System
- Email Alerts for High-Risk Customers

---

# 👨‍💻 Author

**Kapil Dev Singh**

B.Tech (Computer Science & Engineering)

Machine Learning | Python | SQL

LinkedIn:
https://www.linkedin.com/in/kapil-dev-singh-68731435b

GitHub:
https://github.com/sanklankapil-ops
