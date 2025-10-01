# Meteorological Data Analysis Project

This repository contains a comprehensive analysis of meteorological data using R, structured across three main Jupyter notebooks. The project covers data exploration, statistical analyses, and clustering techniques to extract insights from weather station data.

## Data

- The main dataset is located in the data folder:  
  `donnees-synop-essentielles-omm.csv`  
  This file contains essential meteorological observations from various stations.

---

## Notebooks Overview

### I. 0-Data_Presentation.ipynb — Data Exploration & Presentation

This notebook provides an introductory exploration of the meteorological dataset:
- **Data Loading:** Reads the raw CSV data and presents its structure.
- **Numerical Summaries:** Displays basic statistics (mean, min, max, etc.) for each variable.
- **Graphical Summaries:** Visualizes distributions and relationships between key variables using plots and charts.
- **Variable Overview:** Explains the meaning and relevance of the main features in the dataset.

This notebook is ideal for understanding the dataset's content and preparing for further analysis.

---

### II. 1-Analyses.ipynb — Statistical Analyses

This notebook performs advanced statistical analyses on the cleaned dataset:
- **Data Cleaning:** Selects only numerical columns, removes constant columns, and imputes missing values.
- **Correlation Analysis:** Computes and visualizes correlation matrices to identify relationships between variables.
- **Feature Reduction:** Filters and selects relevant features for further study.
- **Principal Component Analysis (PCA):** Reduces dimensionality and interprets the main axes of variation.
- **Regression (LASSO & PLS):** Identifies which features most influence target variables (e.g., humidity) using LASSO and Partial Least Squares regression.
- **ANOVA:** Compares temperature and wind speed across different cities.
- **Precipitation Estimator:** Estimates the probability of rain by month and season, and analyzes trends over years.

This notebook is the core of the statistical analysis, providing insights into the structure and drivers of meteorological phenomena.

---

### III. 2-Cluster.ipynb — Clustering & Pattern Discovery

This notebook focuses on unsupervised learning and pattern recognition:
- **Data Preparation:** Loads and summarizes the dataset, focusing on relevant features.
- **Clustering Techniques:** Applies clustering algorithms (such as k-means, hierarchical clustering) to group weather stations or observations based on their characteristics.
- **Cluster Interpretation:** Visualizes clusters and interprets their meteorological meaning (e.g., identifying typical weather patterns or station types).
- **Advanced Visualizations:** Uses PCA and other dimensionality reduction techniques to visualize clusters in lower-dimensional space.

This notebook is useful for discovering hidden patterns and grouping similar weather stations or conditions.

---


## Requirements

- R and the following packages: `glmnet`, `corrplot`, `pheatmap`, `FactoMineR`, `factoextra`, `caret`, `pls`
- Jupyter or VS Code with R kernel support

---

## Authors

- ESPINOUX Jules
- FALCOZ Nils
- GRUNEWALD Augustin
- PICQ Florian
- FYRD Thomas

