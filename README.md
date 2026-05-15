# Product Revenue A/B Testing Analysis

Python statistical analysis project for comparing revenue performance between control and test groups.

## Project Overview

This project evaluates whether a test variation produces a statistically significant revenue improvement compared to a control group.

## Tools Used

- Python
- pandas
- numpy
- matplotlib
- scipy

## Analysis Performed

- Descriptive statistics
- Revenue distribution analysis
- Boxplot comparison
- Shapiro-Wilk normality test
- Independent t-test
- Mann-Whitney U test
- 95% confidence interval estimation

## Key Findings

- Both groups followed approximately normal distributions
- Independent t-test found no statistically significant difference
- Mann-Whitney test confirmed the same conclusion
- Confidence interval included zero

## Business Conclusion

The experimental variation did not generate a statistically significant improvement in revenue.

## Files

- `ab_testing_analysis.ipynb`
- `product_revenue.csv`
