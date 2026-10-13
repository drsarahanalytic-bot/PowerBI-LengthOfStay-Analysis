# Power BI Project: Hospital Length of Stay Analysis

## Problem Statement
Analyze hospital length of stay data to identify factors affecting patient stay duration, such as gender, BMI, pulse, respiration, and dialysis.

## Tools Used
- Power BI (Power Query, DAX, Visualizations)

## Analysis Steps
1. Imported the cleaned dataset from Excel into Power BI.
2. Used Power Query to add calculated columns:
   - BMI_Category (Normal, Overweight, Obese)
   - Glucose_Status (Normal, High/Diabetes)
   - Respiration_Status (Normal, Bradypnea, Tachypnea)
   - Pulse_Status (Normal, Bradycardia, Tachycardia)
3. Created DAX Measures:
   - Total Patients
   - Average Length of Stay
4. Built visualizations:
   - Card (Total Patients)
   - Card (Average Length of Stay)
   - Pie Chart (Gender Distribution)
   - Bar Chart (BMI Category)
   - Column Chart (Dialysis)
   - Bar Chart (Pulse Status)
   - Bar Chart (Respiration Status)
5. Assembled a dashboard combining all visuals.

## Key Results
- Total patients: 100,000
- Average length of stay: 4 days
- Patients with dialysis have longer stays.
- BMI and Glucose statuses show significant distribution.

## Files
- `Data/` – Source data (LengthOfStay.csv).
- `PowerBI/` – Power BI file (length_of_stay_dashboard.pbix).
- `Screenshots/` – Images of all visualizations.

## Author
Sarah Fayez – Medical Student & Data Analyst