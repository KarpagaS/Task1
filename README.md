# Task1
Cleaning and preparing a raw dataset (with nulls, duplicates, inconsistent formats).
Tools : Excel
Delivered : Cleaned Dataset
Guide: 
1)Identified and handled missing values using  filters in Excel.
    -Blank fields in income column was identified and replaced with the mean value of the income.
2)Removed duplicate rows in Excel’s “Remove Duplicates”.   
   -Checked for duplicates by selecting full data and under Data --> Data tools --> remove duplicates was dane.
    output is "No duplicate values is found".
3)Standardize text values like gender, country names, etc.
   - Checked for inconsistencies in each column and found the 2n cycle as the education in Education column .Found it as typo error and           replaced with secondary.
   - In Marital status column 'Absurd', 'Alone', 'Divorced', 'Married', 'Single', 'Together', 'Widow', 'YOLO' are values inconsistent. So         Absurd was replced with single. Alone was replaced with single. Yolo was replaced with single. Together was replaced with Married.
4)Convert date formats to a consistent type (e.g., dd-mm-yyyy).
   - Date column was selected and right clicked . Then Format cells --> Ddate types.ate 14-March-2014 was selected. So that all date are          converted into date types for analysis.
5)Rename column headers to be clean and uniform (e.g., lowercase, no spaces).
   - In all column headers capital letters are changed into small letters.
6)Check and fix data types (e.g., age should be int, date as datetimes
   - There is no age types to check for data types.
