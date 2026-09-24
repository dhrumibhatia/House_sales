# House Sales Analysis

This repository contains a data analysis project for the **DataCamp Associate Data Scientist Examination Test**. The project explores house sales data for RealAgents, a real estate company operating across a metropolitan area.

## Project overview

The analysis uses historical house listings and sales to investigate factors associated with house sale prices. The included Jupyter Notebook documents the data exploration, preparation, analysis, and modelling workflow.

## Repository contents

| File | Description |
| --- | --- |
| `notebook.ipynb` | Main Jupyter Notebook containing the analysis. |
| `train.csv` | Training data containing house characteristics and known sale prices. |
| `validation.csv` | Validation data containing house characteristics without sale prices. |
| `house_sales.csv` | Additional house sales data containing sale prices and some missing or inconsistent values. |

## Data fields

The datasets include information such as:

- `house_id` — Unique identifier for each property.
- `city` — City where the property is located.
- `sale_price` — Sale price of the property; available in datasets with target values.
- `sale_date` — Date the property was sold.
- `months_listed` — Number of months the property was listed before sale.
- `bedrooms` — Number of bedrooms.
- `house_type` — Type of property, such as detached, semi-detached, or terraced.
- `area` — Property area in square metres.

## Getting started

### Requirements

- Python 3.11
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Scikit-learn

### Run the notebook

1. Clone this repository:

   ```bash
   git clone https://github.com/dhrumibhatia/House_sales.git
   cd House_sales
   ```

2. Install the required packages, if needed:

   ```bash
   pip install jupyter pandas numpy matplotlib seaborn scikit-learn
   ```

3. Start Jupyter:

   ```bash
   jupyter notebook
   ```

4. Open `notebook.ipynb` and run the cells in order.

## Analysis workflow

The notebook covers the typical stages of a data science project:

1. Load and inspect the data.
2. Identify missing, inconsistent, or incorrectly formatted values.
3. Clean and transform the relevant features.
4. Explore relationships between property characteristics and sale prices.
5. Build and evaluate a predictive model, where applicable.
6. Generate predictions for validation data.

## Notes

The CSV files are part of an examination challenge and are retained in their original repository format. Before modelling, inspect the data carefully because some values may require cleaning or standardisation, including missing city values, missing listing durations, abbreviated house types, and area values that include units.

## License

No license has been specified for this repository.
