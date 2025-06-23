# Sales-data-cleaning-task
# 📊 Sales Data Cleaning Task – Internship Day 1

This repository contains the cleaned version of the raw sales dataset provided as part of Day 1 of my internship. The entire cleaning process was done using **Microsoft Excel (Mobile App)**.

---

## 🧾 Dataset Used

- **Dataset Name**: Sample Sales Data  
- **Source**: [Kaggle – Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)  
- **Original File**: `sales_data_sample.csv`  
- **Cleaned File**: `sales_data_cleaned.xlsx`

---

## 🛠 Tools Used

| Tool                      | Purpose                              |
|---------------------------|--------------------------------------|
| Microsoft Excel (Mobile)  | Data cleaning and formatting         |
| GitHub                    | Uploading the cleaned file & report  |

---

## 🧽 Steps Followed for Data Cleaning

1. **Removed Duplicate Rows**
   - Manually checked and deleted any repeated entries in the dataset.

2. **Handled Missing Values**
   - `ADDRESSLINE2`: Replaced with `'N/A'`
   - `STATE`: Replaced with `'Unknown'`
   - `POSTALCODE`: Replaced with `'00000'`
   - `TERRITORY`: Replaced with `'Unknown'`

3. **Standardized Column Headers**
   - Renamed columns to lowercase and replaced spaces with underscores (e.g., `Order Date` → `order_date`).

4. **Formatted Date Fields**
   - Standardized the `order_date` column format to `DD-MM-YYYY` using Excel's date formatting tools.

5. **Checked and Verified Data Types**
   - Ensured numbers (like `quantityordered`, `sales`) were in numeric format.
   - Ensured dates and text values were stored correctly.

---

## ✅ Summary

- Cleaned raw sales data using Excel (Mobile).
- Removed duplicates and handled missing data.
- Formatted dates and column headers.
- Ensured data types were appropriate.
- Saved and uploaded the final version as `sales_data_cleaned.xlsx`.

---