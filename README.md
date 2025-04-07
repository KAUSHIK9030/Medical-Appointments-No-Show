# 🏥 Medical Appointment No-Show – Data Cleaning & Visualization

##  Objective
The goal of this project is to clean and preprocess a real-world dataset of medical appointments in Brazil, focusing on identifying patterns in patient no-shows.

---

##  Files Included

| File Name | Description |

| `Medical_Appointment_No_Show_Cleaning.ipynb` | Jupyter Notebook with all data cleaning steps and visualizations |
| `Cleaned_Medical_Appointment_No_Shows.csv` | Final cleaned version of the dataset, ready for analysis |
| `README.md` | Project overview and explanation |

---

##  Steps Performed

1. **Loaded the dataset** with proper encoding (`ISO-8859-1`) to handle special characters
2. **Renamed all columns**:
   - Removed dashes and underscores
   - Converted camelCase to readable format (e.g., `AppointmentDay` → `Appointment Day`)
3. **Handled missing values** and removed duplicates
4. **Converted date columns** to `datetime` format (`Scheduled Day`, `Appointment Day`)
5. **Standardized text columns**:
   - Fixed inconsistent casing
   - Converted gender abbreviations (`M`/`F`) to `Male`/`Female`
   - Renamed `No-Show` column to `No Show`
6. **Fixed scientific notation** for `Patient Id` column by converting it to string
7. **Saved the cleaned dataset** as a CSV file

---

##  Visualization

A bar chart was created to show **No-show vs Show grouped by Gender** using `seaborn`:
>  This helps identify if one gender is more likely to miss appointments.

---

##  Result

- A fully cleaned and structured dataset
- Clearly labeled columns and readable formats
- At least one clear visualization to support EDA
- Ready for further analysis or modeling

---

## Potential Extensions

- Analyze no-shows by age group or weekday
- Build a basic machine learning model to predict no-shows
- Add more visual insights

---

# Internship Project: Data Cleaning & Preprocessing  
