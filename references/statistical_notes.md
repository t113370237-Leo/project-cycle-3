# Project Cycle 3: Statistical Methodology & Reference Notes

**Dataset:** `q3_cleaned_data.csv` (Derived from YRBS 2007)
**Research Question:** Question 3 (Gender and Sad or Hopeless Feeling)
**Analysis Type:** Two-Sample Proportion Inference

## 1. Statistical Framework
* **Methodology:** Two-Proportion Z-Test (Two-sided)
* **Null Hypothesis ($H_0$):** $p_{female} - p_{male} = 0$ (The proportion of feeling sad or hopeless is equal between female and male students)
* **Alternative Hypothesis ($H_A$):** $p_{female} - p_{male} 
eq 0$ (The proportion of feeling sad or hopeless is significantly different between female and male students)
* **Significance Level ($lpha$):** 0.05

## 2. Implementation Details
* **Programming Language:** Python 3
* **Core Libraries Used:**
  * `statsmodels.stats.proportion.proportions_ztest` for calculating the Z-statistic and P-value.
  * `statsmodels.stats.proportion.confint_proportions_2indep` (Wald method) for computing the 95% Confidence Interval of the difference.
  * `matplotlib.pyplot` for data visualization.

## 3. Interpretation Guidelines
* **Decision Rule:** If P-value < $lpha$ (0.05), reject $H_0$. Otherwise, fail to reject $H_0$.
* **Confidence Interval:** If the 95% Confidence Interval for the difference ($p_{female} - p_{male}$) does not contain 0, it visually and statistically confirms that the difference is significant.
* **Methodological Limitation:** This analysis is based on observational survey data. A statistically significant result indicates a strong association but cannot imply causality.
