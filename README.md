# Hospital-Operations-Dashboard
Review of Hospital Dashboard
**Author:** Mayowa Adeboye
**Date:** 2025-11-18
---
## Project Background
City General Hospital is facing a critical operational crossroads. Despite high patient volumes, the facility is struggling with resource misalignment (such as preparing beds for teenagers while seniors dominate visits), a quality crisis in laboratory testing, and uneven staff workloads. These inefficiencies are compounded by financial leakages from specific insurance providers and significant inventory risks regarding medication stock.
---
## Project Objective
- Identify root causes of ER congestion and resource waste
- Analyze patient flow, staff workload, medication stock, lab efficiency, and finance data
- Build an interactive Excel dashboard to inform board-level decisions
- Recommend prioritized actions to stabilize hospital operations
---
## Datasets- **Patients.csv / Patients.xlsx** — patient_id, age, gender, visit_date, department,
---
## Dashboard Features
![Hospital Operations Dashboard](Screenshot%28745%29.png)
- Key KPIs: total patients,
- Visuals: time-series of visits, age-group distributions, staff workload heatmap, stock expiry
chart, departmental revenue breakdown
- Interactivity: slicers/filters for Department, Date range, Age group, Staff role, Medication type
---
## Key Findings
- Senior Demographic Dominance: Seniors (65+) are the top patient demographic, yet current bed configurations do not reflect this.
- Extreme Workload Imbalance: The busiest doctor handles 20 times the average patient workload.
- Inventory mismatch: critical drugs are short while others are near expiry
- Inventory Risk: High-demand drugs like Lipitor and Ibuprofen require higher safety stock, while low-demand medications face expiration risks.
- Financial Leakage: Aetna has a significantly lower average payment ($25,427.70) compared to other providers like Cigna ($25,727.04)
---
## Recommendations
1. Resource Reallocation: Immediately shift hospital capacity to Senior-focused beds and specialized equipment.
2. Quality Intervention: Dispatch engineering teams to Houston Methodist and Johns Hopkins within 48 hours to repair or recalibrate lab machinery.
3. Scheduling Optimization: Mandate higher staffing levels on Tuesdays to handle predictable ER congestion and balance physician shifts.
4. Financial Audit: Initiate a targeted contract and billing review for Aetna to address the lower reimbursement rates.
5. Audit billing and implement a claims follow-up workflow to reduce unpaid claims
6. Task Force Formation: Approve an Implementation Task Force to oversee these data-driven transitions.
---
## Tools & Techniques
- Microsoft Excel (Pivot Tables, Pivot Charts, Slicers) for data aggregation
- Data cleaning and transformation in Excel
- Dashboard layout and visualization best practices
- Basic descriptive analytics and KPI design
---
## Project Files (included)
- `City_Hospital_Dataset.xlsx` — interactive dashboard file
- `/City_Hospital_Dataset/` — raw data files used for analysis (CSV / XLSX)
- `Mayowa's_Data_Driven_Review.pptx` — boardroom slide deck (10–12 slides)
- `README.md` — this documentation
- `Screenshot(745).png` - Dashboard Picture
---## How to Run / View
1. Open `City_Hospital_Dataset.xlsx` in Excel (desktop recommended)
2. Enable content (if prompted) to allow Pivot Tables and slicers to work
3. Use slicers to filter by Department, Date, Age group, etc.
4. Refer to `Mayowa's_Data_Driven_Review.pptx` for a summary of insights and recommended actions
---
## Contact
Mayowa Adeboye
Email: _Adeboyemayowa86@gmail.com
LinkedIn: _http://www.linkedin.com/in/mayowaadeboye_
