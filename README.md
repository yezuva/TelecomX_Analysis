# 📊 Telecom X – Customer Churn Analysis

## 🧩 Project Overview

This project aims to analyze and understand the key factors driving customer churn at **Telecom X**, a telecommunications company facing high cancellation rates. The insights gathered here will support the Data Science team in building predictive models and creating strategies to improve customer retention.

Data was provided via a JSON API and includes customer demographics, service types, payment information, and churn status.

---

## 📂 Dataset

The dataset is sourced from a JSON file available in the repository:
- `TelecomX_Data.json` – Contains raw customer data.
- `TelecomX_diccionario.md` – Contains the data dictionary.
- `TelecomX_Churn_Analysis_(1).ipynb` – Jupyter Notebook with complete ETL, EDA, and visualization.

Each record includes:
- Customer demographics (gender, senior status, dependents)
- Services (Internet, phone, online backup, etc.)
- Account information (contract type, charges, payment method)
- Churn status (Yes/No)

---

## ⚙️ ETL Pipeline

The notebook follows a clean ETL process:
1. **Extraction** – Data is loaded directly from the JSON file.
2. **Transformation** – Normalization of nested fields, data type conversions, handling of missing values.
3. **Loading** – Transformed data is stored in a Pandas DataFrame and used for analysis and visualization.

---

## 🔎 Exploratory Data Analysis (EDA)

Key analyses included:

### 1. Demographic Insights
- Churn distribution by gender, senior citizen status, partner, and dependents.

### 2. Service Usage
- Churn comparison by Internet service type and additional services (OnlineSecurity, TechSupport, etc.).

### 3. Tenure & Charges
- Visualizations of tenure and monthly charges vs. churn status.

### 4. Payment Method Impact
- Distribution of churn across payment methods.

### 5. Correlation Heatmap
- Relationships between numeric variables and churn.

---

## 📈 Visualizations

All visualizations are included in the report. Examples:
- Churn by contract type.
- Churn rate by additional services.
- Heatmap of correlations.
- Top factors influencing churn (for future modeling).

---

## ✅ Conclusions

- **Short-term contracts** (month-to-month) show the highest churn rates.
- Customers with **no additional services** (e.g., online security or tech support) are more likely to churn.
- **Electronic check** is the payment method with the highest churn.
- **Tenure** has a strong inverse relationship with churn: the shorter the tenure, the higher the churn.
- **Senior citizens** and **customers without dependents** have slightly higher churn rates.

---

## 💡 Recommendations

- **Promote long-term contracts** through incentives or discounts.
- **Bundle additional services** (e.g., online security, tech support) to increase customer stickiness.
- **Monitor and support new customers** within the first few months.
- **Encourage paperless billing and modern payment methods** to improve retention.

---

## 📑 Report & Notebook

- `TelecomX_Churn_Analysis_Report_EN.pdf`: Final report with visualizations and insights.
- `TelecomX_Churn_Analysis_(1).ipynb`: Jupyter Notebook with full code and analysis.

---

## 🧠 Next Steps

- Build predictive models using Logistic Regression or Random Forest.
- Implement a customer segmentation strategy.
- Develop a churn prevention dashboard for business teams.

---

## 👤 Author

Prepared by **Yeikol Alberto Zúñiga Vargas**  
For **Telecom X – Data Science Team Challenge**  
August 2025

---

