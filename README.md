# MLOps Unit-II Practical Submission

## Files
- `MLOps_UnitII_Monitoring_Logging_Practical.ipynb` — notebook containing the monitoring, metrics, drift, reporting, and logging tasks.
- `logs/` — log output is created here when the notebook is run.
- `monitoring_reports/` — CSV reports are created here when the notebook is run.

## Run instructions
1. Install Python 3.10+ and Jupyter Notebook, or use Google Colab.
2. Place `kidney_disease_cleaned.csv` in the same folder as the notebook.
3. Open the notebook and run cells from top to bottom.
4. Check the generated CSV reports in `monitoring_reports/` and the log file in `logs/`.

## Dependencies
The first notebook cell installs pandas, NumPy, scikit-learn, and matplotlib.

## Dataset note
The dataset was not included with the uploaded teaching files. You must supply the exact `kidney_disease_cleaned.csv` dataset expected by the assignment. The notebook intentionally raises a clear error if it is missing; it does not invent dataset rows or fabricated metric results.

## Safety and interpretation
This is an educational MLOps exercise only, not a medical diagnostic system. The shifted-data experiment is synthetic; data drift alone does not prove performance degradation.
