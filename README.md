# Retail-Sales-Analysis
Retail sales dataset analysis (1200 records). Data cleaning, feature engineering, and insights with visualizations using Python (Pandas, Matplotlib, Seaborn).
# 🛍️ Retail Sales Analysis

## 📌 Project Overview
This project analyzes a retail sales dataset (1,200 transactions) to identify trends, patterns, and business insights.  
The analysis includes **data cleaning, feature engineering, summary statistics, and visualizations** using Python.

---

## 📊 Dataset
- **Size:** 1,200 rows × 16 columns  
- **Key Columns:** Date, Store, Product, Category, Price, Quantity, Payment_Method, City, Customer_Age, Customer_Gender  
- **Target:** `Total_Sales` = Price × Quantity  

---

## 🔧 Steps Performed
1. **Data Cleaning**
   - Removed duplicates
   - Filled missing numeric values with mean
   - Filled missing categorical values with mode
   - Dropped unnecessary columns  

2. **Data Type Conversion**
   - Converted `Date` to datetime
   - Converted categorical columns to category type  

3. **Feature Engineering**
   - Created `Total_Sales`, `Month`, `Year`, `DayOfWeek`, `Is_Weekend`, `Sale_Level`

4. **Summary Statistics**
   - Total revenue: **6,079,972**  
   - Average order value: **5,066**  
   - Max transaction: **17,944**  
   - Min transaction: **6.19**  

---

## 📈 Visualizations
- Sales per Month  
- Sales per Category  
- Revenue by Payment Method  
- Average Price per Category  
- Top 3 and Bottom 3 Products  
- Transactions per Month  
- Sales per Store per Year  
- Correlation Heatmap  

All plots are saved in the `plots/` folder.

---

## 🔎 Key Insights
- Highest revenue from **Home & Kitchen**  
- Lowest revenue from **Sports**  
- Most common payment method: **Online Payment**  
- Top products: **Eggs, T-Shirt, Coffee Maker**  
- Bottom products: **Yoga Mat, Milk, Headphones**  
- Store D highest performing; Store C lowest  
- 2023 revenue higher than 2022  
- Peak sales in **March, July, December**

---

## 🛠️ Tools & Technologies
- Python, Pandas, NumPy  
- Matplotlib, Seaborn  
- Excel Spreadsheet for data cleaning  

---

## 📂 Repository Files
- `Cleaned_Retail_Data.xlsx` — clean dataset  
- `Retail_Insights.pdf` — insight report  
- `plots/` — visualizations folder  
- `Retail_Analysis.ipynb` — full notebook

---

## 🔗 Useful Links
- Google Colab Notebook: *(Paste your Colab link here)*
