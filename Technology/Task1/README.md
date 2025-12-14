# Task 1 – Telemetry Data Unification  
Deloitte Australia Technology Consulting Virtual Internship

##  Overview
The goal of this task was to unify two different machine telemetry formats into a single, standardised structure. The input data included JSON messages captured from manufacturing devices across Daikibo factories.

##  Objectives
- Convert multiple telemetry formats (flat vs nested) into one unified output.
- Parse and normalise timestamps (ISO → milliseconds).
- Combine device, location, and status fields into a consistent schema.
- Ensure the final output matches `data-result.json` exactly.

##  Technologies Used
- Python  
- JSON parsing  
- Datetime processing  
- Unit testing (unittest)

##  Files
- `main.py` – Conversion logic + test execution  
- `data-1.json` – Input format 1  
- `data-2.json` – Input format 2  
- `data-result.json` – Expected unified output  

## ▶ How to Run
```bash
python3 main.py
