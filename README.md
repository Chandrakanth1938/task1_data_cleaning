# Task 1: Data Cleaning and Preprocessing

## Dataset
- Netflix Movies and TV Shows (Kaggle)

## Steps Performed
1. **Handled missing values**
   - Filled missing `director`, `cast`, `country`, `rating`, `duration` with `"Unknown"`.
   - Filled missing `date_added` with the mode (most common date).
2. **Removed duplicate records**.
3. **Standardized categorical values**
   - Converted `type`, `country`, and `rating` to lowercase.
4. **Renamed columns** for consistency (lowercase, underscores).
5. **Converted data types**
   - `date_added` → datetime format
   - `release_year` → integer
6. **Exported cleaned dataset**
   - `netflix_titles_cleaned.csv`

## Deliverables
- **Raw Dataset**: `dataset/netflix_titles.csv`
- **Cleaned Dataset**: `dataset/netflix_titles_cleaned.csv`
- **Notebook**: `notebooks/data_cleaning_netflix.ipynb`
