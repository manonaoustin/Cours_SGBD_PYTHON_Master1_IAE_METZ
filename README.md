# Cours_SGBD_PYTHON_Master1_IAE_METZ

# BNP Paribas : Risk Data Aggregation Platform

## Project context :

**Institution:** IAE Metz - Université de Lorraine  
**Program:** Master 1 Finance Internationale  
**Course:** Financial Database Management  
**Professor:** Sitraka Matthieu FORLER  
**Academic Year:** 2025–2026 

---

## Our Team :

| Name | Role |
|------|------|
| [Rose LECLERC] | Company Overview & Problem Statement |
| [Manon AOUSTIN] | BCBS 239 Framework & Data Requirements |
| [Zineb RACHIDI] | Database Selection & Architecture Design |
| [Elodie JIANG] | Justification, Dataset & Conclusion |

---

## Our Research Question :

How can BNP Paribas build a real-time database to group risk data from 65 countries and follow BCBS 239 rules ?

---

## Why BNP Paribas ? :

- Largest bank in France, top 8 globally
- G-SIB designated by the FSB since 2011
- Subject to BCBS 239 since January 2016
- Manages 2.9 trillion euros across 65 countries

---

## Our Database Recommendation :

We propose a three-layer database architecture :
- PostgreSQL - golden source - accurate storage 
- Snowflake - analytics - regulatory reports  
- Redis - real-time - intraday data

---

## BCBS 239 Compliance Mapping :

| Principle | Requirement | Our Solution |
|-----------|-------------|--------------|
| P3 Accuracy | Error rate below 0.01% | PostgreSQL |
| P4 Completeness | Coverage above 99.5% | Centralized ingestion |
| P5 Timeliness | Same day to next day | Redis + Snowflake |
| P6 Adaptability | Any report under 24h | Snowflake |

---

## Repository Contents :

| File | Description |
|------|-------------|
| README.md | Project overview |
| presentation.pptx | Full slide deck |
| sample_dataset.csv | Sample trading positions |



## Contact us 
- [Manon Aoustin](https://www.linkedin.com/in/manon-aoustin-158a26382/)
- [Elodie Jiang] (https://www.linkedin.com/in/elodie-j-b326632b2)
