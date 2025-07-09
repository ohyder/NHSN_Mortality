# NHSN_Mortality
Code for the NHSN Mortality Analysis
Analysis Code Repository

**Surgical Urgency and Perioperative Mortality: A National Analysis Using Procedure-Specific Classification**

This repository contains the SAS code used in our study examining the relationship between surgical urgency and inpatient mortality using nationally representative data from the HCUP-NIS and NHSN procedure classification system. This study builds upon and expands findings from Epstein et al. (Anesthesiology, 2025), using enriched methods to examine patterns of diagnosis, procedure, and mortality across elective and non-elective inpatient surgeries.

📊 Study Objectives
Validate prior findings on surgical urgency and inpatient mortality at a national level

Identify procedure categories with disproportionately high inpatient mortality

Use enrichment analysis to detect diagnosis and procedure codes overrepresented in high-risk groups

Compare elective vs non-elective inpatient surgical outcomes using proportional mortality metrics

📁 Repository Structure
📂 /code
README.md              --> This file
SASCode                --> SAS Code File

Methods Summary
Data Source: HCUP-NIS 2022 inpatient discharges

Procedure Classification: CDC NHSN major operating room procedures

Mortality Measures: In-hospital death (died), stratified by elective_surgery_n

Statistical Approaches:

Enrichment analysis using risk ratios and difference in prevalence

Proportional Mortality Analysis (PMA):

Chi-square tests for mortality distribution across urgency categories

References
Epstein et al. Anesthesiology. 2025. [PMID pending]

Rothman et al. Modern Epidemiology, 3rd ed.

Subramanian et al. PNAS. 2005;102(43):15545–50. doi:10.1073/pnas.0506580102

Raw NIS data is not included in this repo due to licensing restrictions.

Code assumes survey design variables (DISCWT, NIS_STRATUM, HOSP_NIS) are available.

Diagnosis and procedure descriptions require format libraries (e.g., $icddx.) or external reference tables.

