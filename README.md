# EOL Measurement System Analysis with ANOVA and Decision Risk

## Project overview
This project evaluates a synthetic End-of-Line (EOL) measurement system against an external parallel reference setup using pressure and flow data.

The analysis studies whether the EOL system is statistically and practically comparable to the reference setup, especially in threshold-based Pass/Fail decisions.

## Main methods
- Exploratory Data Analysis
- Probability Density Function (PDF) analysis
- Hypothesis Testing
- ANOVA
- Decision-risk analysis
- Reproducible research documentation

## Data sources
The project is based on two independent data sources within the synthetic design:
- EOL machine measurements
- External parallel setup measurements from:
  - CEM DT-8890 pressure meter
  - TSI 5200 airflow meter

## Main findings
The EOL system is broadly comparable to the external reference setup, but small differences become practically important near the Pass/Fail threshold.

The analysis shows that:
- paired source differences are statistically significant
- time-related effects are more important than channel effects in the formal tests
- false fail outcomes are more frequent than false pass outcomes
- agreement is high overall, but lower near the threshold

## Files in the repository
- `measurement_system_analysis.ipynb` — main project notebook
- `synthetic_eol_measurement_data.csv` — generated dataset
- `requirements.txt` — required Python libraries
- `README.md` — project summary

## How to run
1. Open the notebook in Jupyter Notebook.
2. Install the required Python libraries from `requirements.txt`.
3. Run all cells from top to bottom.

## Project status
The notebook is complete and ready for submission.