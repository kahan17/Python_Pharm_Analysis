# Pymaceuticals, Inc. - Anti-Cancer Medications Study

## Overview

Pymaceuticals, Inc. specializes in anti-cancer medications and has recently conducted an animal study to screen for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. This study involved 249 mice who were identified with SCC tumors and received treatment with a range of drug regimens. Tumor development was observed and measured over the course of 45 days to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against other treatment regimens.

## Objective

The objective of this study was to compare the effectiveness of Capomulin with other treatment regimens in reducing tumor volume over time.

## Data Analysis

### 1. Data Merging and Cleaning

- The study results and mouse metadata were merged into a single DataFrame.
- Duplicate entries based on Mouse ID and Timepoint were identified and removed to create a clean DataFrame.

### 2. Summary Statistics

A summary statistics table of the tumor volume for each treatment regimen was generated, including the mean, median, variance, standard deviation, and SEM:

| Drug Regimen | Mean Tumor Volume | Median Tumor Volume | Variance Tumor Volume | Standard Deviation Tumor Volume | SEM Tumor Volume |
|--------------|-------------------|---------------------|-----------------------|-------------------------------|------------------|
| Capomulin    | 40.68             | 41.56               | 24.95                 | 4.99                           | 0.33             |
| Ramicane     | 40.22             | 40.67               | 23.49                 | 4.85                           | 0.32             |
| Infubinol    | 52.88             | 51.82               | 43.13                 | 6.57                           | 0.49             |
| Ceftamin     | 52.59             | 51.78               | 39.29                 | 6.27                           | 0.47             |

### 3. Statistical Analysis

#### Correlation and Regression Analysis

- **Correlation Coefficient**: 0.84
- **Linear Regression Model**: Tumor Volume = 0.95 * Weight + 21.55
- **R-squared**: 0.70

The correlation coefficient of 0.84 indicates a strong positive correlation between mouse weight and average observed tumor volume for the Capomulin regimen. The linear regression model suggests that as mouse weight increases, the tumor volume also tends to increase.

## Conclusion

The data analysis and visualizations provide a comprehensive overview of the study results. Capomulin and Ramicane were effective in reducing tumor volume compared to Infubinol and Ceftamin. The positive correlation between mouse weight and tumor volume for the Capomulin regimen suggests that further studies could investigate the impact of mouse weight on treatment efficacy.

