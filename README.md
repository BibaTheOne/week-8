# COVID-19 Global Trends — Analysis Report

This repository contains a Jupyter Notebook for analyzing global COVID-19 trends using a Kaggle / Johns Hopkins dataset (preferred) or Our World in Data (OWID) as a fallback.

## Files
- `covid19_analysis.ipynb` — Jupyter notebook with data loading, cleaning, EDA, visualizations, and insights.
- `README.md` — This file.
- (Optional) `owid-covid-data.csv` or your Kaggle CSV files — place them in the repo root to use locally.

## How to run
1. Make sure you have Python 3 and Jupyter installed.
2. Optional but recommended: create a virtual environment and install dependencies:
```bash
python -m venv venv
source venv/bin/activate        # macOS / Linux
venv\Scripts\activate         # Windows PowerShell
pip install pandas matplotlib seaborn plotly
```
3. Place your Kaggle CSV (e.g., `covid_19_data.csv`) in the same folder as the notebook, or allow the notebook to download OWID data.
4. Open the notebook and run cells:
```bash
jupyter notebook covid19_analysis.ipynb
```

## Dataset sources
- Kaggle — Johns Hopkins University (JHU CSSE) COVID-19 datasets (downloadable from Kaggle).
- Our World in Data (OWID): https://covid.ourworldindata.org/data/owid-covid-data.csv

## Notes
- The notebook auto-detects common Kaggle filenames and falls back to OWID if none are found.
- For map visualizations, install `plotly`.

## License
This project is provided for educational use.
