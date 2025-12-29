# ITU ICT Indicators Analysis

Exploratory analysis of ICT access, usage, and affordability using ITU official data.

---

## 1. Project Overview

This project presents an exploratory and comparative analysis of selected Information and Communication Technology (ICT) indicators published by the International Telecommunication Union (ITU).  

The analysis focuses on three core indicators:

- **Households with Internet access at home (%)**  
- **Individuals using the Internet (%)**  
- **Data-only mobile broadband basket (5 GB) as % of GNI per capita**  

The objective is to demonstrate:

- Handling and validation of official ICT statistics  
- Exploratory and comparative analysis across countries and over time  
- Policy-relevant interpretation of ICT indicators  

All visualizations are available **directly in the Jupyter notebook** and are also saved in the `outputs/figures` folder.

---

## 2. Data Sources

All datasets used in this project were downloaded from the ITU ICT DataHub and correspond to officially published ITU indicators.  

The analysis uses country-level time series data covering multiple years, depending on indicator availability.

---

## 3. Methodology and Analytical Steps

1. **Data Loading and Validation**  
   - Import CSV files using Python (`pandas`)  
   - Check structure, missing values, and data types  
   - Ensure consistency of country names and time variables  

2. **Exploratory Analysis**  
   - Descriptive statistics for each selected indicator  
   - Time-series visualization to identify long-term trends  
   - Cross-country comparisons to highlight variation  

3. **Comparative Analysis**  
   - Comparison between households’ Internet access and individuals’ Internet use  
   - Analysis of the relationship between Internet affordability and household Internet adoption  
   - Identification of top and bottom countries based on the latest available data  

4. **Visualization**  
   - Line charts for trends over time  
   - Scatter plots for relationships between indicators  
   - Bar charts for country rankings  

---

## 4. Key Findings

- **Strong global upward trend:** Internet access and usage show a clear increase in many countries over time.  
- **Persistent digital divide:** Despite growth, disparities remain between countries, particularly between high-income and low-income contexts.  
- **Affordability matters:** Countries where mobile broadband prices are a higher share of GNI per capita tend to have lower household Internet access rates.  
- **Households vs Individuals:** In many countries, the percentage of individuals using the Internet exceeds the percentage of households with Internet access, indicating reliance on shared or mobile connectivity.  

> Note: These findings are based on the three analyzed indicators: household Internet access, individual Internet use, and mobile broadband affordability.

---

## 5. Tools and Environment

- **Python**  
- **Jupyter Notebook**  
- Libraries: `pandas`, `matplotlib`, `seaborn`  

---

## 6. Visualizations

All charts are saved in the `outputs/figures` folder:

- `households_internet_access_timeseries.png` - Top 10 countries by household Internet access  
- `households_vs_individuals.png` - Scatter plot comparing household vs individual Internet use  
- `households_internet_access_ukraine.png` - Time-series for Ukraine  
- `internet_affordability_vs_access.png` - Affordability vs household Internet access  
- `top_10_internet_usage.png` - Top 10 countries by Internet usage  
- `bottom_10_internet_usage.png` - Bottom 10 countries by Internet usage
