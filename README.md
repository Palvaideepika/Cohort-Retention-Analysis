# Cohort Retention Analysis

## Project Overview

This project analyzes customer retention using cohort analysis on the Online Retail II dataset. Customers are grouped by their first purchase month, and their repeat purchasing activity is measured over subsequent months.

## Objectives

* Identify monthly customer cohorts.
* Calculate customer retention rates.
* Visualize retention patterns using a heatmap.
* Generate business insights from customer purchasing behavior.

## Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

## Methodology

1. Loaded and explored the Online Retail II dataset.
2. Removed records with missing customer IDs, duplicates, and invalid purchase quantities or prices.
3. Assigned each customer to their first purchase month.
4. Calculated monthly cohort indices.
5. Calculated unique active customers and retention percentages.
6. Visualized the results using a heatmap.

## Files

* `cohort_retention_analysis.ipynb` — analysis notebook
* `cohort_customer_counts.csv` — monthly active customer counts
* `cohort_retention_percentages.csv` — retention percentages
* `cohort_retention_heatmap.png` — cohort heatmap

## Business Insights

See the notebook for the calculated retention results and observations based on the dataset.

## Dataset

Online Retail II — UCI Machine Learning Repository:
https://archive.ics.uci.edu/dataset/502/online+retail+ii

## Note

Cohorts are defined by each customer's first recorded purchase month, rather than signup date.
