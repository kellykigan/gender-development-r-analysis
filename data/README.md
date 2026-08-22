# Data

## Dataset

This project uses a country-level Gender Development Index dataset covering 1990 to 2021.

The dataset contains country identifiers, geographic classifications, human development group classifications, 2021 HDI rank, and annual Gender Development Index values.

## Source

Original data source:

[KAGGLE Datasets - https://www.kaggle.com/datasets/iamsouravbanerjee/gender-development-index-dataset]

## Unit of Analysis

The unit of analysis is the country.

## Data Coverage

The dataset contains:

- 195 country-level observations
- 39 variables
- GDI observations covering 1990 to 2021

## Data Availability

The raw dataset is included in this repository because redistribution is permitted by the original data provider.

The dataset is provided for research, educational, and reproducibility purposes in accordance with the terms specified by the original data provider.

## Reproducibility

The dataset is included in the `data/` directory so that users can reproduce the analysis using the R script provided in the `R/` directory.

## Data Quality Considerations

The dataset contains missing GDI observations, particularly for earlier years.

There are also differences in the number of countries represented across years.

These issues are considered when interpreting longitudinal results.
