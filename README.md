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
<img width="1286" height="450" alt="Image" src="https://github.com/user-attachments/assets/7829bb3d-b80a-4554-9131-ab878bd7821e" />
* Unit Price distribution
<img width="1286" height="450" alt="Image" src="https://github.com/user-attachments/assets/3ddc4e50-1f37-4108-8b17-f1ef1185a0f5" />
* Total Revenue distribution
<img width="1286" height="450" alt="Image" src="https://github.com/user-attachments/assets/01d2c015-ed65-4b11-a9d2-3b9550eb2bd6" />

### 2. Revenue Analysis

* Revenue by Product Category
<img width="1286" height="450" alt="Image" src="https://github.com/user-attachments/assets/72b2b5d0-6590-46dd-bb85-25a670ab864c" />
* Revenue trend by Month and Year
<img width="1286" height="450" alt="Image" src="https://github.com/user-attachments/assets/494fc5c7-af3a-41b5-a54f-248029eb4e80" />
* Revenue by Region
<img width="1286" height="450" alt="Image" src="https://github.com/user-attachments/assets/383e4256-3870-4c7f-8145-bfca2e4711a5" />

### 3. Payment Method Analysis

* Payment method distribution by (Interactive toggle between views):
  * Product Category
<img width="1286" height="450" alt="Image" src="https://github.com/user-attachments/assets/6ac63624-04ae-4e70-b7ae-300640ba0d9f" />
  * Region
<img width="1286" height="450" alt="Image" src="https://github.com/user-attachments/assets/d1347af8-2c08-492a-b577-3fab944cf12c" />

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
