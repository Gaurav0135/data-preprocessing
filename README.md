# Heart Disease Analysis

This project is a Python notebook for exploring and preprocessing a heart disease dataset stored in `heart.csv`.

The notebook covers:

- basic inspection of the dataset
- exploratory data analysis with plots
- duplicate and missing-value checks
- cleaning `Cholesterol` and `RestingBP` values
- one-hot encoding categorical columns
- standardizing selected numeric features

## Project Files

- `Heart-data.ipynb` - main notebook with analysis and preprocessing steps
- `heart.csv` - source dataset used by the notebook

## Requirements

Install the packages used in the notebook:

- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`

The notebook also includes an optional exploratory step using `sheryanalysis`.

## How to Run

1. Open `Heart-data.ipynb` in Jupyter or VS Code.
2. Make sure `heart.csv` is in the same folder as the notebook.
3. Run the cells from top to bottom.

## Notes

The notebook is focused on data preparation and visualization rather than model training. If you want, you can extend it with train/test splitting and classification models after preprocessing.