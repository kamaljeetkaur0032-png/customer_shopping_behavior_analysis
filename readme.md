# Clothing Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes **customer shopping behavior in the clothing industry** using Python, SQL, and Power BI.

The goal is to understand customer purchasing patterns, spending behavior, discounts, product categories, reviews, subscriptions, and purchasing frequency.

The project follows a complete data analysis workflow:

**Raw Data → Python Data Cleaning → SQL Analysis → Power BI Dashboard**

---

## 🎯 Objectives

* Understand customer purchasing behavior
* Analyze purchase amounts and spending patterns
* Identify popular product categories and items
* Analyze customer age groups
* Study discount and promotional behavior
* Analyze customer reviews and ratings
* Understand purchase frequency
* Identify customer segments and subscription behavior
* Create an interactive Power BI dashboard

---

## 🛠️ Tools & Technologies

* **Python**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
* **SQL**

  * MySQL
* **Power BI**

  * Data visualization
  * DAX
  * Interactive dashboard
* **Jupyter Notebook / Google Colab**
* **Git & GitHub**

---

## 📂 Project Structure

```text
clothing_customer/
│
├── data/
│   ├── customer_shopping_behavior.csv
│   └── customer.csv
│
├── python/
│   └── customer_shopping_behavior.ipynb
│
├── sql/
│   ├── Customer_Behavior_Schema.sql
│   └── Customer_Behavior_Solutions.sql
│
├── powerbi/
│   └── Customer_Shopping_Behavior.pbix
│
├── documentation/
│   └── Customer_Shopping_Behavior_Report.docx
│
└── README.md
```

---

## 🐍 Python Data Cleaning

Python was used to inspect and prepare the raw dataset for analysis.

### Data Preparation Steps

* Loaded the raw CSV using Pandas
* Checked dataset information and data types
* Generated descriptive statistics
* Checked for missing values
* Filled missing **Review Rating** values using the median rating within each category
* Standardized column names
* Renamed `purchase_amount_(usd)` to `purchase_amount`
* Created an **age_group** column
* Converted purchase frequency into the number of days
* Compared `discount_applied` and `promo_code_used`
* Removed the redundant `promo_code_used` column
* Exported the cleaned dataset as `customer.csv`

---

## 🗄️ SQL Analysis

SQL is used to answer business questions related to customer shopping behavior.

Examples of analysis include:

* Customer spending patterns
* Subscription behavior
* Discount usage
* Customer segmentation
* Product/category performance
* Purchase frequency
* Customer purchasing behavior

---

## 📊 Power BI Dashboard

Power BI is used to create an interactive dashboard for analyzing customer behavior.

The dashboard focuses on:

* Total Customers
* Total Purchase Amount
* Average Purchase Amount
* Average Review Rating
* Product Categories
* Customer Age Groups
* Purchase Frequency
* Discount Usage
* Subscription Status
* Customer Segments

Interactive filters/slicers are used to allow users to explore the data.

---

## 🔍 Key Business Questions

Some of the questions explored in this project are:

1. What is the average purchase amount?
2. Which product categories generate the most purchases?
3. Which products are most frequently purchased?
4. Do customers who use discounts spend more or less?
5. Which age group spends the most?
6. What is the most common purchase frequency?
7. Are subscribed customers more likely to be repeat buyers?
8. Which products have the highest discount usage?
9. How do customer reviews vary across categories?
10. Which customer segments contribute the most revenue?

---

## 📈 Project Outcome

This project demonstrates the ability to:

* Clean and prepare real-world data
* Perform exploratory data analysis using Python
* Write SQL queries to answer business questions
* Create interactive dashboards using Power BI
* Extract meaningful business insights from customer data
* Present data analysis in a professional and understandable format

---

## 👩‍💻 Author

**Kamaljeet Kaur**

Aspiring Data Analyst
Skills: Python | SQL | Power BI | Pandas | Data Analysis
