# Excel-Cleaning-and-Analysis-Project

This project involves importing, cleaning, and analyzing inventory data related to a department's fleet of vehicles. The data was sourced in CSV (comma-separated values) format and required several preprocessing steps before performing any meaningful analysis.

License: Public Domain

📥 Data Import & Preparation
Source Format: CSV

Converted To: XLSX (Excel Workbook)

🧹 Data Cleaning Tasks
Column Width Adjustment
Resized all columns to ensure full visibility of cell content.

Remove Empty Rows
Used Excel’s Filter feature to identify and delete all empty rows.

Duplicate Removal
Leveraged Conditional Formatting and Remove Duplicates tools to eliminate duplicate records.

Spelling Correction
Manually reviewed the dataset to fix spelling errors in textual fields.

Whitespace Cleanup
Applied Find and Replace to remove all instances of double spaces across the dataset.

Department Name Fixes
Department names were incorrectly split across two columns due to import issues.

Used Flash Fill to merge them into a single column.

Removed unnecessary columns after the correction.

📊 Data Analysis Tasks
Format as Table
Used the Format as Table feature to convert the dataset into a structured Excel Table.

AutoSum Calculations
Applied AutoSum on Column C to compute the following metrics:

SUM

AVERAGE

MIN

MAX

COUNT

Pivot Table 1 – Equipment by Department

Rows: Department

Values: Sum of Equipment Count

Sorted in descending order by equipment total.

Pivot Table 2 – Equipment Class by Department

Rows: Department → Equipment Class

Collapsed all fields except Transportation for focused analysis.

Pivot Table 3 – Department by Equipment Class

Rows: Equipment Class → Department

Collapsed all fields except CUV to isolate that category.

📂 Project Outcome
The final Excel file includes:

Cleaned dataset

Three pivot tables offering different perspectives on equipment distribution

Summary statistics for key numerical fields

