# Week 1-2: Data Cleaning & Exploratory Data Analysis

Internship project — AnalystLab Africa Data Analytics Internship Program

## Overview

This project covers the data cleaning and exploratory data analysis (EDA) process applied to two real-world datasets, as required for Weeks 1-2 of the AnalystLab Africa Data Analytics Internship.

## Datasets

1. **Online Retail** — E-commerce transactions from a UK-based online retailer (Dec 2010 - Dec 2011)
   Source: [Kaggle - Online Retail Dataset](https://www.kaggle.com/datasets/vijayuv/onlineretail)

2. **Netflix Movies & TV Shows** — Netflix content catalog metadata
   Source: [Kaggle - Netflix Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## Repository Structure

```
├── OnlineRetail/
│   ├── Week1-2_OnlineRetail.ipynb     # Full analysis notebook (cleaning, EDA, visualizations, insights)
│   └── OnlineRetail_cleaned.csv       # Cleaned dataset
├── Netflix/
│   ├── Week1-2_Netflix.ipynb          # Full analysis notebook (cleaning, EDA, visualizations, insights)
│   └── netflix_cleaned.csv            # Cleaned dataset
├── Summary_report.pdf                 # One-page summary report (cleaning challenges, EDA findings, top insights)
└── README.md
```

## Process

Each notebook follows the same structure:
1. **Dataset Understanding** — shape, data types, numerical vs categorical variables, primary key identification
2. **Data Cleaning** — missing values, duplicates, standardization, data validation, cleaning summary
3. **Exploratory Data Analysis** — summary statistics and pattern exploration
4. **Data Visualization** — at least 5 charts per dataset with findings
5. **Key Insights** — 3-5 insights per dataset

## Key Findings (Summary)

**Online Retail**
- The United Kingdom generates 84.6% of total revenue.
- Monthly revenue peaks in November 2011, consistent with holiday shopping demand.
- Most order lines involve small quantities (under 15 units).

**Netflix**
- Movies account for 69.7% of the catalog vs. 30.3% for TV Shows.
- Catalog growth peaked in 2019, then declined in 2020-2021.
- The United States is the leading content-producing country; TV-MA/TV-14 are the most common ratings.

Full details are available in `Summary_report.pdf` and in each notebook.

## Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook (Anaconda)

---
*Part of the AnalystLab Africa Data Analytics Internship Program.*
