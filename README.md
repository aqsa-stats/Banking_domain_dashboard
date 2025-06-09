# 🏦 Bank Customer Data Analysis & Dashboard

This project combines Python-based Exploratory Data Analysis (EDA) with an interactive Power BI dashboard to uncover insights from a bank's customer dataset. The goal is to assist in data-driven marketing and customer profiling.

---

## 📌 Project Overview

* Perform detailed EDA using Python (Jupyter Notebook)
* Visualize relationships and trends in customer attributes
* Build a Power BI dashboard to explore insights interactively
* Derive conclusions that can support marketing and customer segmentation strategies

---

## 🧠 Objectives

* Explore demographics, financial features, and campaign responses
* Identify customer behavior patterns and marketing effectiveness
* Present findings using interactive dashboards and visuals

---

## 🛠️ Tools & Technologies

| Tool/Language       | Purpose                        |
| ------------------- | ------------------------------ |
| Python              | Data manipulation & EDA        |
| Pandas, NumPy       | Data wrangling                 |
| Matplotlib, Seaborn | Data visualization             |
| Power BI (.pbix)    | Interactive dashboards         |
| Jupyter Notebook    | Code and analysis presentation |

---

## 📁 Repository Structure

```
BankCustomerAnalysis/
│
├── BankEDA.ipynb              # Python-based Exploratory Data Analysis
├── Banking Dashboard.pbix     # Power BI Dashboard file
├── README.md                  # Project documentation
└── requirements.txt           # Python dependencies (optional)
```
---

## 📈 Analysis Highlights

### 🏦 Financial Insights

* Customers with **higher balances** are more likely to subscribe to the term deposit.
* **Housing and personal loans** are held by a considerable proportion of customers.

### 📣 Campaign Response

* The success of marketing campaigns is **not strongly influenced** by education or marital status.
* **Duration of last contact** plays a critical role in campaign success.
* Customers contacted during **May** and **August** were most frequent, but had lower success rates.

### 🔗 Variable Relationships

* Positive correlation found between **balance and duration**.
* Age, campaign count, and previous outcomes show weak correlation with subscription (`y`).

### 📊 Visual Patterns

* Used histograms, pie charts, count plots, and bar graphs for visual storytelling.
* Heatmaps revealed weak multicollinearity in most features.
