# SAS-Clinical-Phase1-TAS114-Capecitabine-SDTM-ADaM-TLFs

## Project Overview

This project demonstrates an end-to-end clinical data workflow for a **Phase 1 oncology study** evaluating the combination of **TAS-114 and Capecitabine**. The objective is to simulate real-world clinical trial data processing aligned with **CDISC standards**, including SDTM, ADaM, and TLF generation using SAS.

---

##  Objectives

* Transform raw clinical trial data into **SDTM-compliant datasets**
* Create **analysis-ready ADaM datasets**
* Perform **safety and pharmacokinetic (PK) analysis**
* Generate **Tables, Listings, and Figures (TLFs)**
* Ensure **regulatory compliance and traceability**

---

## Study Context

* **Study Type:** Phase 1 Oncology Clinical Trial
* **Therapeutic Area:** Oncology
* **Treatment:** TAS-114 + Capecitabine
* **Focus:** Safety, tolerability, and pharmacokinetics

---

##  Workflow

### 1. SDTM Planning & Data Mapping

* Reviewed raw CRF datasets
* Mapped data into SDTM domains:

  * DM (Demographics)
  * AE (Adverse Events)
  * LB (Laboratory Data)
  * VS (Vital Signs)

---

### 2. ADaM Dataset Creation

* Developed analysis-ready datasets:

  * ADSL (Subject-Level Analysis Dataset)
  * ADAE (Adverse Events Analysis Dataset)
  * ADVS (Vital Signs Analysis Dataset)
* Derived:

  * Baseline values
  * Change from baseline
  * PK parameters

---

### 3. Safety Analysis

* Identified and summarized:

  * Adverse Events (AEs)
  * Serious AEs
  * Dose-Limiting Toxicities (DLTs)
* Performed lab shift and toxicity analysis

---

### 4. Pharmacokinetics (PK)

* Calculated key PK parameters:

  * Cmax (Maximum Concentration)
  * Tmax (Time to Cmax)
  * AUC (Area Under Curve)
* Generated concentration-time profiles

---

### 5. TLF Generation

* Created:

  * Summary Tables
  * Patient Listings
  * Graphical Figures
* Used SAS procedures for reporting:

  * PROC REPORT
  * PROC TABULATE
  * PROC SGPLOT

---

### 6. Regulatory & Quality Control

* Ensured:

  * Dataset traceability (SDTM → ADaM → TLF)
  * define.xml documentation
  * QC validation checks
* Prepared submission-ready outputs

---

### 7. Reporting & Insights

* Compiled TLF outputs into study report
* Interpreted safety and PK findings
* Supported clinical decision-making

---

## 🛠️ Tools & Technologies

* **SAS (Base SAS, SAS/STAT)**
* CDISC Standards:

  * SDTM
  * ADaM
* Microsoft Excel (data review)

---

## 📊 Key Skills Demonstrated

* Clinical SAS Programming
* CDISC SDTM & ADaM Implementation
* Statistical Analysis & TLF Generation
* Pharmacokinetics (PK) Analysis
* Regulatory Submission Preparation
* Clinical Data Quality & Traceability

---

## 📁 Project Structure

```
├── data/
│   ├── raw/
│   ├── sdtm/
│   ├── adam/
│
├── programs/
│   ├── sdtm/
│   ├── adam/
│   ├── tlf/
│
├── outputs/
│   ├── tables/
│   ├── listings/
│   ├── figures/
│
├── docs/
│   ├── define.xml
│   ├── study_report.pdf
│
└── README.md
```

---

## Conclusion

This project simulates a real-world **oncology Phase 1 clinical trial workflow**, showcasing the complete lifecycle from raw data to regulatory-ready outputs. It highlights strong expertise in **clinical data standards, SAS programming, and biostatistical analysis**.

---

##  Author

**Sumit Choudhary**
Clinical SAS Programmer | Oncology SDTM/ADaM/TLFs | Biostatistics & Data Analysis

---
