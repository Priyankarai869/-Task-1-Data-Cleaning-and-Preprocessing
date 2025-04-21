# -Task-1-Data-Cleaning-and-Preprocessing<br><br>
## Dataset<br>
**Netflix Movies and TV Shows**<br>
Source: [Kaggle Netflix Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)<br><br>

---<br><br>

##  Tools Used<br>
- Microsoft Excel<br><br>

---<br><br>

##  Data Cleaning Steps Performed<br><br>

1. **Handled Missing Values**<br>
   - Replaced missing `country`, `director`, and `cast` values with `"N/A"`.<br><br>

2. **Removed Duplicates**<br>
   - Used Excel’s Remove Duplicates feature to eliminate duplicate rows, but found 0 duplicates in the dataset.<br><br>

3. **Standardized Text Values**<br>
   - Cleaned up inconsistencies in `country`, `type`, and `rating` columns.<br><br>

4. **Formatted Dates**<br>
   - Converted `date_added` to a proper date format `dd-mm-yyyy` using formula logic in new `formatted_date` column.<br><br>

5. **Renamed Columns**<br>
   - Standardized column headers using lowercase and underscores for clarity (`formatted_date`).<br><br>

6. **Fixed Data Types**<br>
   - Ensured `release_year` and other numeric columns are correctly formatted as numbers.<br>
   - Converted `date_added` into a real date type for filtering and analysis.<br><br>

---<br><br>

##  Additional Features<br><br>

-  Created a `Pivot Table` (in a separate sheet) to analyze:<br>
  - Count of TV Shows vs Movies.<br>
  - Most common content ratings.<br><br>

---<br><br>

## Formatting Enhancements<br><br>

- Applied professional table style (light color).<br>
- AutoFit column widths for readability.<br>
- Created a clean, visually organized layout.<br><br>

---<br><br>

##  Files Included<br><br>

- netflix_tittles.csv folder contains:<br>
  - `netflix_cleaned_final.xlsx` – cleaned and formatted dataset.<br>
  - Pivot table located in **Pivot_Analysis** sheet in `netflix_cleaned_final.xlsx`.<br>
  - `netflix_titles_original.csv` - downloaded dataset.<br><br>

---<br><br>

## Submission Info<br><br>

This task is part of a **Data Analyst Internship** assignment involving:<br>
- Real-world data cleaning<br>
- Hands-on Excel formatting<br>
- Summary writing and GitHub usage<br>

