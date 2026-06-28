\# Data Cleaning Log



\## 1. Problem Overview

The dataset contained order-level retail sales data exported from multiple systems. The data had inconsistencies in text formatting, mixed date formats, duplicate records, missing values, invalid discount values, and business rule violations. The objective was to clean, validate, and prepare the dataset for analysis.



\---



\## 2. Issues Identified



\### 2.1 Text Issues

\- Leading and trailing spaces in multiple columns (e.g., region, segment)

\- Inconsistent casing (e.g., NORTH, north, North)

\- Duplicate category naming (e.g., OFFICE SUPPLIES vs Office Supplies)

\- Irregular spacing (e.g., "Small  Business")



\### 2.2 Date Issues

\- Multiple date formats (DD-MM-YYYY, MM/DD/YYYY, YYYY-MM-DD, text-based dates)

\- Some dates stored as text instead of proper date format

\- Ship dates earlier than order dates

\- Missing or invalid date values





