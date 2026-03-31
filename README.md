

# 📊 Customer Shopping Behavior Analysis

## 🔍 Project Overview

This project analyzes customer shopping behavior using a dataset of **3,900 transactions**. The goal is to uncover insights related to customer spending patterns, product preferences, and business performance.

The analysis helps in understanding how factors like **age, gender, subscription status, discounts, and purchase history** influence customer decisions.

---

## 📁 Dataset Information

* **Total Records:** 3,900
* **Total Features:** 18

### Key Columns:

* Customer Details → Age, Gender, Location
* Purchase Info → Item Purchased, Category, Purchase Amount
* Behavior → Previous Purchases, Frequency of Purchases
* Business Factors → Discount Applied, Shipping Type
* Feedback → Review Rating

---

## 🛠️ Tools & Technologies

* **Python (Pandas, NumPy)** → Data Cleaning & Preprocessing
* **SQL (PostgreSQL/MySQL)** → Data Analysis
* **Power BI** → Data Visualization & Dashboard

---

## ⚙️ Data Preprocessing

* Handled missing values in **Review Rating** using median (category-wise)
* Renamed columns to **snake_case format**
* Created new features:

  * `age_group`
  * `purchase_frequency_days`
* Cleaned dataset exported as CSV

---

## 📊 Key Analysis Performed

* Revenue analysis by gender
* High-spending customers using discounts
* Top-rated products
* Shipping type vs purchase behavior
* Subscribers vs non-subscribers comparison
* Discount-dependent products
* Customer segmentation (New, Returning, Loyal)
* Top products per category
* Repeat buyers vs subscription behavior
* Revenue contribution by age group

---

## 📈 Dashboard

An interactive dashboard was built in **Power BI** to visualize:

* Total Customers
* Average Purchase Amount
* Revenue by Category
* Sales by Age Group
* Subscription Distribution

---

## 💡 Key Insights

* Male customers contribute higher revenue
* Loyal customers dominate the dataset
* Express shipping users tend to spend more
* Some products heavily rely on discounts
* Repeat buyers are more likely to subscribe

---

## 🚀 Business Recommendations

* Improve subscription benefits
* Focus on loyal customers with rewards
* Optimize discount strategies
* Promote top-rated products
* Target high-revenue age groups

---

## 📌 Conclusion

This project demonstrates how data analytics can be used to extract meaningful insights from customer data and support better business decision-making.

---

## 📂 Project Structure

```
├── data/
│   └── processed_customer_shopping_behavior.csv
├── notebooks/
│   └── data_analysis.ipynb
├── sql/
│   └── queries.sql
├── dashboard/
│   └── powerbi_dashboard.pbix
└── README.md
```

---

## ⭐ Author

**MD SHADAB ALAM**

