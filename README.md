# 🧠 Customer Churn Prediction App

A complete machine learning project designed to **predict customer churn in e-commerce platforms** and explain model behavior using SHAP interpretability techniques.

---

## 📘 Overview

Customer churn (attrition) occurs when users stop engaging or purchasing from an e-commerce platform. Retaining customers is far more cost-effective than acquiring new ones.  
This project aims to identify at-risk customers using **machine learning models**, helping businesses implement timely retention strategies such as personalized offers or engagement campaigns.

The project pipeline includes:

- **Data Preprocessing**: handling missing values, encoding categorical variables, removing outliers  
- **Exploratory Data Analysis (EDA)**: visualization and correlation analysis  
- **Modeling**: Decision Tree, Random Forest, and XGBoost  
- **Evaluation**: Accuracy, F1-score, Precision, Recall, Jaccard Index, ROC Curve, and Confusion Matrix  
- **Explainability**: Feature importance analysis using SHAP  

---

## 🧩 Dataset

**File:** `E comm.xlsx`  
This dataset (provided by the supervisor) includes customer demographics, order patterns, app usage, and churn information.  

### Key Columns:
| Feature | Description |
|----------|-------------|
| `Tenure` | Duration of customer relationship (months) |
| `PreferredLoginDevice` | Device used to access app (Mobile/Desktop) |
| `CityTier` | Customer’s city classification (1, 2, or 3) |
| `WarehouseToHome` | Distance (km) |
| `PreferredPaymentMode` | UPI, COD, Credit Card, etc. |
| `Gender` | Male/Female |
| `OrderCount` | Total number of orders made |
| `DaySinceLastOrder` | Recency of customer activity |
| `CashbackAmount` | Average cashback received |
| `Churn` | Target variable (1 = churned, 0 = active) |

---

## 🧮 Technologies Used

- **Programming Language**: Python 3.x  
- **Data Handling**: pandas, numpy  
- **Visualization**: matplotlib, seaborn  
- **Modeling**: scikit-learn, xgboost  
- **Model Explainability**: shap  
- **Utilities**: GridSearchCV, warnings, preprocessing  

