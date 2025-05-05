# Homework 4 – dplyr Practice and SBA Loan Data Analysis

**Author:** Taku Takahashi
**Course:** DATA 312 – Data Visualization with R
**Semester:** Spring 2025
**Homework #:** 4

---

## 📝 Overview

This homework focuses on building fluency with **`dplyr` verbs** for data wrangling in R, based on materials covered in Lecture 3 and Lecture 4.
Using real-world data from the U.S. Small Business Administration (SBA), I applied `dplyr` tools to filter, summarize, and reshape data related to small business loans.

The project was completed in a **Quarto (`.qmd`) notebook** and rendered to **HTML**.

---

## 📊 Topics & Skills Demonstrated

This assignment showcases the following R/data manipulation skills:

- Using `distinct()` to view unique values in a dataset
- Filtering data with multiple conditions using `filter()`
- Selecting specific columns using `select()`
- Grouping and summarizing data with `group_by()` and `summarise()`
- Calculating totals and averages with `sum()` and `mean()`
- Sorting results using `arrange()`
- Creating renamed versions of a dataset using `rename()`

---

## 📁 Data Used

**Dataset:**
`sba_investments` – a filtered subset of SBA 7(a) loan data from [data.sba.gov](https://data.sba.gov/dataset/7-a-504-foia), focused on 6 U.S. states: DC, DE, MD, NC, VA, and WV.

**Source CSV URL:**
[https://raw.githubusercontent.com/jmtfeliciano/teachingdata/refs/heads/main/data7a2024localdata.csv](https://raw.githubusercontent.com/jmtfeliciano/teachingdata/refs/heads/main/data7a2024localdata.csv)

**Documentation:**
A data dictionary for the SBA dataset is available [here](https://data.sba.gov/dataset/7-a-504-foia/resource/6898b986-a895-47b4-bb7e-c6b286b23a7b)

---

## 🧪 Key Tasks Completed

| Task # | Description |
|--------|-------------|
| 1 | Use `distinct()` to explore unique loan statuses |
| 2 | Filter data for a specific borrower in DC using NAICS code |
| 3 | Select a subset of relevant columns and store as `sba_subset` |
| 4 | Calculate total jobs supported by borrower state |
| 5 | Calculate average interest rates by borrower state |
| 6 | Compute overall median loan approval amount |
| 7 | Compute total loans approved for Nail Salons |
| 8 | Compute total loans for Nail Salons in VA and MD |
| 9 | Identify top 5 industries by total SBA loan approval |
| 10 | Rename variables and create a cleaned-up version of the data (`sba_subset_v2`) |

---

## 📄 Files Included

- `Homework4.qmd` – The Quarto notebook with R code and analysis
- `Homework4.html` – Rendered HTML report
- `README.md` – This file

---

## 🔧 Tools Used

- **R** (version 4.x or later)
- **tidyverse** (especially `dplyr` and `readr`)
- **Quarto** for reproducible report generation
