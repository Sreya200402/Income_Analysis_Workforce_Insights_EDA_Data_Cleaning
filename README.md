# 📊 Income Analysis & Workforce Insights (EDA + Data Cleaning)

## 🎯 Project Overview
This project focuses on **data cleaning and exploratory data analysis (EDA)** of the Adult Income Dataset to understand key factors influencing income levels.

The analysis uncovers patterns in demographic and employment-related features such as education, workclass, age, and working hours.

---

## 📂 Dataset
- **Source:** U.S. Census (Adult Income Dataset)  
- **Type:** Structured tabular data  
- **Objective:** Predict whether income exceeds $50K  

---

## 🧹 Data Cleaning
The dataset contained inconsistencies and missing values represented as `"?"`.

### Steps performed:
- Removed extra spaces from categorical columns  
- Converted `"?"` to NaN  
- Handled missing values using mode  
- Removed duplicate records  
- Standardized categorical data  

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis
- Income distribution  
- Workclass distribution  
- Age distribution  
- Education levels  

### 🔹 Bivariate Analysis
- Education vs Income  
- Workclass vs Income  
- Age vs Income  
- Working Hours vs Income  

### 🔹 Correlation Analysis
- Weak correlation among numerical features  
- Income influenced more by categorical variables  

### 🔹 Outlier Handling
- Detected using IQR method  
- Handled using clipping  

---

## 🔍 Key Insights
- Income distribution is highly imbalanced  
- Higher education increases likelihood of earning >50K  
- Private sector dominates employment  
- Experience (age) impacts income  
- Longer working hours are linked to higher income  

---

## 💼 Business Understanding
This analysis helps organizations:
- Understand workforce income distribution  
- Identify factors affecting earning potential  
- Support data-driven decision-making  

---

## 📊 Dashboard
An interactive Power BI dashboard was created to visualize:
- Income distribution  
- Education and workclass impact  
- Age and working hours patterns  
- Relationship between variables  

---

## 📄 Problem Statement
👉 [View Problem Statement](problem_statement.pdf)

---

## 📸 Dashboard Preview
![Dashboard](dashboard_image/dashboard.png)

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy)  
- Matplotlib & Seaborn  
- Power BI  

---

## 🚀 Future Scope
- Build machine learning model for income prediction  
- Feature engineering  
- Dashboard improvements  

---

## 👩‍💻 Author
Sreya
