# Task 1: Data Immersion, Profiling & Cleaning

## 📌 Objective
To rapidly acquaint with the dataset and master the critical first step of analysis: acquiring, cleaning, and preparing data for analysis.

---

## 🛠️ Steps

### 1. Data Access & Familiarization
- Loaded raw dataset (`salesdata2.xlsx`).
- Previewed first 20 rows.
- Documented variables in a **Raw Data Dictionary**.

### 2. Data Quality Assessment
- Identified missing values in CustomerName, DOB, Email, Quantity.
- Found duplicates (same customers repeated).
- Spotted inconsistent formatting (Gender values).
- Detected outliers (negative Price, unrealistic Age).

### 3. Data Cleaning & Transformation
- Removed duplicates.
- Standardized Gender values.
- Converted Quantity and Price to numeric.
- Replaced negative prices with `NaN`.
- Parsed DOB and Date into proper datetime.
- Filled missing DOBs with median/default.
- Engineered new feature: **Age** from DOB.
- Filled missing CustomerName/Email with `"Unknown"`.
- Reset ID column for sequential numbering.

### 4. Deliverables
- **Raw Dataset** (`raw_dataset.xlsx`)
- **Raw Data Dictionary** (`raw_data_dictionary.xlsx`)
- **Cleaned Dataset** (`cleaned_dataset.xlsx`)
- **Cleaned Data Dictionary** (`cleaned_data_dictionary.xlsx`)

---

## 🎯 Conclusion
This task successfully demonstrated the complete **data cleaning workflow**:
- Immersion into raw data,
- Profiling to detect issues,
- Wrangling to fix inconsistencies,
- Exporting analysis‑ready datasets.

By completing Task 1, the dataset is now **structured, reliable, and ready for deeper analysis and dashboarding** in subsequent tasks.
