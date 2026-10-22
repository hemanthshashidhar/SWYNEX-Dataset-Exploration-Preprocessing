# Titanic EDA and Feature Preparation

## Objective
This project demonstrates exploratory data analysis and preprocessing on the Titanic passenger dataset.

## Contents
- `titanic_eda_preprocessing.ipynb`: Complete Jupyter notebook with EDA, missing-value analysis, imputation, categorical encoding, scaling, train/test splitting, and preprocessing validation.

## Dataset
The notebook loads the public Titanic CSV from the Seaborn data repository:
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv

Target: `survived` (0 = did not survive, 1 = survived).

## Requirements
- Python 3.9+
- pandas
- numpy
- matplotlib
- scikit-learn
- Jupyter Notebook or JupyterLab

Install dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

## Run
1. Clone or download this repository.
2. Start Jupyter:
   ```bash
   jupyter notebook
   ```
3. Open `titanic_eda_preprocessing.ipynb` and run the cells from top to bottom.

An internet connection is needed to download the CSV.

## Main steps
1. Dataset inspection and summary statistics
2. Target distribution and visual EDA
3. Missing-value analysis
4. Feature selection and train/test split
5. Median/mode imputation
6. One-hot encoding and numerical scaling
7. Verification of transformed features

This assignment focuses on data preparation; model training and performance evaluation are left as a possible next step.
