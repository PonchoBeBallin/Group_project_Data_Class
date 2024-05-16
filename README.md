# Mortgage Interest Rates: Exploratory Data Analysis (EDA)

Group Members:
- Jose Vela
- Ryan Eikanger
- Mark Olson
- Krishna Pandari

## Description
Think of all the people out there paying more interest on their mortgages than they need to. They might not even realize it! And what about those who could save money by refinancing? Their stories are waiting to be told.

The Mortgage Insights EDA project aims to explore mortgage data from various public sources, including the Consumer Financial Protection Bureau (CFPB), Freddie Mac, and Fannie Mae. By analyzing this rich dataset, we seek to answer critical questions related to mortgage rates, customer demographics, and refinancing opportunities. Our goal is to empower homeowners, lenders, and policymakers with actionable insights and save money.

## Project Objective
The objective of this EDA project is to analyze mortgage data from various sources (such as Consumer Financial Protection Bureau (CFPB) HMDA Data, Freddie Mac, Fannie Mae, etc.) to gain insights into mortgage rates by different customer classes, loan types, and demographics. 

By addressing these questions, we aim to enhance financial literacy, promote informed decision-making, and contribute to a more equitable mortgage market.

### Project Goals, Scope, and Questions to Solve
#### Interest Rate Disparities
**Question:** Are specific customer segments paying significantly higher interest rates than the current market average?

**Goal:** Identify disparities and understand the factors contributing to these variations.
Explore whether certain customer segments (e.g., first-time homebuyers, refinancers, specific income groups) are paying significantly higher interest rates than the current market average.
Investigate variations in interest rates by loan type (fixed-rate vs. adjustable-rate) and loan purpose (purchase vs. refinance).

#### Demographic Patterns
**Question:** How do demographics impact mortgage rates?

**Goal:** Explore interest rate differences based on age, gender, ethnicity, and income level.
Identify any disparities in interest rates across different states or regions.

#### Refinancing Opportunities(Optional)
**Question:** Who could benefit from mortgage refinancing to save money on interest payments?

**Goal:** Highlight potential candidates/classes for refinancing (and quantify potential savings).
Individuals paying higher interest rates than the prevailing market rates.
Those who could benefit from refinancing to save money on interest payments.

## Outcomes
- Clear visualizations illustrating interest rate distributions.
- Insights into demographic patterns affecting mortgage rates.
- Re-financing opportunities (Optional)

## Data Sets
- Consumer Financial Protection Bureau (CFPB) - Mortgage Data HMDA (Home Mortgage Disclosure Act) 
    - [https://www.consumerfinance.gov/data-research/hmda/](https://www.consumerfinance.gov/data-research/hmda/)

### HMDA API
```
https://ffiec.cfpb.gov/v2/data-browser-api/view/csv
```

## Repository Contents
- hmda_data - storage folder for raw HMDA data collected by Jupyter notebook
- HMDA Exploratory Data Analysis.ipynb - Main analysis Jupyter notebook file, open with [Jupyter Notebook](https://jupyter.org/)
- hmda_lib.py - supporting Python module used by Jupyter notebook
