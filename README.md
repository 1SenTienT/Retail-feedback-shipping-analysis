# **Retail Customer Insights & Shipping Feedback Analysis**

*End-to-End Data Analytics & Machine Learning Project*

## 📌 **Project Overview**

This project explores customer behavior in a large retail dataset (300k+ records) to understand how **demographics**, **purchase patterns**, and **shipping methods** influence spending and customer satisfaction.

The goal is to generate **actionable insights** retailers can use to improve marketing, product targeting, and shipping performance.

The work includes **data cleaning, EDA, statistical testing, predictive modeling, and business insights**—all aligned with real industry analytics workflows.

---

## 🎯 **Objectives**

This project answers three key business questions:

### **1. Age vs. Purchase Amount**

Do age groups spend differently on highly rated products?

### **2. Gender vs. Purchasing Behavior**

Do males and females differ in spending, product categories, and brand choices?

### **3. Shipping Method vs. Customer Feedback**

Does Same-Day shipping increase customer satisfaction?

---

## 🧰 **Technologies Used**

* Python (Pandas, NumPy, Scikit-Learn, XGBoost)
* Statistical Tests (T-Test, Chi-Square, ANOVA, Tukey HSD)
* Visualization (Matplotlib, Seaborn)
* Jupyter Notebook
* Excel (initial cleaning)

---

## 🔍 **Project Scope**

### **1. Data Cleaning**

* Removed duplicates and handled missing values
* Standardized demographics, categories, ratings, and shipping fields
* Created derived variables (Age Groups, Rating Flags, Interaction Features)

### **2. Exploratory Data Analysis**

* Customer demographics distribution
* Spending patterns by age and gender
* Feedback trends by shipping method
* Most purchased categories and brands
* Visualizations include bar charts, count plots, heatmaps, and regression plots

---

## 📊 **Key Hypotheses & Findings**

### **Hypothesis 1: Age Influences Purchase Amount of Highly Rated Products**

Methods:

* Chi-Square Test
* Decision Tree Regression
* Random Forest Regression

Findings:

* Older customers (46–65) prefer **Home Decor** and **Food**, especially highly rated items
* Younger customers (18–35) prefer **Electronics** and **Clothing**, influenced by social media and promotions
* Age + Product Category are strong predictors of purchase amount

Business Insight:
Retailers should target younger groups with trend-driven campaigns and promote high-rated quality products to older groups.

---

### **Hypothesis 2: Gender Influences Purchasing Behavior**

Methods:

* T-Test on spending
* Chi-Square on product category & brand
* Linear Regression
* Classification Model (Gender Prediction)

Findings:

* Males and females differ significantly in product category and brand preference
* Gender impacts total spending and choice patterns
* Product category is one of the strongest predictors

Business Insight:
Marketing strategies should segment customers by gender preference to increase relevance and conversion.

---

### **Hypothesis 3: Shipping Method Influences Customer Feedback**

Methods:

* ANOVA
* Tukey HSD
* Chi-Square Test
* XGBoost Classifier

Findings:

* Same-Day shipping receives significantly higher “Excellent” feedback
* Standard shipping correlates with more neutral/negative feedback
* Strongest impact seen in **Electronics** and **Clothing**

Business Insight:
Offering Same-Day delivery for time-sensitive categories can greatly increase customer satisfaction.

---

## 🤖 **Machine Learning Models Implemented**

* **Decision Tree Regression** → Identified key predictors of purchase amount
* **Random Forest Regression** → Improved robustness in feature importance ranking
* **XGBoost Classifier** → Predicted “Excellent” feedback accurately
* **Linear Regression** → Quantified gender and category effects on spending

Each model supports operational decision-making in customer targeting and logistics optimization.

---

## 🧠 **Why This Project Matters**

This analysis provides retailers with:

* Better customer segmentation
* Data-driven product targeting
* Optimization opportunities for shipping operations
* Insights into how demographics shape preferences
* Evidence-based strategies for boosting satisfaction and revenue

---

## 🚀 **Future Enhancements**

* Customer lifetime value (CLV) modeling
* RFM segmentation or clustering
* Power BI dashboard for executives
* A/B testing on shipping incentives

---

## 👤 **Author**

**Samuel Otono**
Data & Analytics | Machine Learning | Business Insights

---


