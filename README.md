Amazon Product Dataset – Data Cleaning Summary

Tool Used: Microsoft Excel

Cleaning Procedures:

Duplicate Removal: Identified and removed redundant rows to ensure data integrity.

Handling Missing Values: Two records with missing rating_count were removed, as they lacked sufficient information for analysis.

Data Normalization:

Stripped currency symbols (₹), commas, and percentage signs (%) from numeric fields for consistency.

Converted actual_price, discounted_price, and rating columns to proper numeric data types to enable calculations and comparisons.

Column Standardization: Renamed all column headers using lowercase letters and underscores for consistency (camelCase or space-separated names were avoided).

Data Type Verification: Ensured each column had the appropriate data type—numeric for prices and ratings, textual for product names and categories.

Outcome:
A fully cleaned and structured dataset with no missing or duplicate entries, ready for further analysis such as price distribution, discount evaluation, or rating trends.

Netflix Titles Dataset – Data Cleaning Overview

Tool Used: Microsoft Excel

Steps Taken:

Duplicate Elimination: Removed repeated entries to maintain a clean, unique dataset.

Imputation of Missing Data:

Filled missing values in key columns with standardized placeholders:

director, country, date_added, duration → "Unknown"

cast → "Not Available"

rating → "Not Rated"

Header Formatting: Standardized column names by converting all to lowercase and replacing spaces with underscores for compatibility in analysis tools.

Date Standardization: Re-formatted the date_added column uniformly to the DD-MM-YYYY format for consistency and ease of filtering.

Text Cleanup: Removed any leading or trailing whitespace from text-based fields to eliminate formatting inconsistencies.

Final Output:
A refined and analysis-ready dataset (netflix_titles_cleaned.xlsx), suitable for visualizations, content analysis, or integration into recommendation systems.
