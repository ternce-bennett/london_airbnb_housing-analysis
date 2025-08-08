# London Airbnb and Housing Affordability Analysis

## Overview

This project explores the relationship between Airbnb activity and housing affordability in London boroughs. Specifically, it looks at the number of Airbnb listings and average nightly prices compared to median rental prices (mock data).

## Dataset

- **Airbnb listings**: Downloaded from [Inside Airbnb](http://insideairbnb.com/get-the-data.html) — `listings.csv` file for London boroughs.
- **Rent data**: Currently mock/generated values for median rents by borough. You can replace these with real data later.

## Analysis

- Data cleaning and preparation using Python (`pandas`).
- Group listings by borough, calculate listing counts and average prices.
- Merge Airbnb data with mock rent data.
- Visualize relationships with scatterplots.
- Calculate correlations between Airbnb metrics and rents.

## How to Run

1. Make sure you have the files `analysis.ipynb` and `listings.csv` in the same folder.
2. Open the project in one of these ways:
   - **Locally**: Use [Jupyter Notebook](https://jupyter.org/install) or [JupyterLab](https://jupyter.org/install) after installing Python.
   - **Online**: Use [GitHub Codespaces](https://github.com/features/codespaces) or [Google Colab](https://colab.research.google.com/).
3. Run all the notebook cells in `analysis.ipynb`.
4. View the plots and correlation results that appear inline.

## Requirements

Make sure you have these Python packages installed:

```bash
pip install pandas matplotlib seaborn
