# COVID-19 Exploratory Analysis for India

A notebook-based exploratory data analysis of state-level COVID-19 records in India. The project focuses on data preparation, aggregation, time-series visualization, and comparative analysis of confirmed cases, recoveries, deaths, and active cases.

## Analytical workflow

- Load and inspect the state-level dataset
- Normalize dates and derive active-case measures
- Aggregate confirmed, recovered, and death counts by state and date
- Compare state-level patterns
- Visualize time trends with Matplotlib, Seaborn, and Plotly

## Repository contents

- `COVID-19.ipynb` — complete exploratory workflow
- `covid_19_india.csv` — project dataset

## Environment

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook "COVID-19.ipynb"
```

## Interpretation notes

This is a historical exploratory project, not a current public-health dashboard. Results depend on the reporting definitions, update cadence, and completeness of the included dataset. The analysis should not be used for medical or policy decisions.

## Skills demonstrated

Pandas aggregation, temporal analysis, data cleaning, exploratory visualization, and communicating state-level comparisons.

## Author

**Purnendu Kale** · [LinkedIn](https://www.linkedin.com/in/purnendukale/)
