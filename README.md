# DA_Task1_ELEVATE_LABS
# Task 1: Data Cleaning and Preprocessing
<b>Objective:</b> Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats).<br><br>
<b>Tools:</b> Excel / Python (Pandas)<br><br>
<b>Dataset from Kaggle</b>: https://www.kaggle.com/datasets/shivamb/netflix-shows<br><br>
<b>Deliverables (Summary of Changes):</b>
- Loaded and explored the Netflix dataset.
- Dropped unnecessary columns: description and date_added.
- Handled missing data by removing rows with null values.
- Renamed all columns for consistency and clarity (e.g., show_id to Show ID).
- Removed duplicate records to ensure data integrity.
- Converted the Release Year column from int64 to datetime64[ns] format using pd.to_datetime().
- Displayed dataset shape, column types, and verified changes with .info() and .head().
<br><br>

<b>Hints / Mini Guide:</b>
- Identify and handle missing values using .isnull() in Python or filters in Excel.
- Remove duplicate rows using .drop_duplicates() or Excel’s “Remove Duplicates”.
- Standardize text values like gender, country names, etc.
- Convert date formats to a consistent type (e.g., dd-mm-yyyy).
- Rename column headers to be clean and uniform (e.g., lowercase, no spaces).
- Check and fix data types (e.g., age should be int, date as datetime).
