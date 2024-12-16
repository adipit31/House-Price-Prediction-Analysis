# House Price Analysis

This repository contains a data analysis project that investigates how various factors influence house prices. Using a dataset of house attributes, we aim to uncover trends, correlations, and insights that help understand what drives property value.

---

## Project Overview

The analysis leverages Python to explore relationships between house prices (`SalePrice`) and features such as:  
- Property type (`MSSubClass`, `BldgType`).  
- Location attributes (`MSZoning`, `LotConfig`).  
- Structural attributes (`YearBuilt`, `YearRemodAdd`, `Exterior1st`).  
- Size and condition metrics (`LotArea`, `OverallCond`, `TotalBsmtSF`, `BsmtFinSF2`).  

Key steps include:  
1. Data cleaning and preprocessing.  
2. Visualizing distributions and correlations.  
3. Examining categorical and numerical impacts on `SalePrice`.  

---

## Repository Structure


Scatter plots to explore trends with time and area.
Distribution plots for SalePrice and numerical features.


---

## Features Explored

- **Numerical Features:**  
  - `LotArea`: Total lot size.  
  - `OverallCond`: Overall condition rating (1–10).  
  - `YearBuilt` and `YearRemodAdd`: Construction and remodeling years.  
  - `BsmtFinSF2` and `TotalBsmtSF`: Basement areas in square feet.  

- **Categorical Features:**  
  - `MSSubClass`: Type of dwelling.  
  - `MSZoning`: Zoning classification (e.g., Residential, Commercial).  
  - `LotConfig`: Lot configuration (e.g., Corner lot, Cul-de-sac).  
  - `BldgType`: Type of building structure.  
  - `Exterior1st`: Primary exterior material.  

---
## Visualizations

This analysis includes a variety of visualizations to explore the dataset:

1. **Correlation Heatmap:**  
   - Highlights relationships between numerical features like `LotArea`, `TotalBsmtSF`, and `SalePrice`.  
   - Strong correlations with `SalePrice` indicate impactful features.

2. **SalePrice Distribution:**  
   - Displays the distribution of house prices, revealing skewness and potential outliers.

3. **Boxplots for Categorical Features:**  
   - Compares `SalePrice` across categories like `MSZoning`, `LotConfig`, and `BldgType`.  
   - Identifies categorical attributes with significant price variations.

4. **Trend Analysis (YearBuilt/YearRemodAdd):**  
   - Visualizes how construction and remodeling years affect `SalePrice`.

5. **Basement Area vs SalePrice:**  
   - Scatter plot showing the impact of basement size (`TotalBsmtSF`) on `SalePrice`.
     
---

## Insights

From the analysis, we derived the following key insights:

1. **Impactful Numerical Features:**  
   - `TotalBsmtSF` shows a strong positive correlation with `SalePrice`, indicating larger basements increase property value.  
   - `YearBuilt` and `YearRemodAdd` show a positive trend, reflecting higher prices for newer or remodeled houses.  

2. **Categorical Trends:**  
   - Houses in high-value zoning categories (`MSZoning`) tend to have higher sale prices.  
   - Property type (`BldgType`) significantly influences `SalePrice`, with single-family detached homes commanding higher prices.  

3. **Outliers in SalePrice Distribution:**  
   - A small number of houses have exceptionally high prices, which may affect regression models.  

4. **Overall Condition:**  
   - Surprisingly, `OverallCond` (overall condition) does not have as strong an impact as other features like `LotArea` and `YearBuilt`.  

5. **Lot Size and Configuration:**  
   - Larger lots (`LotArea`) contribute to higher prices, but the relationship is non-linear, showing diminishing returns for very large lots.  





