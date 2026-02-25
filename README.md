# Identify Customer Segments

## Project Overview

This project applies unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. The goal is to use demographics data to cluster the general population into groups, and then see how customers of the company map onto those clusters to identify which segments are overrepresented or underrepresented among the company's customer base.

## Datasets

- **Udacity_AZDIAS_Subset.csv** — Demographics data for the general population of Germany (891,211 persons × 85 features)
- **Udacity_CUSTOMERS_Subset.csv** — Demographics data for customers of a mail-order company (191,652 persons × 85 features)
- **AZDIAS_Feature_Summary.csv** — Summary of feature attributes including information level, data type, and codes for missing/unknown values
- **Data_Dictionary.md** — Detailed description of all features in the dataset

## Methods

1. **Data Preprocessing** — Handling missing values, feature re-encoding, and feature engineering
2. **Feature Transformation** — Applying feature scaling and dimensionality reduction (PCA)
3. **Clustering** — Using K-Means clustering to segment the general population
4. **Customer Comparison** — Mapping customer data onto the clusters to identify target segments

## Files

| File | Description |
|------|-------------|
| `Identify_Customer_Segments.ipynb` | Jupyter Notebook with the full analysis |
| `Identify_Customer_Segments.html` | HTML export of the notebook |
| `Data_Dictionary.md` | Feature-level documentation |
| `AZDIAS_Feature_Summary.csv` | Feature summary table |
| `data.zip` | Compressed dataset files |

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Usage

1. Extract `data.zip` to obtain the CSV data files.
2. Open `Identify_Customer_Segments.ipynb` in Jupyter Notebook.
3. Run all cells to reproduce the analysis.

## License

This project is part of the Udacity **Intro to Machine Learning with TensorFlow Nanodegree Program**.
