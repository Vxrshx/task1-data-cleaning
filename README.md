Task 1: Data Cleaning and Preprocessing

Dataset
Netflix Movies and TV Shows (from Kaggle)

Tools Used
- Python (Pandas)
- Jupyter Notebook

Steps Performed
- Checked and handled missing values using `.isnull()`, `.fillna()`, `.dropna()`
- Removed duplicate rows using `.drop_duplicates()`
- Standardized text fields and column names
- Converted `date_added` to datetime format using `pd.to_datetime()`
- Renamed all column headers to lowercase and snake_case
- Exported cleaned data as `netflix_cleaned.csv`

Files Included
- `task1_cleaning.ipynb` – Python notebook with code
- `netflix_cleaned.csv` – Final cleaned dataset

Outcome
Cleaned dataset ready for analysis or visualization. Successfully demonstrated data preprocessing skills.
