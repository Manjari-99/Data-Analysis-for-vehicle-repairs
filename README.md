# Data Analysis on Vehicle Repair Industrial Data 
**Author:** Manjari Nandi Majumdar  
**Date:** January 2026  
## Tools & Technologies  

Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn), NLP-based text tagging, Correlation Analysis, Heatmaps  


---

## Summary  

This project analyzes automotive repair and production datasets to identify failure trends, root causes, and cost drivers. The objective was to transform raw operational logs into structured, actionable insights for Quality, Manufacturing, Supply Chain, and Finance stakeholders.

The analysis reveals recurring manufacturing-related leak failures, evidence of early-life (infant mortality) defects, and clear opportunities to reduce warranty spend through predictive maintenance and targeted quality improvements.

---

## Scope of Work  

### Task 1 – Data Validation & Tag Engineering  

- Cleaned and standardized raw repair data  
- Removed deprecated fields and handled missing values  
- Identified critical analytical columns  
- Generated NLP-based tags:
  - **Condition Tags** (how failure occurred)  
  - **Component Tags** (what failed)  
  - **Severity Tags** (impact level)

<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/4f395150-cb93-470b-9249-929b5fa70018" />
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/bba7bd2e-7668-49c0-a828-73da377705ae" />

**Output Files:**  
- `cleaned_data_task1.xlsx`  
 

---

### Task 2 – Data Integration  


- Identified primary keys in both datasets  
- Determined that no logical business join existed  
- Executed **Full Outer Join** to preserve all records  
- Created unified fleet-level dataset
- <img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/06f5be4d-f020-4c2a-933b-61eacef58a31" />
- <img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/599029ae-9c7e-43df-82b6-73bcb3297f1e" />

**Output Files:**  
- `cleaned_data_task2.xlsx`  
- `merged_data_task2and3.xlsx`  


---

## Key Findings  

- **Top Failure Drivers:** Hose leaks and steering-related defects  
- **Infant Mortality Effect:** Newer/lower-mileage vehicles show higher repair costs  
- **Service Volume Surge:** February 2024 spike aligned with component-specific failure clusters  
- **High-Cost Repairs:** Functional and safety-critical failures significantly increase warranty expense  

---
## Business Impact  

Implementation of the identified root-cause improvements would:

- Reduce warranty spend  
- Improve fleet reliability  
- Enable predictive parts positioning  
- Optimize labor and inventory planning  

---


