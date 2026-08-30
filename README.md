# COVID-19 Data Analysis — India

An exploratory Jupyter notebook using a checked-in historical India COVID-19 dataset. The project practices time-series cleaning, aggregation, visualization, and interpretation with Python.

## Repository contents

- `COVID-19.ipynb`: exploratory analysis and visualizations
- `covid_19_india.csv`: historical analysis snapshot

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install jupyter pandas numpy matplotlib seaborn
jupyter lab
```

Open `COVID-19.ipynb` and run the cells from top to bottom.

## Responsible interpretation

This is a historical learning analysis, not a live public-health dashboard. Confirm the dataset's source, reporting period, definitions, revisions, and missing-value conventions before citing results. Case counts are affected by testing and reporting practices; descriptive correlations do not establish causation. Do not use this notebook for medical or public-health decisions.

## License

Code is available under the [MIT License](LICENSE). The dataset remains subject to its original publisher's terms.
