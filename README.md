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


