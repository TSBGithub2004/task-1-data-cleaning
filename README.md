# 🧹 Task 1 – Data Cleaning & Preprocessing

## 📌 Internship Task Overview
As part of the Data Analyst Internship, the objective of this task was to clean and preprocess a raw dataset by addressing common data quality issues like missing values, duplicates, inconsistent formats, and improper data types.

## 🧾 Dataset Used
- **Customer Personality Analysis** dataset (from Kaggle)
- File: `customer_personality_cleaned.xlsx`

## 🔧 Tools Used
- Python (Pandas)
- Jupyter Notebook
- Excel (for initial data exploration)

---

## ✅ Cleaning & Preprocessing Steps

1. **Handled Missing Values:**
   - Identified missing values using `.isnull().sum()`
   - Filled missing values for categorical fields using `'Unknown'` or most frequent value.
   - Dropped rows with critical missing values (e.g., income or age).

2. **Removed Duplicates:**
   - Used `.drop_duplicates()` to eliminate duplicate records.

3. **Standardized Text Data:**
   - Trimmed whitespaces and converted to lowercase.
   - Normalized categorical fields like `Gender`, `Education`, `Marital_Status`.

4. **Date Format Conversion:**
   - Converted all dates (e.g., `Dt_Customer`) to a standard format `dd-mm-yyyy`.

5. **Renamed Columns:**
   - Cleaned and renamed column headers: removed spaces, used lowercase, applied snake_case naming.

6. **Fixed Data Types:**
   - Ensured numeric columns were correctly cast (`int`, `float`).
   - Converted date fields to `datetime` objects.

---

## 📤 Deliverables

- ✅ Cleaned dataset: `customer_personality_cleaned.xlsx`
- ✅ Summary of changes (see below)
- ✅ This README file

---

## ✨ Summary of Changes

| Issue                         | Action Taken                                 |
|------------------------------|----------------------------------------------|
| Missing values               | Filled or removed as per context             |
| Duplicate rows               | Removed using Pandas                         |
| Text inconsistencies         | Standardized (e.g., gender, marital status)  |
| Date format issues           | Converted to `dd-mm-yyyy` format             |
| Column naming inconsistencies| Renamed using `snake_case`                   |
| Incorrect data types         | Casted to appropriate types                  |

---

## 🧠 Key Learnings
- Practical understanding of real-world data cleaning.
- Importance of consistent formatting and data integrity.
- Gained confidence in handling raw datasets using Python (Pandas).

---

## 📎 Submission
GitHub Repo: [Insert your repository link here]

Submission Form: [https://forms.gle/o2uMAByM719GzebC7](https://forms.gle/o2uMAByM719GzebC7)

