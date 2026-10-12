# SWYNEX – Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Adult Census Income dataset using Python and Pandas. The objective is to understand the dataset, calculate descriptive statistics, identify patterns, visualize distributions, and investigate unusual values.

## Dataset
- **Source:** Adult Census Income dataset
- **Records:** 32,537
- **Columns:** 15
- **Missing values after cleaning:** 0
- **Duplicate rows after cleaning:** 0

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Google Colab

## Analysis Performed
1. Inspected dataset structure and data types.
2. Calculated mean, median, minimum, maximum, and descriptive statistics.
3. Analyzed income and workclass distributions.
4. Visualized income, education, and weekly working-hour distributions.
5. Compared education levels with income categories.
6. Investigated unusual working-hour, age, capital-gain, and capital-loss values.

## Key Findings
- 75.91% of records belong to the income category `<=50K`.
- 69.68% of records belong to the Private workclass.
- 46.73% of individuals work exactly 40 hours per week.
- 29.43% work more than 40 hours per week.
- The average weekly working hours are 38.84 for the `<=50K` group and 45.47 for the `>50K` group.
- In the Doctorate education category, 74.09% of records belong to the `>50K` income group.

These findings describe associations in this dataset and do not establish cause and effect.

## Anomaly Investigation
The analysis identified unusual values, including 85 records reporting 99 working hours per week and 770 records with capital gain above 10,000. These values were flagged for investigation rather than automatically removed because unusual values are not necessarily errors.

## Project Outputs
The `eda_results.zip` file contains exported CSV tables for:
- Income distribution
- Education versus income
- Percentage earning above 50K by education
- Numerical summary
- Anomaly summary

## Conclusion
This project demonstrates basic data analysis skills, including data inspection, descriptive statistics, categorical analysis, visualization, and anomaly investigation using Python.

## Author
Completed as part of the SWYNEX data analytics task.
