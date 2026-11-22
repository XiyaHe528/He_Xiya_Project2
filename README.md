# Air Pollution in Durham County (2018–2020)

BIOSTAT 721 Project 2  
Author: Xiya He  
Date: November 22, 2026

## Project Overview

This project uses EPA air quality data from RDU airport for 2018, 2019, and January to April 2020.

The analysis focuses on three pollutants: CO, PM2.5, and O3. It includes data cleaning, summary tables, and monthly plots.

## Project Files

- He_Xiya_Project2.Rproj: RStudio project file
- He_Xiya_Project2.Rmd: R code and report
- He_Xiya_Project2.docx: Final Word report
- data/AQ_2018.csv: Raw data for 2018
- data/AQ_2019.csv: Raw data for 2019
- data/AQ_2020.csv: Raw data for 2020

## How to Run

1. Open He_Xiya_Project2.Rproj in RStudio.
2. Make sure the rmarkdown, knitr, dplyr, tidyr, and ggplot2 packages are installed.
3. Open He_Xiya_Project2.Rmd.
4. Click Knit to generate the Word report.

## Analysis

The R code removes duplicate rows, handles negative values, and calculates daily averages.

The report includes three summary tables and two plots showing monthly air pollution patterns.