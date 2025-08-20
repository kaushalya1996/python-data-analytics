# Python Data Analytics Starter

A clean, GitHub-friendly template to practice data analytics in Python.

## Structure
```
.
├─ notebooks/            # Jupyter notebooks (EDA, modeling, reports)
├─ scripts/              # Reusable Python modules / data pipeline code
├─ data/
│  ├─ raw/               # Raw input data (ignored by git)
│  └─ processed/         # Cleaned data (ignored by git)
├─ reports/figures/      # Exported charts for README / reports
├─ requirements.txt      # Python dependencies
└─ .gitignore            # Ignores data, venv, and junk files
```

## Quickstart
1. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate      # Windows
   # source .venv/bin/activate   # macOS/Linux
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter and open the EDA notebook:
   ```bash
   jupyter notebook
   ```

## Practice workflow
- Put small sample data into `data/raw/` (e.g., `sample_sales.csv` included).
- Do exploration in `notebooks/01_eda.ipynb`.
- Move reusable logic to `scripts/` (e.g., `data_cleaning.py`).
- Export charts to `reports/figures/` and add them to this README.
- Commit small, often; push to GitHub after each milestone.
- Create branches for features: `feature/cleaning`, `feature/modeling`, etc.
- Open a Pull Request to review your own work before merging.

Happy analyzing!