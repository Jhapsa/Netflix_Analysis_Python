# 🎬 Netflix Movies and TV Shows Dataset — Data Cleaning & Preprocessing

## 📌 Objective

This project focuses on cleaning and preparing the Netflix titles dataset for analysis. The raw data contains missing values, inconsistent formatting, and mixed data types. By the end of this project, the dataset is structured, uniform, and analysis-ready.

---

## 🗃️ Dataset Info

- **Source**: [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/shivamb/netflix-shows)
- **Rows**: 8807
- **Columns**: 14
- **Fields**: show ID, type, title, director, cast, country, date added, release year, rating, duration, listed genres, description

---

## 🛠️ Tools Used

- Python 3.x
- Pandas
- Jupyter Notebook

---

## 🧼 Cleaning Steps Performed

1. **Identified and Handled Missing Values**
   - Filled missing values in `director` and `cast` with `"Unknown"`
   - Filled missing `country` with `"Unspecified"`
   - Converted `date_added` to `datetime` and filled NaT with a default date
   - Filled missing values in `rating` with `"Unrated"`
   - Filled missing values in `duration` with `"Unknown"`

2. **Removed Duplicates**
   - Verified and dropped duplicate rows (if any)

3. **Standardized Text Fields**
   - Cleaned whitespace and casing in `type`, `rating`, `country`, etc.

4. **Converted Date Formats**
   - Converted `date_added` to `datetime64[ns]`
   - Extracted `year_added` and `month_added` from `date_added`

5. **Renamed Columns**
   - Renamed all columns to lowercase and used snake_case formatting

6. **Validated Data Types**
   - Ensured `release_year` is `int`
   - Ensured `date_added` is `datetime`
   - Ensured all fields are in consistent and appropriate data types

---

## ✅ Final Deliverables

- `netflix_cleaned.csv`: Fully cleaned and preprocessed dataset
- `netflix_cleaning.ipynb`: Jupyter Notebook showing all steps
- `README.md`: Project overview and documentation

---

## 📊 Ready For

- Exploratory Data Analysis (EDA)
- Dashboard creation (Power BI, Tableau, etc.)
- Machine learning preprocessing
- Portfolio showcase

---

## ✍️ Author

**Biswarup Das**  
MCA Student | Data Analyst Aspirant  
📍 West Bengal, India

---

## 📄 License

This project is open-source and free to use under the MIT License.
