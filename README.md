# Smaller Academic Projects – Machine Learning & Data Analysis

Selected original university coursework notebooks demonstrating classical machine learning and exploratory data preprocessing. These are **educational exercises**, not deployed applications.

## Contents

### Bayesian vs. Ridge Regression

**File:** `machine-learning/bayesian-vs-ridge-regression.ipynb`

Compares Ridge regression (including a hyperparameter search) with Bayesian Ridge regression using the California Housing dataset, test-set MSE and R². Uses NumPy, pandas, matplotlib and scikit-learn. The notebook includes the original recorded output/discussion.

### Metropolitan Museum Data Cleaning

**File:** `data-analysis/met-museum-data-cleaning.ipynb`

An exercise exploring data consistency, historical object date fields, data types and outlier detection using pandas and visualization libraries. **The required input `MetObjects.csv` is not included.** You must separately obtain an appropriately licensed Metropolitan Museum of Art open dataset and place the CSV where the notebook expects it (or update the path).

## Run locally

```bash
python -m pip install jupyter numpy pandas matplotlib scikit-learn seaborn
jupyter notebook
```

The California Housing notebook downloads its dataset via scikit-learn, so an internet connection may be needed on the first execution. Notebook environments, dependency versions and all prior outputs have not been independently validated.

## Scope

These notebooks are preserved as coursework samples and may contain Czech commentary. Only selected student project notebooks were included; course tutorial notebooks, completed teaching templates and unrelated materials have been excluded.

## License

No open-source license is granted by this repository. Please contact the author before reuse.
