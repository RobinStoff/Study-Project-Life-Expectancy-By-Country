📊 Life Expectancy by Country — Data Analysis Project
Project Overview

This project explores the relationship between GDP (a measure of economic wealth) and life expectancy across 158 countries. Using exploratory data analysis (EDA), statistical summaries, quartiles, quantiles, and distributions, we evaluate how strongly economic conditions correlate with national health outcomes.

Key Steps
1. Data Loading & Inspection (EDA)

Loaded dataset with pandas

Inspected datatypes and missing values

Confirmed numerical features (Life Expectancy, GDP) and categorical (Country)

2. Summary Statistics

Calculated quartiles using np.quantile()

Computed overall range and Interquartile Range (IQR)

Used scipy.stats.iqr() for quick IQR extraction

3. Group Splitting

Split dataset into:

high_gdp → GDP above median

low_gdp → GDP at or below median

4. Group-Level Statistics

Compared quartiles of life expectancy for both groups

Identified major differences in central tendency and spread

5. Visualizations

Histograms of life expectancy

Overlapping histograms comparing high vs. low GDP countries

Labeled axes, title, legend for clarity

Results

High-GDP countries cluster tightly around 75–82 years

Low-GDP countries have wider spread and lower central tendency

A life expectancy of 70 years is:

1st quartile for high-GDP countries

4th quartile for low-GDP countries

Strong evidence that GDP is positively correlated with life expectancy

Conclusion

Economic conditions appear to strongly influence life expectancy. Countries with higher GDP not only live longer on average but also show far less variability, suggesting more stable healthcare systems and social conditions.

Technologies Used

Python

Pandas

NumPy

SciPy

Matplotlib

Files

life_expectancy.ipynb — Main notebook

README.md — Project summary

life_expectancy.csv — Dataset
