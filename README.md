# Exercise 2: Human Development Index Analysis

**Github Pages Link:** https://fundamentalsamogh.github.io/week5_hw2/

## Overview

This project analyzes the Human Development Index (HDI) data from the UNDP Human Development Report 2025. The analysis reads the HDI Table 1 Excel file from GitHub, cleans the data to keep only countries without missing values, computes summary statistics, and creates visualizations.

## Data Source

- **Source:** [UNDP Human Development Report 2025](https://hdr.undp.org/data-center/documentation-and-downloads)
- **File:** Table 1: Human Development Index and its components
- **Countries:** 193 (after removing entries with missing values)

## Columns Kept

| Column | Description |
|--------|-------------|
| HDI_Rank | Country ranking by HDI value |
| Country | Country name |
| HDI_Value | Human Development Index (0-1 scale) |
| Life_Expectancy | Life expectancy at birth (years) |
| Expected_Years_Schooling | Expected years of schooling for children |
| Mean_Years_Schooling | Mean years of schooling for adults |
| GNI_Per_Capita | Gross National Income per capita (2021 PPP $) |

## Mean Values Computed

| Variable | Mean | Unit |
|----------|------|------|
| Life Expectancy at birth | 73.11 | years |
| Expected Years of Schooling | 13.58 | years |
| Mean Years of Schooling | 9.17 | years |
| GNI per Capita | 24,620.68 | 2021 PPP $ |

## Visualizations

1. **Histogram:** Distribution of HDI values with global mean line
2. **Scatter Plot:** Life Expectancy vs GNI per Capita
3. **Scatter Plot:** Expected vs Mean Years of Schooling

## Files

- `index.Rmd` - R Markdown source file
- `index.html` - Rendered HTML report
- `HDR25_Statistical_Annex_HDI_Table.xlsx` - Raw HDI data file

## Author

Amogh Guthur
