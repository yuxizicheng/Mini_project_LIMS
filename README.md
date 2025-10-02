# Mini_project_LIMS
## LIMS QC Mini-Project: Automated Pass/Fail Flagging

This Python script automates QC result evaluation, simulating a LIMS workflow in a pharmaceutical lab. Specifications are stored in code (like in LIMS) and can be updated as standards change.

## Key Features
- Define test specifications:
  - Numeric limits (e.g., Plasmid Retention %, Cell Viability)  
  - Categorical allowed values (e.g., Product Expression Result)
- Flag samples as Pass/Fail using the `flag_result` function
- Add `"Pass/Fail"` column to the dataset
- Generate Excel report with visual highlights:
  - `"Pass"` in green  
  - `"Fail"` in red, entire row highlighted for clarity
- Save final results to `Bacterial Cell Bank_qc_results_colored.xlsx`
