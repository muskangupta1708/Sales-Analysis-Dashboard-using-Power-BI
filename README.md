# Sales-Analysis-Dashboard-using-Power-BI

## Project Overview

This project is a Sales Analysis Dashboard built in Power BI to analyze sales performance, profitability, customer behavior, product performance, and geographic trends.

The dashboard helps stakeholders monitor key business metrics and make data-driven decisions through interactive visualizations and filters.

---

## Dataset Information

The dataset contains the following fields:

* Order ID
* Order Date
* Customer Name
* Category
* Sub-Category
* City
* State
* Payment Mode
* Amount
* Quantity
* Profit

---

## Data Preparation

### Step 1: Import Dataset

* Open Power BI Desktop.
* Click **Get Data**.
* Import the sales dataset.

### Step 2: Data Cleaning

* Verify data types.
* Ensure Order Date is formatted as Date.
* Remove null values if present.
* Check for duplicate Order IDs.

## DAX Measures

### Total Sales

```DAX
Total Sales =
SUM('Sales Dataset'[Amount])
```

### Total Profit

```DAX
Total Profit =
SUM('Sales Dataset'[Profit])
```

### Total Quantity

```DAX
Total Quantity =
SUM('Sales Dataset'[Quantity])
```

### Total Orders

```DAX
Total Orders =
DISTINCTCOUNT('Sales Dataset'[Order ID])

---

## Key Insights

* Identified top-selling categories.
* Measured overall profitability.
* Analyzed sales growth trends.
* Evaluated customer purchase patterns.
* Compared regional sales performance.
* Studied preferred payment methods.

---

## Tools Used

* Power BI Desktop
* DAX
* Data Visualization
* Data Analysis

---

## Dashboard Preview

### Executive Summary Dashboard
<img width="1419" height="865" alt="1" src="https://github.com/user-attachments/assets/b7aba8e1-9846-4955-bd1c-7a943e441331" />

### Product Analysis Dashboard
<img width="1425" height="861" alt="2" src="https://github.com/user-attachments/assets/682881e0-4bad-4e5e-92b9-4adb7d21063e" />

### Geographic Analysis Dashboard
<img width="1432" height="857" alt="3" src="https://github.com/user-attachments/assets/b1616c12-62a0-4df1-8311-a91e74e60a58" />

### Customers Analysis Dashboard
<img width="1429" height="858" alt="4" src="https://github.com/user-attachments/assets/407f8d87-3817-47d4-a072-ab1ab043f2d5" />
 
---
