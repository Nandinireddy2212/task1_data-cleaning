# task1 - data cleaning

This task performs data cleaning and preprocessing on the Netflix Titles dataset using Python (Pandas) in Google Colab

## Tools used 
- Python (pandas) 
- Google colab

## Files
- task1_data_cleaning.ipynb  –  Colab notebook with code
- netflix_titles.csv  –  Original dataset
- cleaned_netflix_titles.csv  –  Cleaned dataset

## Cleaning Steps performed
### 1. Handled Missing Values
- Dropped rows with missing `title`.
- Replaced other missing fields with `'unknown'`.

### 2. Removed Duplicate Records
- Checked for and removed exact duplicate rows.

### 3. Standardized Text Columns
- Converted all text columns to lowercase.
- Stripped leading and trailing whitespace from text fields.

### 4. Normalized Date Format
- Converted `date_added` column to a consistent `dd-mm-yyyy` string format.

### 5. Renamed Columns
- Standardized column headers by converting to lowercase and replacing spaces with underscores.

### 6. Fixed Data Types
- Converted `release_year` column to integer type (`Int64`).

### 7. Final Output
- Cleaned dataset saved as: `cleaned_netflix_titles.csv`
