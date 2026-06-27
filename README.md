# Task1_Gayani-_Jayasundara
# Task 1 – Data Cleaning & Handling Missing Values

## Overview

This project demonstrates the data cleaning process performed on a retail sales dataset using Python and Pandas. The goal was to prepare the raw dataset for further analysis by handling missing values, checking for duplicate records, validating data formats, and exporting a cleaned dataset.

## Objective

- Identify missing values
- Handle missing data appropriately
- Check for duplicate records
- Validate data types
- Save the cleaned dataset for future analysis

## Dataset

The dataset contains retail order information including:

- Order ID
- Date
- Customer ID
- Product
- Quantity
- Unit Price
- Shipping Address
- Payment Method
- Order Status
- Tracking Number
- Items in Cart
- Coupon Code
- Referral Source
- Total Price

## Tools Used

- Python
- Pandas
- Microsoft Excel
- Jupyter Notebook / VS Code

## Project Structure

Task-1-Data-Cleaning/
│
├── Dataset for Data Analytics.xlsx
├── Cleaned Dataset.xlsx
├── task1_data_cleaning.ipynb
├── Task 1_Report.docx
└── README.md

## Steps Performed
### 1. Load the Dataset
Imported the Excel dataset into a Pandas DataFrame.

### 2. Check Missing Values
Checked for missing values in all columns.

### 3. Handle Missing Values
Replaced missing CouponCode values with **"No Coupon"**.

### 4. Check Duplicate Records
Verified duplicate rows and duplicate Order IDs.

### 5. Validate Date Format
Converted the Date column into datetime format.

### 6. Save the Cleaned Dataset
Exported the cleaned dataset.

## Output

The project generates:
- Cleaned Dataset.xlsx

## How to Run

1. Clone this repository.
```bash
git clone https://github.com/yourusername/Task-1-Data-Cleaning.git
```

2. Install the required package.
```bash
pip install pandas openpyxl
```

3. Run the Python script.
```bash
python task1_data_cleaning.py
```
or open the Jupyter Notebook.

