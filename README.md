# 🚌 Kerala Private Bus Accident Analysis

A beginner data analysis project in **Python**. It looks at **private bus accidents in Kerala, India** between **November 2024 and November 2026**.

👉 **[Open the notebook](Kerala_Bus_Accident_Analysis_Beginner.ipynb)** to see all the code, tables and charts.

---

## 📌 What is this project about?

In Kerala, private buses carry a large share of road passengers, and they often make the news for crashes. This project uses real, publicly available data to answer a simple question:

> **How serious is the private bus accident problem in Kerala, and what patterns can we see?**

## ❓ Questions answered

1. Did private bus accidents **go up or down** from 2024 to 2025?
2. How do private buses **compare with other buses** (KSRTC, school, college and mini buses)?
3. Are road accidents in Kerala **increasing overall**?
4. Which **districts** have the most bus accidents?
5. What do **news-reported accidents** tell us about crash types, injuries and causes?

---

## 📊 Key findings

| # | Finding |
|---|---|
| 1 | Private buses are involved in about **65% of all bus accidents** in Kerala. |
| 2 | From 2024 to 2025, private bus **accidents rose 4.1%** (2,443 → 2,543). |
| 3 | **Deaths fell 7.8%** (258 → 238), but **serious injuries rose 13.1%** (1,482 → 1,676). |
| 4 | **KSRTC** accidents are **more deadly** per accident than private bus accidents (15.5 vs 9.4 deaths per 100 accidents in 2025). |
| 5 | Private buses are linked to **~5% of all road accidents** but **6.4% of road deaths** in Kerala. |
| 6 | Road accidents across Kerala are **increasing**: about 4,070 per month in 2024, 4,157 in 2025 and 4,484 in 2026. |
| 7 | **Kozhikode, Ernakulam and Thrissur** have the most bus accidents (2024). |
| 8 | In the news reports, **Thrissur** has the most accidents, and **speeding** is mentioned in 12 of 27 cases. |

### 💡 Suggestions based on the findings
- Stricter **speed checks** on private buses, especially on busy routes such as Kozhikode–Thrissur.
- Make sure bus **doors stay closed** while the bus is moving (some passengers fell out).
- Regular checks of **tyres, brakes and speed governors**.

---

## 🗂️ The data

The data comes from an Excel workbook built from **official government sources** and **news reports**:

| Data | What it tells us | Source |
|---|---|---|
| Accidents by bus type (2024, 2025) | Accidents, deaths and injuries for each type of bus | Kerala Police |
| Accidents by district (2024) | Bus accidents in each district | Kerala State Planning Board (Economic Review 2025) |
| Kerala road accident totals (2024 – Aug 2026) | All road accidents, deaths and injuries in the state | Kerala Police |
| News-reported accidents (28 cases) | Date, place, crash type, cause, deaths and injuries | Onmanorama, The New Indian Express, Kerala Kaumudi, Times of India |

> ℹ️ The Excel data file is **not included** in this repository. The notebook is saved **with all its results**, so you can read every table and chart directly on GitHub without running anything.

---

## 🛠️ Tools used

| Tool | Used for |
|---|---|
| **Python** | Programming language |
| **pandas** | Reading and analysing the data tables |
| **matplotlib** | Drawing charts |
| **Jupyter Notebook** | Writing code and explanations together |

---

## 🪜 How the analysis was done

The notebook follows **6 simple steps**:

1. **Import libraries**: load pandas and matplotlib.
2. **Load the data**: read the sheets from the Excel file.
3. **Understand the data**: look at rows and columns, data types and missing values.
4. **Clean the data**: fix dates, remove a duplicate accident, and combine City and Rural police areas into districts.
5. **Analyse and visualise**: calculate changes and percentages, then draw bar and line charts.
6. **Conclusion**: summarise the findings and suggestions.

Every code cell has a short explanation in plain English, and each section ends with an **Observation** explaining the result.

---

## ▶️ How to run it yourself

1. Install Python, then install the libraries:
   ```bash
   pip install pandas matplotlib openpyxl notebook
   ```
2. Download `Kerala_Bus_Accident_Analysis_Beginner.ipynb`.
3. Put the data file `kerala_private_bus_accident_powerbi_data_pack.xlsx` in the **same folder**.
4. Start Jupyter and open the notebook:
   ```bash
   jupyter notebook
   ```
5. Click **Run → Run All Cells**.

---

## ⚠️ Limitations

- The official data gives **yearly totals only**, not details of every single accident.
- The news data is a **sample of 27 accidents** (after removing one duplicate), not a complete list.
- Some causes in news reports are **not officially confirmed** by the police or the Motor Vehicles Department.
- "Other buses" in the district data includes private buses **plus some other bus types**.

---

## 🙋 About

Made by **[Anandhuvimalan](https://github.com/Anandhuvimalan)** as a Python data analysis learning project.

⭐ If you found this project useful, consider giving it a star!
