# PV-Signal-Detection-PRR
Pharmacovigilance signal detection project using Proportional Reporting Ratio (PRR) method on simulated ADR dataset to identify potential safety signals.
#  Pharmacovigilance Signal Detection Project  
### Proportional Reporting Ratio (PRR) Analysis

![Pharmacovigilance](https://img.shields.io/badge/Domain-Pharmacovigilance-blue)
![Signal Detection](https://img.shields.io/badge/Analysis-Signal_Detection-orange)
![Method](https://img.shields.io/badge/Method-PRR-green)
![Dataset](https://img.shields.io/badge/Dataset-Simulated_150_ICSRs-lightgrey)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

##  Project Overview

This project demonstrates the practical application of **disproportionality analysis** in pharmacovigilance using the **Proportional Reporting Ratio (PRR)** method.

A simulated dataset of 150 Individual Case Safety Reports (ICSRs) was created to identify potential drug–event safety signals.

---

##  Objective

To evaluate whether specific adverse events are reported disproportionately more frequently for certain drugs using PRR methodology.

---

##  Dataset Description

Total Reports: **150 simulated ADR cases**

### Drugs Included:
- Remdesivir
- Dexamethasone
- Tocilizumab
- Favipiravir

### Adverse Events:
- Liver Injury
- Hyperglycemia
- Infection
- Renal Failure
- Headache

Each report contains:
- Case_ID
- Drug
- Adverse_Event
- Seriousness
- Outcome

---

##  Methodology

For each drug-event pair, a 2×2 contingency table was constructed:

|              | Event | Other Events |
|--------------|--------|--------------|
| Drug         | A      | B            |
| Other Drugs  | C      | D            |

### PRR Formula:

PRR = (A / (A + B)) / (C / (C + D))

### Signal Criteria:
- PRR ≥ 2
- A ≥ 3 cases

---

##  Results Summary

| Drug | Event | PRR | Signal |
|------|-------|------|--------|
| Remdesivir | Liver Injury | 1.81 | No |
| Tocilizumab | Infection | 2.29 | Yes |
| Dexamethasone | Hyperglycemia | 1.38 | No |

###  Key Finding:
A potential safety signal was detected for:

**Tocilizumab – Infection (PRR = 2.29)**

---

##  Files Included

- `ADR_Dataset.xlsx` – Simulated pharmacovigilance dataset
- `PRR_Calculation.xlsx` – PRR analysis sheet
- `Signal_Detection_Report.pdf` – Structured assessment report
- `README.md` – Project documentation

---

##  Skills Demonstrated

- Pharmacovigilance fundamentals
- Signal detection methodology
- Disproportionality analysis (PRR)
- 2×2 contingency table construction
- Statistical interpretation
- Regulatory-style documentation
- Excel data analysis

---

##  Project Significance

This project simulates early-stage signal detection workflows used in regulatory pharmacovigilance systems such as:

- EMA spontaneous reporting systems
- FDA FAERS database
- WHO VigiBase

It demonstrates readiness for junior-level safety analyst roles.

---

##  Author

Nihal Nadaf 
Pharmacovigilance Enthusiast  
Signal Detection Project
