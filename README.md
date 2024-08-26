# A/B Test Results Analysis for E-commerce Website

## Overview
This project focuses on analyzing the results of an A/B test conducted by an e-commerce website. The goal is to determine whether the website should adopt a new page, retain the old page, or extend the testing period to gather more data. This Jupyter notebook uses a question-and-answer format to guide through the probability calculations, hypothesis testing, and logistic regression analysis needed to make an informed decision.

## Repository Contents
- **Jupyter Notebook:** Contains the analysis and code for examining the A/B test results.
- **Data File:** `ab-data.csv` - Contains user IDs, timestamps, group assignments (control or treatment), landing page type (old or new), and conversion status.

## Steps in the Analysis
1. **Probability Analysis:** Calculate probabilities to understand the baseline conversion rates.
2. **Hypothesis Testing:** Formulate and test hypotheses about the effectiveness of the new page versus the old page.
3. **Regression Analysis:** Apply logistic regression to model the conversion rates based on the page type and other variables.

## Libraries Used
- `pandas` and `numpy` for data manipulation.
- `matplotlib.pyplot` for visualizing the data.
- `statsmodels` for performing regression analyses.

## How to Run the Notebook
To run this notebook:
1. Ensure that Python and Jupyter Notebook are installed on your system.
2. Download the `ab-data.csv` file and place it in the same directory as the notebook.
3. Open the Jupyter Notebook and execute the cells sequentially to reproduce the analysis.

## Results
The analysis should provide insights into whether the new page leads to higher conversion rates compared to the old page and if the observed differences are statistically significant.
