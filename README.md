# 🍔 Food Delivery Cost and Profitability Analysis

This project analyzes a dataset of food delivery orders to understand the cost structure and identify strategies for improving profitability in the food delivery business.

---

## 📁 Dataset

**Source:** `food_orders_new_delhi.csv` csv file added in repo

**Key Columns:**
- **Order Details:** Order ID, Customer ID, Restaurant ID
- **Timestamps:** Order Date and Time, Delivery Date and Time
- **Financials:** Order Value, Delivery Fee, Payment Method, Discounts and Offers, Commission Fee, Payment Processing Fee, Refunds/Chargebacks

---

## 🔧 Analysis Performed

### 1. Data Loading and Exploration
- Loaded the dataset using pandas
- Inspected structure, null values, and data types

### 2. Data Cleaning and Preparation
- Converted datetime columns
- Extracted discount amounts from text data
- Cleaned and prepared cost-related fields

### 3. Cost and Revenue Calculations
- **Total Cost** = Delivery Fee + Payment Processing Fee + Discount Amount
- **Revenue** = Commission Fee
- **Profit** = Revenue - Total Cost

### 4. Overall Metrics
- Total Orders
- Total Revenue
- Total Costs
- Total Profit

### 5. Profitability Analysis
- Profit per order distribution (histogram)
- Cost breakdown (pie chart)
- Revenue vs. Costs vs. Profit (bar chart)

### 6. Strategy for Profit Improvement
- Analyzed profitable orders to determine optimal commission and discount rates
- Simulated profit under:
  - **Commission = 28%**
  - **Discount = 6%**
- Compared simulated vs. actual profitability

---

## 📊 Key Findings

- Business is **currently unprofitable**
- **Discounts and Offers** are the biggest cost contributors
- Profitable orders tend to have:
  - **~28% Commission**
  - **~6% Discounts**
- Simulation using optimized rates shows improved profit per order

---

## 📈 Recommendations

- Reduce aggressive discounting; aim for 6% average
- Slightly increase commission rates for sustainable revenue
- Run A/B tests to validate changes before full deployment
- Segment analysis by restaurant, region, or order value for deeper insights

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

