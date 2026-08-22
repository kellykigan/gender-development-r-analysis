# Gender Development Across Countries: A Quantitative Analysis Using R

## Project Overview

This project applies quantitative research methods and R programming to examine patterns in the Gender Development Index (GDI) across countries and over time.

The analysis uses country-level GDI data covering 1990 to 2021 and examines differences across human development groups and geographic regions, the association between GDI and HDI rank, and changes in GDI over time.

The project was developed as a practical demonstration of quantitative data analysis in development research.

## Research Question

**How does gender development vary across countries and over time, and how is it associated with broader human development?**

## Supporting Questions

1. How does the Gender Development Index vary across countries in 2021?
2. How does GDI differ across human development groups and geographic regions?
3. How is GDI associated with HDI rank?
4. How has GDI changed between 1990 and 2021 among countries with comparable observations?

## Dataset

The dataset contains country-level observations for:

- Country and ISO3 identifiers
- Continent
- Hemisphere
- Human Development Group
- UNDP developing region classification
- HDI rank for 2021
- Gender Development Index values from 1990 to 2021

### Unit of Analysis

The primary unit of analysis is the country.

The dataset contains 195 country-level observations and 39 variables.

## Methodology

The analysis follows a quantitative research workflow covering:

1. Data import and inspection
2. Data quality assessment
3. Missing-data assessment
4. Data cleaning and preparation
5. Descriptive statistics
6. Data visualization
7. Group comparisons
8. Correlation analysis
9. Linear regression
10. Longitudinal analysis
11. Regression diagnostics
12. Interpretation and limitations

## Development Research Relevance

The analysis explores cross-country patterns in gender-related human development and examines how these patterns relate to broader levels of human development.

The project demonstrates how R can be used to support quantitative development research, from data preparation and descriptive analysis to statistical modelling and interpretation.

## Key Findings

Key findings from the analysis include:

- Substantial cross-country variation in GDI.
- Higher human development groups generally record higher GDI values.
- GDI varies substantially across geographic regions.
- GDI is associated with HDI rank.
- GDI generally increased over the period covered by the dataset.

## Important Limitation

The analysis is based on observational country-level data.

The findings therefore demonstrate patterns and statistical associations rather than causal effects.

## Tools

- R
- RStudio
- tidyverse
- ggplot2
- Descriptive statistics
- Statistical testing
- Correlation analysis
- Linear regression
- Data visualization

## Repository Structure

```text
R/
    Main R analysis script

data/
    Dataset information and source documentation

outputs/
    Figures and analytical tables

docs/
    Methodology and detailed findings
