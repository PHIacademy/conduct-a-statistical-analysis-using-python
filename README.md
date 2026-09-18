# MSc in AI Capstone #2: Conduct a Statistical Analysis Using Python Project

**Repository:** <https://github.com/PHIacademy/conduct-a-statistical-analysis-using-python.git>

## Project Description

This project performs a complete, reproducible statistical analysis of the Prosper Loan Data dataset. It loads and cleans 113,937 peer-to-peer loan listings, explores descriptive statistics and key variable distributions, builds three visual models, and tests whether a borrower's Prosper-assigned risk score (`ProsperScore`) is significantly associated with whether a loan is completed or ends in default.

## File Structure

```
.
├── README.md
├── Statistical_Analysis_Report.pdf
├── analysis.ipynb
├── prosper-loan-data-variable-definitions.xlsx
├── prosperLoanData.csv
└── requirements.txt
```

- `analysis.ipynb` — a Jupyter Notebook containing the full workflow: data ingestion, data cleaning (out-of-range value removal, duplicate removal), descriptive statistics, three labeled visual models with comparative interpretation, a Welch's *t*-test hypothesis test with stated hypotheses and effect size, and a final notebook summary.
- `requirements.txt` — the Python dependencies needed to run the notebook.
- `Statistical_Analysis_Report.pdf` — a written APA-formatted report with academic citations, covering the overview, dataset description, methods, results, a non-technical interpretation, and limitations/bias discussion (see separate report).
- `prosper-loan-data-variable-definitions.xlsx` — the data dictionary describing every column in the raw dataset.

## Dataset

**Prosper Loan Data** (peer-to-peer loan listings from the Prosper.com lending platform)
Source: [Kaggle — Prosper Loan Data](https://www.kaggle.com/datasets/henryokam/prosper-loan-data)
File used: `prosperLoanData.csv`

## How to Run the Project

### 1. Install dependencies

```
pip install -r requirements.txt
```

### 2. Get the dataset

Download `prosperLoanData.csv` from the [Kaggle dataset page](https://www.kaggle.com/datasets/henryokam/prosper-loan-data)
and place it in the same folder as `analysis.ipynb`.

### 3. Run the notebook

```
jupyter notebook analysis.ipynb
```

Run all cells from top to bottom. The notebook should execute without errors and reproduce all cleaning steps, tables, visualizations, and the hypothesis test results.
