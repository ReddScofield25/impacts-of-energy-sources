# ⚡ Impacts of Energy Production – Environmental Analysis

## 📦 Project Summary
Hands-on practice from the **Google Data Analytics Certificate**.  
This project analyzes a **Kaggle dataset on environmental impacts of energy sources** to apply **SMART questioning**, develop a **Scope of Work (SOW)**, and conduct spreadsheet-based analysis.  
The objective is not to provide policy arguments, but to demonstrate **structured analytical thinking**, **data preparation**, and **comparative environmental assessment**.

## 🧭 Scenario
I act as a data analyst evaluating different **energy sources** (Coal, Nuclear, Solar, Wind, etc.) using key environmental impact metrics. The goal was to clean the dataset, define SMART questions, prepare a SOW, and determine which sources carry the highest environmental burden.

## 🎯 SMART Questions (Guiding the Analysis)
- Which energy source has the **highest CO₂ emissions** per unit?
- Which source uses the **most water** per unit of electricity?
- Which source has the **lowest land use**?
- Which source has the **highest combined toxicity** (carcinogenic + non-carcinogenic)?

These questions structured the Scope of Work and guided all analytical tasks.

## 🧰 Tools Used
- **Google Sheets** – Data cleaning, computation, visual charts  
- **Kaggle** – Dataset source  
- **GitHub** – Project documentation

## 🧹 Data Preparation & Cleaning

| Step | Action |
|------|--------|
| Import | Dataset retrieved from Kaggle |
| Null Columns | Dropped fully empty fields (*Death Rate, Agricultural Land, Urban Land*) |
| Header Renaming | Standardized names for clarity (*CO₂ Emissions, Water Use, Land Use, Carcinogenic, Non-Carcinogenic*) |
| Derived Field | Created **Total Toxicity = Carcinogenic + Non-Carcinogenic** |

## 📁 Project Files
- `impacts_of_energy_sources.csv` — Original dataset  
- `impacts_of_energy_sources.xlsx` — Cleaned dataset & analysis  
- `impacts_of_energy_sources_sow.docx` — Scope of Work document  
- `entity_vs_co2_emissions.png` — CO₂ emissions chart  
- `land_use_vs_water_use_scatter.png` — Land vs Water scatter chart

## 🔗 Live Resources *(Optional)*
Access planning documents and analysis:

- **Scope of Work (Google Doc):** *[View here](https://docs.google.com/document/d/17k1wqkY1ycU8Cuw4YogN6HO22xsQ-P7d4E6x8BxnSMs/edit?usp=sharing)*  
- **Spreadsheet Analysis (Google Sheet):** *[View here](https://docs.google.com/spreadsheets/d/1BaLRfDi9-mmUhXtirqwd910umRzDzUgMaz-F7C3oKMY/edit?usp=sharing)*  

> These links provide real-time access to the working files used in the analysis.

---

## 📊 Visual Analysis (Charts Created)

| Chart | Purpose |
|--------|---------|
| **`entity_vs_co2_emissions.png`** | CO₂ emissions comparison across energy sources |
| **`land_use_vs_water_use_scatter.png`** | Land preservation vs water demand distribution |

---

## 🔍 Observations & Findings

### CO₂ Emissions (Combo Chart)
- **Coal** recorded the highest emissions (**970**), making it the most carbon-intensive source.
- **Nuclear** had the lowest (**5.6**), representing minimal greenhouse gas output.

### Land vs Water Use (Scatter Plot)
- Most energy sources clustered where **Water Use < 50** and **Land Use 0–35**, indicating limited joint impact.
- Minimal clustering at **high water use (>50)** implies **higher water intensity does not correlate with higher land impact**, suggesting conservation trade-offs.

---

## 🧪 SMART Question Answers

| Question | Result |
|----------|--------|
| Highest CO₂ Emissions | **Coal** |
| Most Water Use | **Coal with CCS** |
| Lowest Land Use | **Nuclear** |
| Highest Toxicity | **Coal with CCS** |

(Toxicity calculated as **Carcinogenic + Non-Carcinogenic**)

---

## 🧠 Learning Outcomes
✔ Practiced SMART question design to define analytical focus  
✔ Demonstrated SOW as a planning and documentation tool  
✔ Conducted environmental comparison using spreadsheet techniques  
✔ Recognized data limitations and environmental trade-offs

---

## 📣 About This Project
A self-directed exercise under the **Google Data Analytics Certificate**, focused on:
- Dataset interpretation  
- Structured analytical methodology  
- Practical environmental insight through data comparison  

