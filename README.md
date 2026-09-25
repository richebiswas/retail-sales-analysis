# 📊 Retail Sales Analysis

## 📌 Project Overview

This project analyzes retail sales data to identify sales trends, category performance, regional performance, customer and product concentration, and seasonal patterns.

The analysis focuses on converting raw transactional data into actionable business insights and recommendations.

The project follows a business-oriented analytics workflow:

Raw Data → Data Exploration → Analysis → Visualization → Business Insights → Recommendations

---

## 🎯 Business Objective

The objective of this project is to understand the major factors affecting retail sales performance and identify opportunities for improving business decision-making.

The analysis focuses on:

- Overall sales and order performance
- Category and sub-category performance
- Product performance
- Customer sales concentration
- Regional and geographic performance
- Monthly and yearly sales trends
- Sales concentration and business risk
- Seasonal patterns and unusual sales periods

---

## 📂 Dataset

The analysis uses a retail sales dataset containing transactional sales information.

The dataset contains:

- 9,800 records
- 18 fields
- Customer information
- Product information
- Category and sub-category
- Sales information
- Order dates
- Geographic information

The analysis covers sales activity from 2015 to 2018.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Exploratory Data Analysis (EDA)
- Data Aggregation
- Business Analytics
- Data Visualization

---

## 🔍 Analysis Performed

### 1. Data Loading & Understanding

- Dataset structure
- Data types
- Missing-value checks
- Duplicate checks
- Basic statistical exploration

### 2. Sales & Order Analysis

- Total sales
- Number of orders
- Number of customers
- Average order value
- Yearly sales performance

### 3. Category & Product Analysis

- Category performance
- Sub-category performance
- Top-performing products
- Product sales concentration

### 4. Customer Analysis

- Customer sales contribution
- Top customer analysis
- Customer sales concentration
- Cumulative sales contribution

### 5. Regional Analysis

- Regional sales comparison
- State-level performance
- Category performance across regions
- Geographic sales concentration

### 6. Time-Based Analysis

- Yearly sales trends
- Monthly sales patterns
- Seasonal performance
- Monthly performance across years
- Identification of unusual sales periods

---

## 📈 Key Business Findings

- Technology is the strongest-performing sales category.
- The West region generates the highest overall sales.
- The South region contributes approximately 17.2% of total sales.
- The top 10 customers contribute approximately 6.8% of total sales.
- 168 customers account for approximately 50% of cumulative sales.
- The top 10 products contribute approximately 10.8% of total sales.
- November shows the strongest average monthly sales performance.
- February shows the weakest average monthly sales performance.
- November 2018 shows an unusually strong sales performance and should be investigated further.

These findings are based on the analysis performed in the accompanying Jupyter Notebook.

---

## 💡 Business Recommendations

Based on the analysis:

### 1. Strengthen High-Performing Categories

Continue monitoring Technology performance and identify the products and sub-categories driving its contribution.

### 2. Investigate Regional Differences

Examine the causes of performance differences between regions, particularly the lower contribution from the South.

### 3. Monitor Customer Concentration

Use customer segmentation and targeted retention strategies while monitoring dependence on high-value customers.

### 4. Improve Product-Level Decisions

Identify consistently strong products and evaluate opportunities for inventory, pricing, and promotional optimization.

### 5. Use Seasonal Patterns for Planning

Use historical monthly trends to support inventory, marketing, and promotional planning.

### 6. Investigate Sales Anomalies

Analyze the drivers behind the unusually strong November 2018 performance to determine whether the pattern can be replicated.

---

## 📊 Visualizations

The project includes visualizations covering:

- Annual sales trends
- Category performance
- Regional sales performance
- Category × region performance
- Monthly seasonality
- Monthly sales trends across years
- Top 10 products
- Customer sales concentration
- Geographic sales concentration

All visualization outputs are available in the `visualizations/` directory.

---

## 📑 Management Presentation

A management-style presentation summarizes the major findings, business implications, and recommended actions.

[📥 Download the Management Presentation](./Superstore_Retail_Sales_Analysis_Management_Deck.pptx)

---

## 📁 Project Structure

```text
retail-sales-analysis/
│
├── README.md
├── retail_sales_analysis_final.ipynb
├── Superstore_Retail_Sales_Analysis_Management_Deck.pptx
├── train.csv
├── requirements.txt
├── .gitignore
│
└── visualizations/
    ├── annual_sales_trend.png
    ├── category_sales.png
    ├── regional_sales.png
    ├── region_category_sales.png
    ├── monthly_seasonality.png
    ├── monthly_sales_by_year.png
    ├── top10_products.png
    ├── customer_concentration.png
    └── top_states.png
