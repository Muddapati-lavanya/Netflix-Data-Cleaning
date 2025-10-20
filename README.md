# Netflix-Data-Cleaning
Data Cleaning and Pre processing of Netflix dataset using Python(Pandas)

# Netflix Titles Data Cleaning – Task 1 (Elevate Data Analyst Internship)

## 🎯 Project Overview
This project involves cleaning and preprocessing the **Netflix Titles** dataset (`netflix_titles.csv`) as part of the **Elevate Data Analyst Internship – Task 1**.  
The dataset contains details about movies and TV shows available on Netflix, such as title, director, cast, country, release year, rating, duration, and more.

---

## 🧹 Steps Performed
1. **Loaded the dataset** using Pandas.
2. **Checked data structure** with `.info()`, `.describe()`, and `.isnull().sum()`.
3. **Handled missing values:**
   - Filled missing `director`, `cast`, and `country` fields with `'Unknown'`.
4. **Removed duplicates** to ensure data consistency.
5. **Standardized text formatting** (lowercase, trimmed spaces).
6. **Converted date formats** in the `date_added` column using `pd.to_datetime()`.
7. **Renamed columns** for consistency (lowercase with underscores).
8. **Verified data types** and saved the cleaned dataset.

---

## 📁 Files Included
- `netflix_titles.zip` – Contains the full cleaned dataset (`netflix_titles_cleaned.csv`)
- *(Optional)* `netflix_titles_sample.csv` – A small preview file with 100 rows for easy viewing
- `README.md` – Project summary and documentation

---

## 🧾 Summary of Cleaning Results
- ✅ Removed duplicate records  
- ✅ Replaced missing values with appropriate placeholders  
- ✅ Standardized and formatted text columns  
- ✅ Ensured correct data types  
- ✅ Cleaned dataset ready for further analysis and visualization  

---

## 🧰 Tools & Libraries Used
- Python 🐍  
- Pandas  
- NumPy  
- Jupyter Notebook / VS Code  

