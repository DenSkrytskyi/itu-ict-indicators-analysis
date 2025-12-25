# ITU ICT Indicators Analysis

Exploratory analysis of ICT access, usage and affordability using ITU data

## 1. Project Overview

This project presents an exploratory and comparative analysis of selected Information and Communication Technology (ICT) indicators published by the International Telecommunication Union (ITU).

The analysis focuses on ICT access, usage and affordability, three core dimensions monitored by the ITU Telecommunication Development Bureau (BDT) to assess digital inclusion and digital transformation across countries and regions.

The objective of this project is to demonstrate:

data handling and validation of official ICT statistics;

exploratory and comparative analysis across countries and time;

policy-relevant interpretation of ICT indicators in line with ITU analytical work.

## 2. Data Sources

All datasets used in this project were downloaded from the ITU ICT DataHub and correspond to officially published ITU indicators.

The analysis uses country-level time series data covering multiple years, depending on indicator availability.

## 3. Indicators Used

The following ICT indicators are included in the analysis:

Households with Internet access at home (%)

Individuals using the Internet (%)

Individuals who own a mobile cellular telephone (%)

Individuals who own a smartphone (%)

Active mobile-broadband subscriptions (count)

Fixed-broadband subscriptions (per 100 people)

Population coverage by mobile network (at least 2G/3G/4G/5G)

Data-only mobile broadband basket (5 GB) – % of GNI per capita

Fixed-broadband Internet basket (5 GB) – % of GNI per capita

Household expenditure on ICTs (% of total household expenditure)

These indicators reflect ITU’s core analytical areas: connectivity, usage, affordability and digital inclusion.

## 4. Methodology and Analytical Steps

The analysis follows standard ITU-style analytical steps:

Data loading and validation

-Importing CSV files using Python (pandas).

-Checking structure, missing values and data types.

-Ensuring consistency of country names and time variables.

Exploratory analysis

-Descriptive statistics for each indicator.

-Time-series visualisation to identify long-term trends.

-Cross-country comparisons to highlight variation across development contexts.

Comparative analysis

-Comparison between households’ Internet access and individuals’ Internet use.

-Analysis of the relationship between Internet affordability and Internet adoption.

-Identification of top and bottom countries based on latest available data.

Visualisation

-Line charts for trends over time.

-Scatter plots to analyse relationships between indicators.

-Bar charts for country rankings.

## 5. Key Findings (Policy-Oriented Summary)

Strong global upward trend
Most countries show a clear increase in Internet access and usage over time, reflecting sustained global progress in ICT adoption.

Persistent digital divide
Despite overall growth, large disparities remain between countries, especially between high-income and low-income contexts.

Affordability matters
Countries where mobile broadband prices represent a higher share of GNI per capita tend to have lower household Internet access rates, highlighting affordability as a key barrier to digital inclusion.

Households vs individuals
In many countries, the percentage of individuals using the Internet exceeds the percentage of households with Internet access, indicating reliance on shared access, mobile connectivity or public access points.

These findings are consistent with ITU’s global assessments of ICT development and affordability.

## 6. Relevance to ITU ICT Statistics Work

This project directly aligns with the work of the ICT Data and Analytics Division (IDA) by demonstrating:

- handling and validation of official ICT statistics;

- analytical use of ICT access, usage and price indicators;

-production of clear, policy-relevant visual outputs;

- concise interpretation of statistical results for decision-making contexts.

## 7. Tools and Environment

Python

Jupyter Notebook

Libraries:

pandas

matplotlib

seaborn

## 8. Reproducibility

The analysis is fully reproducible:

all source data are stored in the data/raw folder;

all analytical steps are documented in the Jupyter notebook;

no manual data manipulation was performed outside the code.
