<img width="310" height="163" alt="image" src="https://github.com/user-attachments/assets/7f41fa30-bb77-4a37-9777-388bbfbe9ee0" />





**How Wealth Shapes Life Expectancy Around the World**

Life expectancy is one of the simplest ways to measure the quality of life in a country. But does money actually matter? To find out, I analyzed a dataset containing the life expectancy of 158 countries, along with their GDP — a common measure of national wealth.

**What the Data Shows**
When we divide countries into low-GDP and high-GDP groups, the difference becomes immediately clear.
High-GDP countries cluster around 75–82 years, with relatively little variation.
Low-GDP countries range widely, often between 50–70 years, with much more spread and instability.
When plotting the distributions together, the contrast is unmistakable: the two histograms barely overlap. Economic strength appears strongly linked to public health, infrastructure, medical access, and long-term survival.

**A Closer Look**
To test this, I looked at quartiles:
The median life expectancy of high-GDP countries was dramatically higher.
A life expectancy of 70 years is:
Low (1st quartile) for high-GDP countries
High (4th quartile) for low-GDP countries

This tells us something important:
The same number means completely different things depending on the economic context.

**Why It Matters**
These insights remind us that global health is deeply tied to economic stability. As countries develop and GDP grows, life expectancy tends to rise with it. Understanding these patterns helps governments, NGOs, and researchers make targeted health interventions.

**Final Thoughts**
Wealth isn’t everything, but in this dataset, it has a clear connection with how long people live.
Richer countries live longer — and more consistently.

**README / Technical Project Summary (voor GitHub Portfolio)**
**📊 Life Expectancy by Country — Data Analysis Project

**Project Overview****
This project explores the relationship between GDP (a measure of economic wealth) and life expectancy across 158 countries. Using exploratory data analysis (EDA), statistical summaries, quartiles, quantiles, and distributions, we evaluate how strongly economic conditions correlate with national health outcomes.

**Key Steps**
**1. Data Loading & Inspection (EDA)**
Loaded dataset with pandas
Inspected datatypes and missing values
Confirmed numerical features (Life Expectancy, GDP) and categorical (Country)

**2. Summary Statistics**
Calculated quartiles using np.quantile()
Computed overall range and Interquartile Range (IQR)
Used scipy.stats.iqr() for quick IQR extraction

**3. Group Splitting**
Split dataset into:
high_gdp → GDP above median
low_gdp → GDP at or below median

**4. Group-Level Statistics**
Compared quartiles of life expectancy for both groups
Identified major differences in central tendency and spread

**5. Visualizations**
Histograms of life expectancy
Overlapping histograms comparing high vs. low GDP countries
Labeled axes, title, legend for clarity

**Results**
High-GDP countries cluster tightly around 75–82 years
Low-GDP countries have wider spread and lower central tendency

A life expectancy of 70 years is:
1st quartile for high-GDP countries
4th quartile for low-GDP countries

Strong evidence that GDP is positively correlated with life expectancy

**Conclusion**
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
