# ASEAN Internet Adoption Analysis

## About This Project

Technology and internet access have become increasingly important across countries. This made me curious about how internet usage has developed across ASEAN countries and whether countries show similar patterns of internet adoption.

In this project, I analyze Internet Usage and Population across ASEAN countries from 2010 to 2024. The project uses data from the World Development Indicators (WDI) and is analyzed using Python.

## Dataset

- **Source:** World Development Indicators (WDI)
- **Period:** 2010–2024
- **Coverage:** 11 ASEAN countries
- **Indicators:** Population and Internet Usage (% of population)

## Tools

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Analysis Questions

1. Which country had the highest average Internet Usage from 2010 to 2024?
2. Which country had the largest increase in Internet Usage from 2010 to 2024?
3. Did the country with the largest increase in Internet Usage also have the highest Internet Usage in 2024?
4. In which year did each country experience its largest annual increase in Internet Usage?
5. What was the relationship between Population and Internet Usage across ASEAN countries in 2024?

## Data Preparation

- Inspected the raw dataset to understand its structure and shape.
- Removed metadata and records that were not part of the observations.
- Cleaned the Year column and converted it into a numeric format.
- Transformed the dataset from wide to long format.
- Pivoted the indicators into separate Population and Internet Usage columns.
- Converted Population and Internet Usage into numeric data types and checked for missing values.

## Key Findings

- Malaysia had the highest Internet Usage in ASEAN in 2024 at 98.02%, while Singapore had the highest average Internet Usage from 2010 to 2024 at 84.83%.

- Although Malaysia had the highest Internet Usage in 2024, Thailand experienced the largest increase from 2010 to 2024. This shows that the country with the highest Internet Usage is not necessarily the country with the largest increase.

- Population and Internet Usage showed a weak negative correlation in 2024 (r = -0.325). This suggests that countries with larger populations tended to have lower Internet Usage in this dataset, although the relationship was weak.

## Limitations

- Internet Usage data for Myanmar (2021–2024) and Timor-Leste (2022–2024) were unavailable. Therefore, analyses that required complete data through 2024 used 9 ASEAN countries.
- The analysis only covers the period from 2010 to 2024, so the results may differ when using a different time period.
- The relationship between Population and Internet Usage represents correlation, not causation. Other factors that may affect Internet Usage were not included in this analysis.

## Repository Structure

- `README.md` — Overview and key findings of the project.
- `ASEAN_Internet_Adoption_Analysis.ipynb` — Full data cleaning, analysis, visualization, and interpretation.
- `data/` — Raw dataset used in the analysis.
