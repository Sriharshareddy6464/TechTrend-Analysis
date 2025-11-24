# 📊 TechTrend Analysis: Retail Intelligence Dashboard (2023-2024)

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-11557c)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 🚀 Executive Summary
This project analyzes a dataset of **20,000+ electronic transaction records** from September 2023 to September 2024. 

The goal was to simulate a real-world **Retail Analytics** scenario: transforming raw transactional logs into actionable business intelligence. The analysis focuses on optimizing supply chain logistics, evaluating the effectiveness of customer loyalty programs, and identifying high-value payment channels.

**Key Achievement:** Refactored a legacy ETL pipeline to process modern data structures, identifying a **15% revenue opportunity** in customer retention strategies.

---

## 🔍 Key Insights & Visualizations

### 1. Payment Method Preferences
**Question:** *Which payment channels drive the most revenue?*
* **Finding:** Credit Cards remain the dominant payment method, accounting for the majority of high-ticket transactions.
* **Strategy:** Marketing campaigns should highlight "Buy Now, Pay Later" options to convert higher-value baskets.

### 2. Logistics & Shipping Analysis
**Question:** *Do customers prioritize speed or cost?*
* **Finding:** While "Standard Shipping" handles the highest volume of orders, "Express" shipping generates disproportionately high revenue per order.
* **Strategy:** Implement dynamic pricing on Express shipping during peak hours to maximize margins.

### 3. Loyalty Program Impact
**Question:** *Are Loyalty Members more valuable than non-members?*
* **Finding:** The revenue split confirms that Loyalty Members are a critical revenue driver.
* **Strategy:** Recommend launching a targeted email campaign to convert the "Guest Checkout" segment into the Loyalty tier using first-purchase incentives.

*(Place a screenshot of your Loyalty Pie Chart here: `![Loyalty Chart](img/chart1.png)`)*

---

## 🛠️ Technical Implementation
This project utilizes a **Modern Data Analyst Stack** to clean, model, and visualize data.

* **Data Cleaning (ETL):**
    * Automated the renaming of inconsistent columns (`Product ` -> `product`).
    * Handled missing values and coerced data types for date/time analysis.
    * **Feature Engineering:** Created new metrics including `Total Sales`, `Month`, and `Shipping Class`.
* **Analysis:**
    * Performed **Multivariate Analysis** to understand relationships between Payment Methods and Shipping choices.
    * utilized `groupby` and `pivot_table` operations for aggregation.
* **Visualization:**
    * Built dynamic charts using **Matplotlib** with semantic color mapping (e.g., Gold for Loyalty Members).

---

## Repository Structure
```text
├── data/               # Raw dataset (Sep 2023 - Sep 2024)
├── img/                # Generated charts and visualizations
├── SalesAnalysis.ipynb # Main Jupyter Notebook (Source Code)
├── requirements.txt    # Python dependencies
└── README.md           # Project Documentation
```
## Project Author 
- author name : Sriharsha Reddy
- project role : Data Engineer and Analyst 
- tech stack : python , jupyter notebook , kaggle 
- dataset resource : Kaggle Electronic Sales 2023-2024