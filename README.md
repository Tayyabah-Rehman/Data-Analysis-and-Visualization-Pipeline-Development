# Task: Titanic Data Analysis & Visualization
A Python pipeline for EDA and visualization on CSV datasets, including data inspection, summary stats, missing value handling, and rich visualizations (bar plots, histograms, scatter plots, correlation heatmap) using Pandas, Matplotlib, and Seaborn.

## Dataset
Titanic passenger dataset (891 rows, 12 columns). Contains passenger information: class, age, fare, sex, cabin, ticket, and survival status.

## Files

| File | Description |
|------|-------------|
| `Task1_ML_Tayyabah_Rehman.ipynb` | Complete Python code for data loading, EDA, and visualizations |
| `titanic.csv` | Raw dataset file |
| `ML_Task Description.docx` | Original task requirements |
| `ML_Titanic Data Analysis.docx` | Analysis report with key findings |

## Key Analysis Results

**Survival:** 38.4% survived, 61.6% died

**Top Predictors:**
- Title: Mrs/Miss survived (50-80%), Mr died (10-15%)
- Deck: Top decks (A/B/C) survived 90-100%
- Pclass: 1st class (62%), 3rd class (25%)
- Fare: Survivors paid $48 avg, non-survivors $22
- Age: Children under 10 survived most

**Missing Data:** Cabin (77%), Age (20%), Embarked (0.2%)

## Conclusion
Wealth + Gender + Age determined survival on Titanic. First class women and children had the highest chance of survival. Third class men had the lowest. Passengers on top decks (closer to lifeboats) survived at much higher rates than those on bottom decks. Small to medium family groups (especially 4 people) survived best, while solo travelers fared worst.

---
