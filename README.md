# 🚗 Road Accident Data Cleaning Project

## 📌 Project Overview
Data cleaning is the most critical step in any analysis. This project demonstrates my ability to take a "messy" real-world dataset (Road Accidents) and transform it into a high-quality, reliable format for further insights.

## 🛠️ Data Cleaning Techniques Used
In this project, I handled several common data issues using **Python & Pandas**:
* **Temporal Conversion:** Converted `Time_of_Day` into a standardized Python time format.
* **Categorical Imputation:** Filled missing values in `Weather_Conditions` and `Type_of_Junction` using the **Mode**.
* **Numerical Imputation:** * Replaced zero-values in `Vehicle_Speed` with the **Median** speed.
    * Fixed faulty sensor readings in `Visibility` and `Road Friction` using statistical medians.
* **Integrity Checks:** Verified and removed duplicate records to ensure data uniqueness.

## 🧰 Tools
* **Python:** 3.11
* **Environment:** Google Colab
* **Library:** Pandas

## 📂 Files in this Repo
* `road_accident_data.xlsx`: The raw, uncleaned dataset.
* `Data_Cleaning_Process.ipynb`: The full cleaning script with logic.
* `cleaned_data.csv`: The final, ready-to-use dataset.

---
*This project is part of my portfolio as I prepare for a **Data Analysis Internship**.*# Road-Accident-Data-
