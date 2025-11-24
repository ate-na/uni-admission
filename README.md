# University Admission Chance Prediction

**Predicting the probability of getting admitted to graduate programs (mainly in the US)**  
A machine learning project using the famous "Graduate Admissions" dataset.

![Python](https://img.shields.io/badge/python-3.7%2B-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-orange)
![Pandas](https://img.shields.io/badge/pandas-1.0%2B-green)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Project Overview

This project predicts a student's **Chance of Admit** to graduate programs based on the following features:

| Feature             | Description                                 |
| ------------------- | ------------------------------------------- |
| GRE Score           | GRE exam score (out of 340)                 |
| TOEFL Score         | TOEFL exam score (out of 120)               |
| University Rating   | Target university tier (1–5)                |
| SOP                 | Strength of Statement of Purpose (1–5)      |
| LOR                 | Strength of Letters of Recommendation (1–5) |
| CGPA                | Undergraduate GPA (out of 10)               |
| Research            | Has research experience? (0 or 1)           |
| **Chance of Admit** | **Target** – Probability of admission (0–1) |

Dataset: 400 real student records.

## Best Model

**Linear Regression**

- R² Score: **~0.82**
- MAE: **0.042**
- Simple, interpretable, and most accurate on this dataset.

## Repository Contents

| File                                | Description                                                             |
| ----------------------------------- | ----------------------------------------------------------------------- |
| `Admission in the University.ipynb` | **Main notebook** – Full analysis, visualization, modeling & comparison |
| `adm_data.csv`                      | Clean dataset (400 rows)                                                |
| `preprocessing.ipynb`               | Unrelated file (football matches) – uploaded by mistake, can be ignored |


## How to Run

```bash
git clone https://github.com/ate-na/uni-admission.git
cd uni-admission
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook "Admission in the University.ipynb"
```
