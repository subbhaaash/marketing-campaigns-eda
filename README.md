# Marketing Campaigns — EDA & Hypothesis Tests

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/subbhaaash/marketing-campaigns-eda/blob/main/MARKETING_CAMPAIGNS.ipynb)
[![View in nbviewer](https://img.shields.io/badge/View%20in-nbviewer-blue)](https://nbviewer.org/github/subbhaaash/marketing-campaigns-eda/blob/main/MARKETING_CAMPAIGNS.ipynb)
[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/subbhaaash/marketing-campaigns-eda/HEAD?labpath=MARKETING_CAMPAIGNS.ipynb)

Concise EDA on the Marketing Campaigns dataset using the 4Ps (People, Product, Place, Promotion).  
Focus: simple pipeline, clear visuals, and four hypothesis tests.

## Highlights
- Standardized **Education** and **Marital_Status**; numeric **Income** with **group-median imputation**.
- New features: **Children**, **Age**, **TotalSpending**, **TotalPurchases**.
- Visuals: histograms, boxplots, **correlation heatmap**, and five required business charts.
- Tests: ANOVA (age vs store share), Welch t-test (children vs web share), Pearson correlation (online vs store), Welch t-test (USA vs Rest).

## Results at a glance
- **H1 (Age vs Store Share):** groups show a **significant** difference (ANOVA, p < 0.05).
- **H2 (Children vs Web Share):** users with children have **higher** web share (Welch t-test, p < 0.05).
- **H3 (Online vs Store):** **negative correlation** between online (Web+Catalog) and store purchases (Pearson, p < 0.05).
- **H4 (USA vs Rest on TotalPurchases):** **no significant difference** (Welch t-test, p ≥ 0.05).

## Project structure
- `MARKETING_CAMPAIGNS.ipynb` — main analysis
- `requirements.txt` — quick run for Binder/Colab

## How to run
1) Keep `marketing_data.csv` in the same folder.  
2) Open `MARKETING_CAMPAIGNS.ipynb` in Jupyter.  
3) Run → **Run All Cells**.

## Requirements
pandas, numpy, matplotlib, seaborn, scipy




