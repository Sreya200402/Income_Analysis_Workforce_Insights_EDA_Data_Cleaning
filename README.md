# 📊 Income Analysis & Workforce Insights (EDA + Data Cleaning)

## 🚀 Project Highlights
- End-to-end data analysis project: Data Cleaning → EDA → Dashboarding  
- Processed ~32,000+ records to uncover income-driving factors  
- Built an interactive Power BI dashboard with dynamic filters and KPIs  
- Identified key drivers of high income: education, age, and working hours  
- Translated raw data into actionable business insights  

---

## 🎯 Project Overview
This project analyzes workforce demographics and income distribution using the Adult Income dataset. It focuses on identifying key factors that influence whether an individual earns more than $50K annually.

The project follows an end-to-end analytics workflow including data cleaning, exploratory analysis, and dashboard development to generate actionable insights.

---

## 📂 Dataset
- **Source:** U.S. Census (Adult Income Dataset)  
- **Type:** Structured tabular data  
- **Size:** ~32,000 records, 15+ features  
- **Objective:** Predict whether income exceeds $50K  

---

## 🧹 Data Cleaning
The dataset contained inconsistencies and missing values represented as `"?"`, which could impact analysis accuracy.

### Steps performed:
- Removed extra spaces to ensure consistency in categorical data  
- Replaced `"?"` with NaN and handled missing values using mode  
- Removed duplicate records to avoid bias  
- Standardized categorical values for accurate grouping  

👉 Ensured high data quality and reliability for analysis  

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis
Analyzed distribution of individual variables to understand data spread:
- Income distribution (class imbalance observed)  
- Age distribution (majority between 25–50)  
- Workclass and education frequency  

### 🔹 Bivariate Analysis
Examined relationships between features and income:
- Higher education strongly correlates with >50K income  
- Private sector employees dominate both income groups  
- Longer working hours increase likelihood of higher income  

### 🔹 Correlation Analysis
- Weak correlation among numerical features  
- Income is primarily influenced by categorical variables  

### 🔹 Outlier Handling
- Identified using IQR method  
- Applied clipping to reduce skewness  

---

## 🔍 Key Insights
- Income distribution is imbalanced, with majority earning ≤50K  
- Individuals with higher education levels are significantly more likely to earn >50K  
- Working more than 40 hours/week increases probability of higher income  
- Age (experience) shows a positive relationship with income up to mid-career  
- Private sector dominates employment but does not guarantee higher income  

---

## 📌 Dashboard Features
- KPI cards for total population, average age, and income distribution  
- Interactive slicers for gender, education, and workclass  
- Visual comparison of income groups (>50K vs ≤50K)  
- Drill-down capability across demographic segments  
- Dynamic filtering for better user exploration  

---

## 💡 Business Impact
- Helps organizations identify key factors influencing employee income  
- Supports workforce segmentation and compensation analysis  
- Enables data-driven decision-making for HR and policy planning  
- Provides insights for targeting high-value workforce segments  

---

## 📊 Dashboard
An interactive Power BI dashboard was created to visualize:
- Income distribution  
- Education and workclass impact  
- Age and working hours patterns  
- Relationship between variables  

---

## 📊 Dashboard

👉 [View Dashboard](Dashboard/dashboard.pdf)

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy)  
- Matplotlib & Seaborn  
- Power BI  

---

## ▶️ How to Run the Project
1. Clone the repository  
2. Run the Jupyter Notebook for data cleaning and EDA  
3. Open the Power BI (.pbix) file to explore the dashboard  

---

## 🚀 Future Enhancements
- Build a machine learning model for income prediction  
- Perform feature engineering for improved insights  
- Enhance dashboard with advanced DAX and drill-through features  

---
