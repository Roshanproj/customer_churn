# 📊 Customer Churn Analysis Project

## 📌 Project Overview

Customer churn is one of the most critical challenges faced by subscription-based and service-oriented businesses. Retaining existing customers is often more cost-effective than acquiring new ones.

This project focuses on analyzing customer behavior and predicting churn using data analytics, machine learning, SQL, and business intelligence tools.

The objective is to identify high-risk customers, understand churn drivers, and provide actionable insights to support data-driven retention strategies.

---

## 🎯 Project Objectives

* Analyze customer demographics, usage patterns, and billing information
* Identify key factors influencing customer churn
* Build and evaluate machine learning models for churn prediction
* Perform SQL-based business analysis
* Visualize insights using Power BI dashboards
* Estimate revenue at risk due to churn

---

## 📂 Dataset Description

* Dataset: Telco Customer Churn Dataset (Real-world dataset)
* Source: Public telecom customer records
* Records: Customer-level subscription data
* Target Variable: `Churn_Value` (0 = No, 1 = Yes)

### Key Features:

* Demographics: Gender, Senior Citizen, Partner, Dependents
* Services: Internet Service, Streaming, Tech Support, Phone Service
* Billing: Monthly Charges, Total Charges, Payment Method
* Contract: Contract Type, Tenure
* Engineered Features: Tenure Group, Auto Payment, High Monthly Charges

---

## 🛠️ Tools & Technologies Used

| Category        | Tools                                         |
| --------------- | --------------------------------------------- |
| Programming     | Python (Pandas, NumPy, Scikit-learn, XGBoost) |
| Database        | MySQL                                         |
| Visualization   | Power BI, Matplotlib                          |
| Environment     | Jupyter Notebook, MySQL Workbench             |
| Version Control | Git, GitHub                                   |

---

## 🔄 Project Workflow

### 1️⃣ Data Collection

* Loaded dataset from Excel/CSV
* Validated data quality and schema

### 2️⃣ Data Cleaning & Preprocessing (Python)

* Handled missing values
* Removed duplicates
* Converted data types
* Removed data leakage columns
* Encoded categorical variables
* Feature engineering

### 3️⃣ Exploratory Data Analysis (EDA)

* Churn distribution analysis
* Contract and tenure impact
* Payment method trends
* Monthly charges vs churn
* Customer segmentation

### 4️⃣ Feature Engineering

* Created tenure groups
* Generated binary indicators
* Created high-value customer flags
* Normalized numeric features

### 5️⃣ Machine Learning Modeling

* Train-test split with stratification
* Models implemented:

  * Random Forest Classifier
  * XGBoost Classifier
* Class imbalance handling
* Model evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
  * ROC-AUC

### 6️⃣ Model Selection & Deployment

* Compared Random Forest vs XGBoost
* Selected XGBoost based on recall and ROC-AUC
* Saved final model using Joblib
* Generated churn probabilities

### 7️⃣ SQL-Based Analysis (MySQL + Python)

* Imported cleaned dataset into MySQL
* Connected database using SQLAlchemy
* Performed analytical queries in Jupyter

Example SQL Analysis:

* Overall churn rate
* Churn by contract type
* Churn by tenure group
* Revenue at risk
* High-risk customer segments

### 8️⃣ Power BI Dashboard Development

* Connected Power BI to MySQL / CSV output
* Created interactive dashboards
* Designed KPI cards and visual analytics

---

## 🤖 Machine Learning Models

| Model         | Purpose                         |
| ------------- | ------------------------------- |
| Random Forest | Baseline ensemble model         |
| XGBoost       | Final selected predictive model |

### Model Evaluation Metrics

* Accuracy
* Precision
* Recall (Primary focus)
* F1 Score
* ROC-AUC

XGBoost was selected as the final model due to superior performance in identifying churn-prone customers.

---

## 📈 Power BI Dashboard

The Power BI dashboard provides interactive business insights including:

### Key Visuals:

* Overall Churn Rate
* Churn by Contract Type
* Churn by Tenure Group
* Churn by Payment Method
* Revenue at Risk
* High-Risk Customer Segments
* Monthly Charges vs Churn

### Dashboard Benefits:

* Enables management to monitor churn trends
* Supports targeted retention campaigns
* Helps prioritize high-value customers
* Improves decision-making

---

## 💡 Key Insights

* Month-to-month contracts show the highest churn rate
* Customers with high monthly charges are more likely to churn
* Short-tenure customers have higher churn probability
* Auto-payment users demonstrate lower churn rates
* Long-term contracts improve customer retention

---

## 📊 Business Impact

* Identified high-risk customer segments
* Estimated revenue loss due to churn
* Enabled proactive retention strategies
* Improved customer lifetime value management
* Supported data-driven marketing decisions

---

## 🚀 How to Run This Project

### 1️⃣ Clone Repository

```bash
git clone <repository_url>
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

### 4️⃣ Database Setup

* Import dataset into MySQL
* Update database credentials
* Connect using SQLAlchemy

### 5️⃣ Power BI

* Open `.pbix` file
* Refresh data source
* Explore dashboard

---

## 📌 Future Enhancements

* Hyperparameter tuning
* Deep learning models (ANN)
* Real-time churn prediction API
* Cloud deployment
* Automated reporting system

---

## 👤 Author

**Roshan Zameer**
Aspiring Data Analyst / Data Scientist

---

## 📬 Contact

For queries or collaboration:

* GitHub: <your_github_profile>
* LinkedIn: <your_linkedin_profile>

---

⭐ If you found this project useful, feel free to star the repository!
