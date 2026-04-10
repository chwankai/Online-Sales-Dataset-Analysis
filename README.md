# Data Wrangling Project - Online Sales Dataset Analysis

## 📌 Project Overview

This project focuses on **data wrangling, cleaning, and visualization** using an online sales dataset. The main objective is to explore sales performance, detect data issues, remove outliers, and generate meaningful insights through statistical analysis and interactive visualizations.

We use Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, SciPy, and Plotly to perform end-to-end data analysis.

### Members

1. 242UT2449Z – KHO WEI CONG
2. 242UT244B2 – TEE KIAN HAO
3. 242UT2449P – SEE CHWAN KAI
4. 242UT24490 – TEO JING AN

---


## 📂 Dataset

**File used:** `Online Sales Data.csv`

The dataset contains transactional-level data including:

* Transaction ID
* Product Category
* Units Sold
* Unit Price
* Total Revenue
* Date
* Region
* Payment Method

---

## ⚙️ Tools & Libraries Used

* pandas
* numpy
* matplotlib
* seaborn
* scipy (zscore)
* plotly (express & graph objects)

---

## 🧹 Data Wrangling Process

### 1. Data Inspection

* Checked dataset shape, structure, and data types
* Identified categorical and numerical variables
* Detected missing values and duplicates

### 2. Outlier Detection & Removal

* Used **Z-score method** grouped by Product Category
* Removed outliers from:

  * Unit Price
  * Total Revenue

### 3. Data Cleaning

* Recalculated Total Revenue using:
  `Units Sold × Unit Price`
* Corrected inconsistent revenue values

### 4. Feature Engineering

* Converted Date column into:

  * Year
  * Month
  * Day

---

## 📊 Exploratory Data Analysis (EDA)

### Descriptive Statistics

Computed:

* Mean
* Median
* Min / Max
* Range
* Variance
* Standard Deviation

### Correlation Analysis

* Examined relationships between:

  * Units Sold
  * Unit Price
  * Total Revenue

---

## 📈 Data Visualization

### 1. Distribution Analysis

* Units Sold distribution
* Unit Price distribution
* Total Revenue distribution

### 2. Revenue Analysis

* Revenue by Product Category
* Revenue trend by Month and Year
* Revenue by Region

### 3. Payment Method Analysis

* Payment method distribution by:

  * Product Category
  * Region
* Interactive toggle between views

---

## 📌 Key Insights

* Certain product categories contribute significantly higher revenue than others.
* Revenue shows noticeable variation across months, indicating seasonal trends.
* Region plays a strong role in overall sales performance.
* Payment method preferences differ by both category and region.

---

## 📊 Key Outputs

The project generates:

* Cleaned dataset after outlier removal
* Statistical summary tables
* Correlation heatmap
* Interactive Plotly visualizations

---

## 🚀 How to Run the Project

1. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scipy plotly
   ```

2. Place `Online Sales Data.csv` in the same directory as the script.

3. Run the Jupyter Notebook.

---

## 👨‍💻 Notes

* All data cleaning steps are reproducible.
* Outlier removal is done per product category for better accuracy.
* Interactive charts are built using Plotly for better insight exploration.

---
