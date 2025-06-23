# ELEVATELABS_Task01
# Netflix Movies and TV Shows — Data Cleaning & Preprocessing Task

# Objective
To clean and preprocess a raw dataset of Netflix Movies and TV Shows by handling:
- Missing values
- Duplicates
- Inconsistent formats
- Text standardization
- Data type corrections

---

# Dataset
Source: https://www.kaggle.com/datasets/shivamb/netflix-shows 
Columns in Dataset:
- show_id
- type
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in
- description

---

# Tools Used
- Python 
- Pandas 
- VS Code with Jupyter Notebook Extension (.ipynb)
- GitHub 

---

# Data Cleaning Steps Performed

1. Missing Values Handled:
- Filled missing values in `director`, `cast`, `country`, and `rating` with `'Not Available'`.
- Converted `date_added` to datetime format; handled missing dates with `NaT`.

2. Removed Duplicates:
- Used `drop_duplicates()` to clean the dataset.

3. Standardized Text:
- Converted string columns to lowercase and removed extra spaces.
- Cleaned and renamed column headers to lowercase with underscores.

4. Date Format Standardization:
- Used `pd.to_datetime()` to ensure all dates are in `YYYY-MM-DD` format.

5. Corrected Data Types:
- Verified data types using `.info()`, especially for date and year columns.

---

# Output
- Cleaned dataset ready for analysis or modeling.
- Exported as `netflix_titles_cleaned.csv`.

---

# Learning Outcomes

- Understood key data preprocessing tasks using Pandas.
- Practiced handling missing values, duplicates, and standardizing formats.
- Built confidence to clean raw datasets independently.

---

# Author
Ankur Parmar
MScIT 1st Year | CHARUSAT 

---

