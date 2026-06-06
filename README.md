# HR Analysis

An end-to-end HR data analysis project built in Python, covering data cleaning, exploratory data analysis, and business insight generation across 1000+ employee records.

## Overview

This project analyzes HR data to uncover patterns in employee demographics, performance, attrition, and compensation. The goal is to provide actionable insights that support data-driven HR decisions.

## Sample Visualizations

<table>
  <tr>
    <td><img width="500" alt="status_performance_count" src="https://github.com/user-attachments/assets/cd69c8fd-3c70-4145-b80b-3a5e2eff1e14" /></td>
    <td><img width="500" alt="salary_by_department" src="https://github.com/user-attachments/assets/5b13ebfb-cfc9-4f0a-9ec1-6b9dd52f347c" /></td>
  </tr>
</table>






## Project Structure

```
hr-analysis/
├── data/               # Raw and processed datasets
├── plots/              # Generated visualizations
├── report/             # Final report output
├── hr_analysis.ipynb   # Main analysis notebook
├── requirements.txt
└── .gitignore
```

## Key Analyses

- **Data Cleaning** — handling missing values, type casting, outlier detection
- **Exploratory Data Analysis (EDA)** — distributions, correlations, and group comparisons
- **Attrition Analysis** — identifying factors that predict employee turnover
- **Department & Role Insights** — performance and compensation breakdowns by department
- **Business Recommendations** — data-backed suggestions for HR strategy

## Setup

```bash
# Clone the repo
git clone https://github.com/horridhaider/hr-analysis.git
cd hr-analysis

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook hr_analysis.ipynb
```

## Requirements

- Python 3.8+
- See `requirements.txt` for full list of dependencies

## Dataset

The dataset contains 1000+ employee records with fields including department, job role, salary, performance rating, years at company, and attrition status.

## License

MIT
