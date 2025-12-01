# Learning Today: What Are Students Telling Us?

This repository contains the full code, data processing workflows, and results of the project  
**“Learning Today. What Are Students Telling Us?”**  
focused on the analysis of academic performance in Barcelona and Catalonia under different socioeconomic, institutional, and educational conditions.

The project is based exclusively on **open public datasets** from the Generalitat de Catalunya, IDESCAT, and Open Data Barcelona.

---

## 👥 Research Team

- Ana Cano Herranz  
- Julia Carrillo Alonso  
- Ander Gabarrús Ordóñez  
- Quintín Huertas Murcia  
- Anna Szymanski Cortés  

Contact: `andergabarrus.val@gmail.com`

---

## 🎯 Research Objectives

This project investigates:

- The **evolution of academic performance** in Barcelona and Catalonia.
- The **relationship between socioeconomic context and school success**.
- The **impact of school ownership (public vs private)** on academic outcomes.
- The **effect of special educational needs (NESE)** on students’ performance.
- The **post-compulsory educational trajectories** of students after 4th ESO.
- The **impact of COVID-19 on academic progression**.
- Students’ growing **detachment from traditional academic paths**.

---

## 🗂️ Data Sources

All datasets are publicly available and fully anonymized:

- ESO academic results (2013–2023)
- Basic competencies test results (4º ESO)
- Territorial Socioeconomic Index (IST)
- Rent per capita by census section
- Population census data
- Educational trajectories (ESO → Bachillerato / FP)
- University enrollments
- NESE (special educational needs)
- Barcelona district geometries (JSON)

Formats include **CSV, XLSX and JSON**.

---

## 💾 Repository Structure

```text
data/
├── raw/                 # Original datasets (unmodified)
├── processed/           # Cleaned and transformed datasets
├── ana/
├── ander/
├── anna/
├── julia/
├── quintin/

notebooks/
├── notebook_ana.ipynb
├── notebook_ander.ipynb
├── notebook_anna.ipynb
├── notebook_julia.ipynb
├── notebook_quintin.ipynb

scripts/                 # Data processing and visualization scripts
results/                 # Generated figures and tables
