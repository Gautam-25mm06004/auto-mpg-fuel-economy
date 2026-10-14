# What Determines a Car's Fuel Economy? (Auto MPG)

Regression study of fuel economy on the classic Auto MPG data: cleaning, exploratory analysis, model comparison and interpretation of what drives miles per gallon.

## Contents

| File | What it does |
|---|---|
| `notebooks/auto_mpg_fuel_economy_study.ipynb` | What Determines a Car's Fuel Economy? |

Notebooks are saved with the outputs of their last run, so results and figures can be read on GitHub without running anything.

## Data

UCI "Auto MPG" dataset.

## How to run

The notebooks were developed on Google Colab. Upload a notebook to Colab (File → Upload notebook) and run the cells in order; the first cells install anything missing. To run locally in VS Code instead: `python -m venv .venv`, activate it, `pip install -r requirements.txt jupyter`, then open the notebook and pick the `.venv` kernel. Cells that mount Google Drive (`google.colab`) can be skipped locally if the data files are placed next to the notebook.

Python packages used: `ipython`, `joblib`, `lightgbm`, `matplotlib`, `numpy`, `pandas`, `scikit-learn`, `scipy`, `seaborn`, `xgboost` (see `requirements.txt`).

## License

MIT, see `LICENSE`.
