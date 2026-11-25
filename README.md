# 🛍️ Vrinda Store Data Analysis (2022) — Excel Dashboard

An end-to-end **Sales Data Analysis & Interactive Dashboard** built in **Microsoft Excel** for **Vrinda Store**. This project analyzes annual sales performance, customer demographics, order trends, and channel contributions to help drive data-backed business decisions for 2023.

---

## 📌 Project Objective
Vrinda Store wants to generate an annual sales report for 2022 to understand customer purchasing behavior and identify key growth opportunities so they can boost sales in 2023.

---

## 📊 Key Questions Answered
- Compare **Sales vs. Orders** using a single dual-axis combo chart.
- Which month recorded the **highest sales and orders**?
- Who purchased more in 2022 — **Men or Women**?
- What are the different **order statuses** in 2022?
- Which are the **Top 5 States** contributing the most to sales?
- What is the relationship between **Age Group and Gender** based on order volume?
- Which **sales channel** contributed the maximum orders?
- Which **product category** recorded the highest sales?

---

## 🛠️ Tools & Techniques Used
- **Microsoft Excel**
- **Data Cleaning & Preprocessing:** Standardizing gender labels (`M`/`F` to `Men`/`Women`), handling missing/duplicate values, and formatting dates.
- **Feature Engineering:** Created helper columns for **Month** (`=TEXT(Date, "mmm")`) and **Age Group** (`Adult`, `Senior`, `Teenager`) using nested `IF` formulas.
- **Pivot Tables & Pivot Charts:** Built dynamic multi-dimensional summaries across time, geography, demographics, and channels.
- **Interactive Slicers:** Added slicers for **Month**, **Channel**, and **Category** for real-time dashboard filtering.

---

## 💡 Key Business Insights
- **Gender Dominance:** Women accounted for **~65%** of total purchases compared to Men (**~35%**).
- **Top States:** **Maharashtra, Karnataka, and Uttar Pradesh** emerged as the top 3 revenue-generating states.
- **Target Age Group:** The **Adult (30–49 years)** demographic contributed roughly **50%** of overall orders.
- **Leading Sales Channels:** **Amazon, Flipkart, and Myntra** drove nearly **80%** of total orders.
- **Peak Sales Month:** **March** saw the highest sales and order volume, followed closely by February.

---

## 🚀 Strategic Recommendations for 2023
- Target **Women customers aged 30–49** residing in **Maharashtra, Karnataka, and Uttar Pradesh** with personalized offers, festive campaigns, and loyalty discounts.
- Prioritize inventory and ad spend on top-performing marketplaces (**Amazon, Flipkart, and Myntra**).

---

## 📁 Repository Structure
```text
├── Vrinda Store Data Analysis (1).xlsx   # Complete workbook (Raw Data, Cleaned Data, Pivot Tables & Dashboard)
└── README.md                            # Project documentation
