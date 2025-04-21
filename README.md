# Task-1-Data-Cleaning-and-Preprocessing
Objective: Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats)

- Identified and filtered missing values using filters in Excel in every column.
- Highlighted the rows that have one or more blank cells
- Removed Duplicates, if any, using "Data > Remove duplicates"
- Standardised the "CountryName" Column in a new column (H2) using the "IF, OR, and SWITCH" functions with the formula "=IF(OR(F2="USA", F2="usa", F2="U.S.A", F2="united states", F2="United States"), "United States", IF(OR(F2="India", F2="INDIA", F2="india", F2="IND"), "India", F2))"
- To standardize the phone numbers, we first removed everything that was not a number (like +, -, (, ), x, etc.) using functions like LEN, INDIRECT, ISNUMBER, TEXTJOIN, RIGHT, etc.
- Next, I standardised the Date column using the IFERROR function. "=IFERROR(TEXT(DATEVALUE(E3), "yyyy-mm-dd"), "")"


In the completion of this task, I have used the MS Office tool - Excel. I took help from the internet to gain knowlegde of various excel functions.
