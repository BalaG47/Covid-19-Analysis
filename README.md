# Covid-19-Analysis

---

## 📂 Project Overview
This project analyzes COVID-19 patient-level data to uncover patterns, risk factors, and outcomes. The analysis was performed in **Python (Jupyter Notebook)**, followed by the creation of an **interactive Tableau dashboard** for visualization.

Key objectives:
- Explore patient demographics and profiles.
- Investigate comorbidities and their impact on outcomes.
- Assess hospitalization, ICU admissions, intubation, and mortality.
- Provide interactive visual analytics for deeper insights.

---

## 📊 Tableau Dashboard Topics
The dashboard is divided into four main sections:

1. **Classification and Final Outcome** – Case classification (confirmed/suspected) and survival outcomes.  
2. **Patient Profile** – Age, sex, and patient type (inpatient vs outpatient).  
3. **Comorbidities and Death** – Relationship between diseases (diabetes, hypertension, obesity, etc.) and mortality.  
4. **Clinical, Pneumonia & Pregnancy** – Analysis of pneumonia cases, ICU admission, intubation, and pregnancy-related outcomes.  

---

## 📂 Repository Contents
- **Covid19Analysis.ipynb** → Jupyter Notebook with data cleaning, preprocessing, and exploratory data analysis.  
- **README.md** → Project documentation (this file).  
- **Tableau Dashboard** → Published online for interactive exploration.  

---

## 🔑 Data Dictionary
| Column Name          | Description                                                            | Data Type | Possible Values / Codes |
|----------------------|------------------------------------------------------------------------|-----------|--------------------------|
| **USMER**            | Indicates if the medical unit is part of the USMER monitoring network  | int64     | 1 = Yes, 2 = No |
| **MEDICAL_UNIT**     | Type/category of the medical unit/hospital                             | int64     | Integer ID (requires mapping) |
| **SEX**              | Patient’s biological sex                                               | int64     | 1 = Male, 2 = Female |
| **PATIENT_TYPE**     | Type of care received                                                  | int64     | 1 = Outpatient, 2 = Inpatient |
| **DATE_DIED**        | Date of death (if applicable)                                          | object    | dd/mm/yyyy, "9999-99-99", or 97 = Alive |
| **INTUBED**          | Patient required intubation                                            | int64     | 1 = Yes, 2 = No, 97 = Unknown |
| **PNEUMONIA**        | Patient diagnosed with pneumonia                                       | int64     | 1 = Yes, 2 = No, 97 = Unknown |
| **AGE**              | Patient’s age in years                                                 | int64     | 0–120 |
| **PREGNANT**         | Patient was pregnant (for females of reproductive age)                 | int64     | 1 = Yes, 2 = No, 97 = N/A / Unknown |
| **DIABETES**         | Patient diagnosed with diabetes                                        | int64     | 1 = Yes, 2 = No, 97 = Unknown |
| **COPD**             | Patient diagnosed with COPD                                            | int64     | 1 = Yes, 2 = No, 97 = Unknown |
| **ASTHMA**           | Patient diagnosed with asthma                                          | int64     | 1 = Yes, 2 = No, 97 = Unknown |
| **INMSUPR**          | Patient is immunosuppressed                                            | int64     | 1 = Yes, 2 = No, 97 = Unknown |
| **HIPERTENSION**     | Patient diagnosed with hypertension                                    | int64     | 1 = Yes, 2 = No, 97 = Unknown |
| **OTHER_DISEASE**    | Patient has other significant diseases not listed separately           | int64     | 1 = Yes, 2 = No, 97 = Unknown |
| **CARDIOVASCULAR**   | Patient diagnosed with cardiovascular disease (excluding hypertension) | int64     | 1 = Yes, 2 = No, 97 = Unknown |
| **OBESITY**          | Patient is clinically obese                                            | int64     | 1 = Yes, 2 = No, 97 = Unknown |
| **RENAL_CHRONIC**    | Patient diagnosed with chronic kidney disease                          | int64     | 1 = Yes, 2 = No, 97 = Unknown |
| **TOBACCO**          | Patient uses tobacco                                                   | int64     | 1 = Yes, 2 = No, 97 = Unknown |
| **CLASIFFICATION_FINAL** | Final classification of COVID-19 case                             | int64     | 1 = Confirmed by lab, 2 = Epidemiologic link, 3 = Expert judgment, 4–7 = Suspected |
| **ICU**              | Patient admitted to Intensive Care Unit                                | int64     | 1 = Yes, 2 = No, 97 = Unknown |

---

## ⚙️ Tools & Libraries Used
- **Python** 🐍 → Pandas, NumPy, Matplotlib, Seaborn  
- **Jupyter Notebook** → Data preprocessing & EDA  
- **Tableau** → Interactive data visualization  

---
