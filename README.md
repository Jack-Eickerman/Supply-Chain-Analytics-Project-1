# Supply-Chain-Analytics-Project-1
Analysis of Example Data in a Retail Setting
# Retail Stockout Analysis

This repository contains the code for **Assignment 1** in a Supply Chain Analytics Project (SCAP). It analyzes retail transaction, inventory, and warehouse data to:

- Clean and preprocess sales and stock datasets
- Identify **stockout dates** per product and supplier (when cumulative sales exceed initial stock)
- Explore monthly sales trends by category and region
- Compare sales performance across European regions (Central, Western, Northern, Southern)
- Perform statistical tests (t-test, ANOVA, correlation analysis)
- Visualize trends, distributions, and correlations

Built entirely with pandas, numpy, matplotlib, seaborn, and scipy — no external APIs or ML models required.

## Features
- **Stockout detection**: Simulates depletion of supplier stock based on ordered units over time
- **Regional insights**: Average units sold, top products, and statistical comparison of sales distributions
- **Outlier handling**: IQR-based removal for realistic analysis
- **Visualizations**: Time-series plots, heatmaps, boxplots, histograms with statistical overlays
- Interactive product selection for stockout queries (via simple input)

## Datasets
- Product master
- Supplier stock levels
- Sales transactions
- Warehouse information
