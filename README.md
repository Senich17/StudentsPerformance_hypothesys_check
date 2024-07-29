# Analysis of Educational Impact on Math Scores

## Overview

This repository contains a series of analyses to investigate the impact of parental education level on students' math scores. The analysis includes statistical tests and correlation studies to determine whether there's a significant difference in math scores based on whether students' parents attained higher education or not.

## Contents

data_parents_higher: Dataset containing math scores of students whose parents attained higher education.

data_parents_nothigher: Dataset containing math scores of students whose parents did not attain higher education.

analysis.py: Python script performing the statistical analysis, including:
  Calculation of Pearson correlation coefficients.
  Permutation testing to evaluate the significance of observed differences.
  Comparison of mean math scores between groups.

## Key Analyses

1. Pearson Correlation Coefficient:
Calculated the Pearson correlation coefficient between math scores and writing scores to determine the strength of their linear relationship.

2. Permutation Test:
Conducted a permutation test to assess whether the observed difference in mean math scores between students with higher-educated parents and those without is statistically significant.

3. Difference in Means:
Computed the difference in mean math scores between the two groups and tested the significance of this difference using permutation testing.

## Results

Pearson Correlation Coefficient: A strong positive correlation of approximately 0.80 was observed between math scores and writing scores.

p-Value: A p-value of 0.0 indicates a highly significant correlation, suggesting that the observed correlation is unlikely to have occurred by random chance.

Difference in Means: The analysis revealed a notable difference in mean math scores between the two groups, with statistical significance confirmed through permutation testing.

## Usage

To reproduce the analysis or apply it to your own datasets, follow these steps:

Clone the repository:
```git clone https://github.com/yourusername/educational-impact-analysis.git```

Navigate to the project directory:
```cd educational-impact-analysis```

Data source: [https://www.kaggle.com/datasets/spscientist/students-performance-in-exams]
