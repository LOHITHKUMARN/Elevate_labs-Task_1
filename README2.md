
# Netflix Titles Datase – Data Cleaning 
  
**Tool Used:** Microsoft Excel


## Steps Performed
1. **Removed Duplicates** – Eliminated repeated records to ensure data uniqueness.  
2. **Handled Missing Values** – Filled missing values appropriately:  
   - `director`, `country`, `date_added`, `duration` → *Unknown*  
   - `cast` → *Not Available*  
   - `rating` → *Not Rated*  
3. **Standardized Column Names** – Converted all headers to lowercase and replaced spaces with underscores.  
4. **Fixed Date Formats** – Converted `date_added` column into a consistent `DD-MM-YYYY` format.  
5. **Trimmed Extra Spaces** – Removed leading/trailing spaces from all text fields for cleaner representation.

## Final Output
- Cleaned dataset: **netflix_titles_cleaned.xlsx**  
- Ready for data visualization, trend analysis, or further preprocessing.

