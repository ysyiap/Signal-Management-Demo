# Signal-Management-Demo---DPA-Risk-Analysis-Pipeline

This repository demonstrates an **adverse drug reaction (ADR) signal management workflow** originally developed for internal post-marketing pharmacovigilance, adapted here with **synthetic, anonymized data** for educational and reproducibility purposes.
It is also my first data analytics project - a capstone submission for the Google Data Analytics Professional Certificate.

Codes, reports and other relevant documentations were refined with AI-assisted editing using OpenAI’s ChatGPT (GPT-5).

---

## Disclaimer

The dataset in this repository is synthetic and anonymized.

No real NPRA data, patient records, or proprietary company information are included.

This project is for educational and demonstration purposes only.

---

## Overview

The analysis script automates the detection and characterization of **ADR signals** reported to regulatory bodies using disproportionality analysis and logistic regression risk-factor modeling.

---

## Objectives

- Clean and standardize ADR datasets for analysis.  
- Filter non-ADR and duplicate entries.  
- Compute disproportionality metrics:  
  - Reporting Odds Ratio (ROR)  
  - Proportional Reporting Ratio (PRR)  
  - Information Component (IC)  
- Identify and visualize potential safety signals.  
- Analyze risk factors (age, dose, gender) using logistic regression.  

---

## Repository Structure

signal-management-demo/
- README.md                  # Project overview and usage instructions
- Signal_Management.Rmd    # Main R Markdown analysis script
- scripts/
  - Synthetic_Sample_ Generator.Rmd     # Creates anonymized synthetic ADR dataset   
- data/
  - npra_anon_sample.csv     # Synthetic dataset used for example run
  - npra_anon_sample_result.csv # Synthetic result from generated dataset
- docs/
  - npra_analysis.html       # Knitted report for viewing via GitHub Pages

 ---
 
## Key Features

- **Automated signal detection** using ROR, PRR, and IC algorithms.  
- **Risk factor analysis** via logistic regression for age, dose, and gender.  
- **Reproducible code structure** following good data science and pharmacovigilance practices.  
- **Anonymized synthetic data** to preserve confidentiality while maintaining analytic realism.  

---

## How to Run

1. Clone or download this repository.  
2. Ensure R (≥ 4.3.0) and RStudio are installed.  
3. Install required packages listed in the knitted report
4. Run in RStudio

---

## Author

Yiap Yong Sheng

Regulatory Affairs Pharmacist | Data Analytics Learner

Coursera Google Data Analytics Capstone Project
