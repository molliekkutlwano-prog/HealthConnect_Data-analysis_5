# HealthConnect_Data-analysis_5
# HealthConnect Clinic — Week 8 Final Analytics, Dashboard & Decision Support Package

**Author:** Kutlwano Mmoloki Gabanthate  
**Role:** Data Analytics Track Lead  
**Institution:**AnalystLab Africa Experience Lab  
**Project:** HealthConnect Clinic Analytics & Multidisciplinary Decision Support System  
**Deliverable:** Week 8 Final Integrated Analytics Package & Executive Decision Support System  
**Technical Stack:** Python (`pandas`, `numpy`, `matplotlib`, `seaborn`, `reportlab`)  
**Date:** September 2026  

---

## 📌 Project Executive Summary

This repository contains the final Week 8 analytical engine, dataset validation pipeline, dynamic dashboard visual generator, and decision support architecture for the **HealthConnect Clinic System**. 

Building upon the testing readiness and data hygiene fixes established in Week 7, Week 8 integrates the **Data Analytics Track** outputs into a unified, multidisciplinary solution alongside **Data Science**, **Healthcare Operations**, **ML Engineering**, **Generative AI**, and **Project Management**. 

Programmatic validation across 1,000 ground-truth clinic appointment records verified that operational friction drivers—specifically in-clinic wait times (`waiting_time_minutes`) and travel distance (`distance_to_clinic_km`)—dictate patient defaults far more reliably than uncalibrated static risk tiers ($\text{ROC-AUC} \approx 0.45$). By operationalizing a calibrated decision probability threshold ($<0.30$), HealthConnect optimizes default recall and powers automated WhatsApp patient outreach workflows.

---

## 📁 Repository Structure

```text
├── HealthConnect_With_Risk_Scores.xlsx        # Raw ground-truth clinic dataset (1,000 records)
├── run_healthconnect_week8_pipeline.py        # Automated test suite (TS-01 to TS-05) & analytical pipeline
├── generate_dashboard_evidence.py            # Matplotlib/Seaborn executive visual dashboard generator
├── create_pdf.py                              # ReportLab script for automated PDF report generation
├── HealthConnect_Week8_Final_Report.pdf       # Unified Week 8 Final Decision Support Package Report
├── healthconnect_executive_dashboard.png      # High-resolution 4-panel executive visual dashboard artifact
├── DataScience_Feature_Importance_Handoff.csv # Serialized feature importance ranking file from Week 6/7
├── Professional_Development_Branding_Guide.md # LinkedIn, X, GitHub branding & post guides (#AnalystLabAfrica)
├── HealthConnect_Week8_Presentation_Script.md # 5-10 min individual presentation script & deck outline
└── README.md                                  # Complete repository documentation & execution guide
