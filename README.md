# Customer-Purchase-Behavior-Analysis
# 📊 Customer Purchase Behavior Analysis

---

## 🧠 Problem Statement

E-commerce platforms often face **low conversion rates**, where many users browse products but do not complete purchases.

This project aims to analyze **customer behavior** and identify key factors that influence purchase decisions, helping businesses improve their conversion funnel.

---

## 🎯 Objectives

* Understand user behavior during sessions
* Identify factors influencing purchases
* Analyze drop-offs in the conversion funnel
* Provide actionable business recommendations

---

## 📁 Dataset Overview

The dataset includes session-level customer behavior with the following features:

* SessionID
* UserID
* PageType
* DeviceType
* Country
* ReferralSource
* TimeOnPage_seconds
* ItemsInCart
* Purchased (Target Variable)

---

## ⚙️ Project Workflow

### 🔹 1. Data Cleaning

* Handled missing values using appropriate techniques
* Removed duplicates
* Fixed inconsistent values (e.g., invalid session time)
* Treated outliers using boxplot/IQR method

---

### 🔹 2. Feature Engineering

* Created engagement-related metrics
* Identified cart activity as a strong indicator of purchase intent

---

### 🔹 3. Exploratory Data Analysis (EDA)

* Purchase vs Non-purchase comparison
* Distribution of session time and user activity
* Funnel analysis: View → Cart → Purchase
* Correlation analysis

---



## 📊 Key Insights

* 🔥 A large proportion of users do not complete purchases, indicating a **low conversion rate**

* 🔥 High session time does not always lead to purchase, suggesting **browsing behavior without intent**

* 🔥 Users who add items to cart are significantly more likely to purchase, showing **strong buying intent**

* 🔥 Major drop-off occurs between **product view and cart stage**, highlighting a critical conversion gap

---

## 💡 Business Recommendations

* ✅ Improve **Call-to-Action (CTA)** buttons like “Add to Cart”

* ✅ Provide **personalized recommendations** to increase engagement

* ✅ Optimize **checkout process** to reduce cart abandonment

* ✅ Target high-intent users (cart activity) with remarketing strategies

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas, NumPy** (Data Processing)
* **Matplotlib, Seaborn** (Visualization)
* **Jupyter Notebook** (Analysis)


---

## 📈 Conclusion

This project highlights how user behavior impacts purchase decisions and identifies key areas to improve conversion rates. The insights can help businesses make data-driven decisions to enhance user experience and increase revenue.

---

## 🚀 Future Scope

* Build machine learning models to predict purchase behavior
* Perform customer segmentation
* Implement real-time recommendation systems

---

