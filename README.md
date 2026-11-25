# Ontario Swimming Pool Facilities Analysis

## Project Overview

This project investigates the relationship between population, household income and swimming pool facility availability across Ontario municipalities using Statistics Canada open data and Microsoft Power BI.

The objective is to explore how demographic and socioeconomic factors relate to the distribution of recreational infrastructure through statistical analysis and interactive data visualization.

## Dashboard

<img width="190" height="217" alt="image" src="https://github.com/user-attachments/assets/ac2233b4-3269-4faf-a75f-bc0d4ec87b58" />


## Research Objectives

- Examine the relationship between municipal population and recorded swimming pool counts.
- Investigate whether household income is associated with pool availability per capita.
- Identify municipalities and providers with the highest recorded pool counts.
- Explore demographic differences in recreational facility distribution.
- Develop an interactive business intelligence dashboard to communicate statistical findings.

## Tools and Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- M Query Language
- Relational Data Modelling
- Statistical Analysis
- Data Visualization

## Data Sources

- Statistics Canada — Open Database of Recreational and Sport Facilities (ODRSF)
- Statistics Canada — 2021 Census of Population

## Methodology

### 1. Data Preparation and Transformation

- Extracted, cleaned and transformed raw Statistics Canada datasets.
- Filtered recreational facilities by province and facility type.
- Selected relevant demographic and socioeconomic variables.
- Transformed Census data into a structured analytical format.
- Integrated demographic and recreational facility data using census subdivision identifiers.

### 2. Data Modelling

- Established a one-to-many relationship between the demographic and recreational facility datasets.
- Developed custom DAX measures for statistical calculations and key performance indicators.
- Aggregated facility counts by municipality and provider.
- Normalized facility counts relative to municipal population.

### 3. Statistical Analysis

The following statistical methods were applied:

- **Descriptive Statistics:** Summarized recorded facility counts and municipality coverage.
- **Per-Capita Normalization:** Calculated swimming pool facilities per 100,000 residents to facilitate comparisons between municipalities of different population sizes.
- **Pearson Correlation Coefficient (r):** Measured the strength and direction of linear relationships between selected variables.
- **Simple Linear Regression Assessment:** Used linear trend lines to examine relationships between demographic variables and facility availability.
- **Coefficient of Determination (R²):** Assessed the proportion of observed variation explained by each individual linear relationship.

## Key Findings

| Metric | Result |
|---|---:|
| Recorded Pool Facilities | 615 |
| Municipalities Represented | 30 |
| Population Correlation (r) | 0.90 |
| Population R² | 0.80 |
| Income Correlation (r) | -0.04 |
| Income R² | 0.00 |

### Population and Swimming Pool Facilities

Population demonstrates a strong positive linear association with recorded swimming pool counts, with a Pearson correlation coefficient of approximately 0.90.

The coefficient of determination (R²) indicates that approximately 80% of the observed variation in recorded pool counts is explained by the fitted population relationship within the analyzed sample.

### Household Income and Swimming Pool Availability

Median household income demonstrates a negligible negative linear association with recorded swimming pool facilities per 100,000 residents, with a Pearson correlation coefficient of approximately -0.04.

The coefficient of determination is approximately zero when rounded to two decimal places, suggesting that household income alone explains virtually none of the observed variation in recorded pool availability per capita.

## Dashboard Features

- Six statistical KPI cards
- Interactive municipality filter
- Top 10 municipalities by recorded pool count
- Top 10 swimming pool providers
- Population versus recorded pool count scatter plot
- Household income versus pools per 100,000 residents scatter plot
- Linear regression trend lines
- Municipal demographic and facility statistics table
- Interactive visual filtering

## Limitations

- The analysis is limited to municipalities represented in the recreational facilities dataset.
- Recorded pool facilities may include wading pools and do not necessarily represent comprehensive public swimming pool access.
- Facility counts do not account for operating hours, capacity, admission costs, accessibility or facility conditions.
- Correlation does not imply causation.
- Multiple linear regression and formal statistical significance testing were not performed.
- The statistical results are exploratory and have not been independently validated.

## Future Improvements

- Multiple linear regression
- Hypothesis testing and p-value calculations
- Confidence intervals
- Residual and outlier analysis
- Geospatial accessibility analysis
- Integration of municipal recreation budgets and operating costs
- Analysis of recreational infrastructure demand and resource allocation

## Skills Demonstrated

- Business Intelligence
- Data Analytics
- Statistical Analysis
- Exploratory Data Analysis (EDA)
- Data Cleaning and Transformation
- Extract, Transform and Load (ETL)
- Data Integration
- Relational Data Modelling
- DAX Programming
- Demographic Analysis
- KPI Development
- Interactive Dashboard Development
- Analytical Problem-Solving
- Data Storytelling

## Personal Project & Disclaimer

This project was developed in my spare time as part of my ongoing professional development and personal interest in data analytics, business intelligence and statistical analysis.

The project is intended for educational and portfolio purposes, allowing me to apply analytical techniques to real-world, publicly available datasets while strengthening my technical, statistical and problem-solving skills.

This project is not affiliated with, commissioned by, or endorsed by Statistics Canada or any municipality. The findings are exploratory and should not be interpreted as official statistics, validated predictions or policy recommendations.

## Author

**Philip Tomic**

Personal Data Analytics & Business Intelligence Portfolio

November 2026
