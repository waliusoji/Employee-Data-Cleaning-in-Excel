# Employee Data Cleaning in Excel

## Project Overview

This project focuses on cleaning a messy HR dataset containing **1,256 employee records**. The goal was to transform raw, inconsistent data into a clean, structured, and analysis-ready dataset using **Microsoft Excel**.

---

## Dataset Details

| Property | Details |
|----------|---------|
| Rows | 1,265 |
| Columns | 14 |
| Tool Used | Microsoft Excel |
| Project Type | Data Cleaning / Data Wrangling |

---

## Data Quality Issues Identified

- Inconsistent text casing
- Leading and trailing spaces
- Duplicate records
- Missing values
- Mixed currency formats
- Non-numeric values in numeric columns
- Multiple date formats
- Invalid age values
- Out-of-range performance scores
- Inconsistent boolean values
- Department name inconsistencies
- Invalid email formats
- Placeholder phone numbers
- Empty rows
- Mixed foreign currencies


## Cleaning Steps

1. Removed completely blank rows
2. Removed duplicate records using Employee ID
3. Standardized text using `TRIM()` and `PROPER()`
4. Cleaned and unified department names
5. Unified date formats → `YYYH-MM-DD`
6. Cleaned and standardized the salary column
7. Replaced missing numeric values using `MEDIAN()`
8. Corrected invalid age values
9. Standardized performance scores using `MODE()`
10. Unified boolean values → `TRUE` / `FALSE`
11. Fixed email formatting issues
12. Cleaned the phone number column
13. Handled all remaining missing values

---

## Results

| Metric | Outcome |
|--------|---------|
| Final Dataset Size | ~1,200 rows |
| Duplicate Rows | Removed |
| Missing Values | Handled |
| Date Formats | Standardized (DD-MM-YYYY) |
| Salary Column | Fully numeric |
| Data Consistency | Achieved across all columns |

---

## Tools & Techniques

**Excel Functions:**
`TRIM()` · `PROPER()` · `MEDIAN()` · `MODE()`

**Excel Features:**
- Find & Replace
- Remove Duplicates
- Filters
- Text to Columns
- Conditional Formatting

---

## Key Learnings

- Data cleaning requires both **technical skills** and **decision-making**
- **Preserving data** is often better than deleting it
- **Standardization** is critical for accurate analysis
- Small inconsistencies can lead to **major analytical errors**


## Project Outcome

The final dataset is clean, consistent, and fully ready for analysis or dashboard creation.

---
