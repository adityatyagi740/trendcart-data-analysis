# 🛒 TrendCart E-Commerce Data Analysis & Business Insights

An end-to-end Data Analysis project examining e-commerce sales, customer demographics, and transactional behavior to uncover revenue drivers and provide actionable business recommendations.

---

## 📌 Project Overview

TrendCart is a growing e-commerce store selling products across multiple categories. The goal of this analysis is to clean raw transactional data, perform Exploratory Data Analysis (EDA), visualize key metrics using Matplotlib, and translate numerical findings into strategic decisions for business stakeholders.

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python 3.x
* **Data Manipulation & Analysis:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`
* **Environment:** Jupyter Notebook / VS Code

---

## 🧹 Key Data Cleaning Steps (Tasks 1 & 2)

Before analysis, the raw dataset was cleaned and structured:
1. **Duplicate Removal:** Identified and dropped duplicate transaction records.
2. **Missing Value Handling:** Imputed or dropped null values across columns to preserve data integrity.
3. **Feature Engineering:** Created a calculated column `Total_Sales` = `Price` × `Quantity` to evaluate gross revenue per order.

---

## 📊 Exploratory Data Analysis & Key Findings (Task 3)

Using Pandas aggregations and NumPy statistical functions, key insights were extracted:

* 💰 **Revenue Leader:** **Electronics** generated the highest total revenue due to higher unit prices, despite lower total sales volume.
* 💳 **Payment Preference:** **Credit Card** is the most dominant payment method (~46% of total orders), followed by PayPal (~29%). Cash and Debit Card represent a smaller share.
* 👥 **Demographic Insights:** 
  * **Home & Kitchen** attracts the oldest customer base (Average Age: ~44 years).
  * **Beauty** and **Books** cater heavily to younger buyers (18–28 age range).
* 📈 **Statistical Percentiles (Customer Age):**
  * **25th Percentile:** ~25 years
  * **50th Percentile (Median):** ~35 years
  * **75th Percentile:** ~48 years

---

## 🎨 Data Visualizations (Task 4)

The project includes three distinct Matplotlib visualizations to present findings clearly:

1. **Bar Chart (`plt.bar`):** *Total Revenue by Product Category* — Highlights top-performing product verticals.
2. **Pie Chart (`plt.pie`):** *Payment Method Breakdown (%)* — Illustrates transaction share across payment options.
3. **Histogram (`plt.hist`):** *Customer Age Distribution* — Shows the distribution spread and density across customer age groups.

---

## 💡 Strategic Business Recommendations (Task 5)

Based on data findings, three key strategic actions were provided to management:

1. **Product Bundling & Up-Selling:**
   * Pair high-ticket *Electronics* items with complementary lower-cost items (e.g., offer discounts on *Books* or accessories when purchasing laptops/devices) to boost overall order volume.

2. **Targeted Marketing Campaigns:**
   * Focus digital ad spend for *Home & Kitchen* on mature platforms like Facebook and Email marketing.
   * Shift *Beauty* and *Books* marketing budgets toward Instagram/TikTok influencer collaborations targeting Gen-Z & Millennial audiences.

3. **Checkout & Conversion Optimization:**
   * Optimize the payment gateway for Credit Card users (e.g., 1-click checkout, credit card reward incentives) to reduce cart abandonment rates.

---


   📄 Author & Acknowledgments
Author: Aaditya Kumar 

Role: Data Analyst
