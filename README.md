# 📊 Retail Sales Data Cleaning & Transformation Project

## 🚀 Project Overview

This project demonstrates an end-to-end data cleaning and transformation pipeline using Python (Pandas, NumPy, Matplotlib).

The objective was to clean messy retail sales data and transform it into an analysis-ready dataset while generating key business insights and visualizations.

This project simulates a real-world data analyst workflow.

---

## 🎯 Problem Statement

The raw sales dataset contained:

- Missing values
- Duplicate records
- Mixed date formats
- Invalid dates
- Currency symbols in numeric columns
- Negative quantities
- Inconsistent category naming
- Outliers in revenue

The goal was to:

✔ Clean the dataset  
✔ Engineer useful features  
✔ Generate business KPIs  
✔ Create visual insights  
✔ Export clean data for reporting  

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab / VS Code
- Excel (for exported reports)

---


---

## 🔍 Data Cleaning Steps

1. Removed duplicate records
2. Handled missing values using:
   - Mode imputation
   - Zero replacement for discounts
3. Standardized text columns (Category, Region, Customer_Name)
4. Cleaned currency symbols from Price column
5. Converted mixed date formats to datetime
6. Removed invalid dates
7. Removed negative quantities
8. Removed outliers using IQR method
9. Created Revenue column
10. Generated new features:
    - Year
    - Month
    - Month Name
    - Quarter
11. Performed customer segmentation

---

## 📊 Key KPIs Generated

- Total Revenue
- Average Order Value
- Revenue by Category
- Revenue by Region
- Monthly Revenue Trend
- Top 5 Customers
- Customer Segmentation Distribution

---

## 📈 Visualizations Included

- Revenue by Category (Bar Chart)
- Revenue by Region (Bar Chart)
- Monthly Revenue Trend (Line Chart)
- Revenue Distribution (Histogram)
- Top Customers Analysis
- Customer Segmentation Chart


## 📌 Business Insights

- Electronics generated the highest revenue.
- North region contributed the maximum sales.
- High-value customers contributed significantly to total revenue.
- Revenue shows seasonal variation across months.
- Outlier transactions were identified and removed for accuracy.

---

## 📤 Exported Outputs

- Cleaned dataset (CSV)
- Summary Excel report with multiple sheets

---

## 💡 What I Learned

- Handling real-world messy datasets
- Dealing with inconsistent date formats
- Removing outliers using IQR
- Feature engineering for business analysis
- Generating insights using grouped aggregations
- Creating structured data analysis notebooks
- Building portfolio-ready data projects

