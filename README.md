# Early-Onset CRC Trends and Social Vulnerability Analysis

This project analyzes trends in colorectal cancer (CRC) cases diagnosed before age 50 from 2010 to 2022, with additional stratification by sex, race, Hispanic origin, and social vulnerability.

The analysis was conducted using R and Quarto/R Markdown. The workflow includes cohort definition, variable recoding, descriptive summary tables, temporal trend visualization, and statistical comparison of Social Vulnerability Index (SVI) scores.

## Project Overview

The main goals of this project are to:

- Define a colorectal cancer cohort based on cancer site recode variables
- Classify patients into age groups and identify cases diagnosed before age 50
- Visualize yearly trends in the proportion of CRC cases among patients aged under 50
- Compare trends by sex and race
- Evaluate the distribution of Social Vulnerability Index scores among under-50 CRC cases
- Assess differences in social vulnerability by age group and Hispanic origin

## Methods

The analysis includes:

- Data cleaning using `janitor`
- Cohort filtering using colorectal cancer site categories
- Age group recoding and creation of an under-50 indicator
- Descriptive summary tables using `gtsummary`
- Trend analysis from 2010 to 2022
- Data visualization using `ggplot2`
- Statistical testing using Welch two-sample t-tests and Wilcoxon rank-sum tests

## Key Outputs

This project generates:

- Descriptive Table 1 for the full CRC cohort
- Descriptive Table 2 for CRC cases aged under 50
- Line plots of under-50 CRC trends over time
- Stratified trend plots by sex and race
- Age-group composition plots among under-50 CRC cases
- Boxplots of Social Vulnerability Index distribution by diagnosis year
- Trend plot of Hispanic proportion among under-50 CRC cases

## Repository Structure

```text
.
├── early_onset_crc_svi_analysis.qmd
├── README.md
└── .gitignore
