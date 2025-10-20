# Data Cleaning (Amazon Dataset)

**Tool Used:** Microsoft Excel

### Cleaning Steps:
1. Removed duplicate rows.
2. Deleted 2 rows with missing `rating_count`.
3. Removed ₹, %, and commas from numeric columns.
4. Converted `actual_price`, `discounted_price`, and `rating` to numeric type.
5. Standardized column names to lowercase with underscores.
6. Verified numeric and text data types.

### Final Output:
Cleaned dataset with consistent formatting and no missing or duplicate entries.

Netflix Titles Datase – Data Cleaning
Tool Used: Microsoft Excel

Steps Performed
Removed Duplicates – Eliminated repeated records to ensure data uniqueness.
Handled Missing Values – Filled missing values appropriately:
director, country, date_added, duration → Unknown
cast → Not Available
rating → Not Rated
Standardized Column Names – Converted all headers to lowercase and replaced spaces with underscores.
Fixed Date Formats – Converted date_added column into a consistent DD-MM-YYYY format.
Trimmed Extra Spaces – Removed leading/trailing spaces from all text fields for cleaner representation.
Final Output
Cleaned dataset: netflix_titles_cleaned.xlsx
Ready for data visualization, trend analysis, or further preprocessing.
