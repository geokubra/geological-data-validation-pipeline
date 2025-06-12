# geological-data-validation-pipeline
Automated Python notebooks for validating geological exploration data
# Geological Data Validation Pipeline

This repository includes three automated data validation notebooks used in mineral exploration and resource modeling processes. Each notebook is designed to detect inconsistencies, missing values, and structural mismatches between lab-received raw data and final reporting datasets.

## 📁 Notebooks

1. **Raw_Sample_Data_Validation.ipynb**  
   - Compares raw sample entries between received and reported Excel files.
   - Handles specific checks for elements like Na, Na₂O, K₂O, Cl.
   - Outputs detailed discrepancy reports to Excel.

2. **XRD_Data_Validation.ipynb**  
   - Normalizes and compares XRD mineralogical data.
   - Highlights differences and applies corrections.
   - Tracks updated vs original states with visual markers.

3. **Density_Data_Validation.ipynb**  
   - Validates consistency of bulk density measurements.
   - Detects column naming mismatches, missing values, and structural differences.
   - Outputs a comprehensive Excel-based comparison report.

## 🧪 Tools
- Python 3.10+
- Pandas
- NumPy
- Openpyxl
- Jupyter Notebook

## 💬 Author
Developed by Kübra Akbulut | Resource Geologist 
