End-to-end data analysis of Zepto product data focusing on pricing strategy, discount patterns, and inventory availability using Python.
# Zepto Quick Commerce Inventory & Pricing Analysis

## 1. Project Overview

This project focuses on analyzing product-level data from Zepto, a quick commerce grocery delivery platform. The analysis aims to understand pricing strategies, discount patterns, inventory availability, and stock-out risks using data analysis techniques. The project simulates a real-world business problem commonly faced by quick commerce and retail companies.

This project is designed to demonstrate practical data analyst skills including data cleaning, exploratory data analysis (EDA), feature engineering, and business insight generation.

---

## 2. Business Problem Statement

Quick commerce companies like Zepto operate with tight delivery timelines and high customer expectations. Poor pricing strategies or inventory mismanagement can lead to stock-outs, revenue loss, and customer dissatisfaction.

The key business questions addressed in this project are:

* How are products priced and discounted across categories?
* Which categories have higher discount dependency?
* Which products or categories face inventory risks?
* How can pricing and inventory planning be optimized using data insights?

---

## 3. Dataset Description

The dataset contains product-level information with more than 3,700 records and the following attributes:

* **Category**: Product category (e.g., Fruits, Snacks, Dairy)
* **name**: Product name
* **mrp**: Maximum Retail Price
* **discountPercent**: Discount percentage offered
* **availableQuantity**: Available inventory quantity
* **discountedSellingPrice**: Final selling price after discount
* **weightInGms**: Product weight in grams
* **outOfStock**: Stock availability status (True/False)
* **quantity**: Pack size or unit quantity

---

## 4. Tools and Technologies Used

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **Jupyter Notebook**
* **GitHub** for version control and project hosting

---

## 5. Data Cleaning and Preparation

The following data preprocessing steps were performed:

* Checked for missing values and data consistency
* Removed duplicate records
* Converted data types for numerical and boolean fields
* Standardized columns for accurate analysis

These steps ensured reliable and accurate analysis results.

---

## 6. Feature Engineering

To enhance analysis and derive business insights, additional features were created:

* **Discount Amount**: Difference between MRP and discounted selling price
* **Discount Ratio**: Proportion of discount relative to MRP

These features helped evaluate the impact of discounts on pricing and inventory decisions.

---

## 7. Exploratory Data Analysis (EDA)

The EDA phase focused on answering key business questions:

### 7.1 Category-wise Product Distribution

Analyzed how products are distributed across categories to understand inventory focus areas.

### 7.2 Discount Analysis

Studied average discount percentages across categories to identify discount-driven product segments.

### 7.3 Pricing Analysis

Compared MRP with discounted selling price to understand Zepto’s pricing strategy.

### 7.4 Inventory Availability Analysis

Identified low-stock products that pose a risk of stock-outs.

### 7.5 Out-of-Stock Analysis

Analyzed stock-out rates across categories to identify inventory planning gaps.

### 7.6 Weight vs Pricing Analysis

Explored the relationship between product weight and selling price to assess pricing efficiency.

---

## 8. Key Insights

* Essential categories dominate the product listings
* Competitive categories receive higher discounts
* Some products are heavily discounted despite low inventory
* Stock-out risks are higher in high-demand categories
* Product pricing is not always proportional to weight

---

## 9. Business Recommendations

Based on the analysis, the following recommendations are proposed:

* Improve demand forecasting for low-stock, high-demand products
* Avoid over-discounting items with limited inventory
* Maintain buffer stock for fast-moving categories
* Optimize pricing strategies to protect margins

---

## 10. Conclusion

This project demonstrates how data analysis can be used to derive actionable business insights in a quick commerce environment. By analyzing pricing, discounts, and inventory availability, the project highlights opportunities to improve operational efficiency, reduce stock-outs, and enhance customer satisfaction.

The project showcases practical data analyst skills and can be extended further using SQL or Power BI dashboards.

---

## 11. Author

**Virendra Pangannavar**

MCA Graduate | Aspiring Data Analyst

---

## 13. How to Run the Project

1. Clone the repository
2. Install required Python libraries
3. Open the Jupyter Notebook
4. Run the cells sequentially to reproduce the analysis

---

*This project is created for learning, portfolio, and interview demonstration purposes.*
