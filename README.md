Marketing Campaign A/B Testing Analysis

Overview

This project evaluates the performance of two website landing page variants using A/B testing and statistical analysis. The objective is to determine whether the new landing page leads to a higher conversion rate than the existing version and whether the observed difference is statistically significant.

Business Objective

Before introducing a new website design or marketing campaign to all users, businesses need evidence that the proposed changes improve customer engagement and conversions. This project analyzes user behavior to determine whether the new landing page performs better than the existing version and supports data-driven decision-making.

The analysis focuses on the following questions:

* Does the new landing page achieve a higher conversion rate?
* Is the improvement statistically significant at a 95% confidence level?
* Should the new design be deployed or should additional testing be conducted?

Tools and Technologies

Language: Python 3

Libraries:

* Pandas (Data Cleaning and Analysis)
* NumPy (Numerical Computation)
* SciPy (Statistical Hypothesis Testing)
* Matplotlib (Data Visualization)
* Seaborn (Statistical Data Visualization)

Development Environment:

* Jupyter Notebook

Project Workflow

* Imported and cleaned the A/B testing dataset.
* Performed exploratory data analysis to compare user behavior across the Control and Variant groups.
* Calculated conversion rates and summarized key performance metrics.
* Visualized the distribution of conversions and group performance.
* Conducted a Two-Sample T-Test to evaluate statistical significance.
* Interpreted the results and provided a business recommendation based on the findings.

Key Findings

* Compared conversion rates between the Control and Variant groups to measure the effectiveness of the new landing page.
* Applied statistical hypothesis testing to determine whether the observed difference was statistically significant.
* Based on the test results, provided a data-driven recommendation on whether the new design should be implemented or whether further experimentation was required.

How to Run the Project

1. Clone this repository.
2. Download an A/B testing dataset in CSV format from Kaggle.
3. Ensure the dataset contains a test group column (for example, `group`) and a conversion column (for example, `converted`).
4. Save the dataset as `ab_test_data.csv` in the project directory.
5. Open `ab_testing_analysis.ipynb` using Jupyter Notebook or JupyterLab.
6. Run all notebook cells to reproduce the analysis and results.
