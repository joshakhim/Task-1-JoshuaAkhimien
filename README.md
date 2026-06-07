# Task-1-JoshuaAkhimien

# DecodeLabs Data Cleaning & Exploratory Data Analysis

## Project Overview

This project focuses on cleaning, validating, and analyzing transactional business data using Python and Pandas.

The objective was to transform raw transactional records into a reliable and analysis-ready dataset through structured data cleaning, validation checks, and exploratory data analysis (EDA).

---

## Tools Used

* Python
* Pandas
* NumPy
* Jupyter Notebook

---

## Dataset Summary

The dataset contains approximately 1,200 transaction records and includes:

* Order Information
* Customer IDs
* Product Details
* Quantity Purchased
* Unit Price
* Total Price
* Payment Methods
* Coupon Usage
* Referral Sources
* Transaction Dates

---

## Data Cleaning Process

### Missing Values

* Identified missing coupon codes.
* Replaced null values with "No Coupon".

### Duplicate Validation

* Checked duplicate rows.
* Checked duplicate Order IDs.
* No duplicates found.

### Date Validation

* Verified datetime consistency.
* Standardized date formatting.

### Financial Validation

* Validated that:

Total Price = Quantity × Unit Price

* Corrected floating-point precision issues through rounding.

### Text Standardization

* Standardized categorical text values.
* Improved consistency for reporting and analysis.

---

## Key Findings

### Revenue Validation

* Dataset passed all financial integrity checks.

### Data Quality

* No duplicate transactions found.
* No invalid negative sales values detected.

### Business Readiness

* Dataset successfully transformed into an analysis-ready format suitable for reporting and business intelligence.

---

## Skills Demonstrated

* Data Cleaning
* Data Validation
* Exploratory Data Analysis
* Python Programming
* Pandas
* Business Analytics
* Data Documentation

---

## Project Outcome

The project successfully transformed raw transactional data into a structured, validated, and reliable dataset suitable for downstream analytics and reporting workflows.
