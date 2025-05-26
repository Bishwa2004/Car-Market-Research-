# Car-Market-Research & Demand estimation
## 🛠️ Project Update – May 26, 2025

This repository currently contains the codebase and analysis developed during my Spring 2025 Economics research course. Over the summer, I plan to extend this work by incorporating **up-to-date 2025 vehicle data** and writing new reports to reflect current market trends. This will serve as a self-directed summer research initiative to deepen my understanding of demand estimation and automotive economics.

## 🤖 AI Assistance Disclosure
Some aspects of this project—such as code formatting, markdown structure, and documentation—were enhanced with the support of OpenAI's ChatGPT. However, all statistical modeling, economic interpretation, and dataset integration were independently developed.
# 🚗 Car Market Research - Demand Estimation (2005)

This repository contains a comprehensive project focused on estimating car demand using data from the 2005 U.S. automobile market. The analysis is divided into multiple notebooks, where each part walks through the steps of importing, cleaning, analyzing, and modeling the data using econometric techniques.

## 📂 Repository Structure


## 📊 Project Objective

To understand and model consumer demand for vehicles using real-world data from 2005. The ultimate goal is to estimate price elasticities and assess how vehicle attributes like horsepower, fuel efficiency, and footprint influence purchasing behavior.

---

## 🔍 Key Features

- **Data Cleaning**: Handles missing values, inconsistent formatting, and type conversion.
- **Descriptive Statistics**: Summarizes data by vehicle type, fuel type, hybrid status, etc.
- **Instrumental Variable (IV) Regression**: Tackles price endogeneity using cost-shifters.
- **Elasticity Estimation**: Measures sensitivity of quantity demanded to changes in price.
- **Model Interpretation**: Uses log-log regression outputs and robust standard errors.
- **Plots & Visuals**: Histogram and scatter plots for data visualization and EDA.

---

## 📘 Notebooks Breakdown

### ✅ `demand_estimation_PART 1.ipynb`
- Imports and inspects 2005 vehicle and sales data
- Cleans and merges datasets
- Generates summary statistics and plots

### ✅ `Demand_estimation_PART 2.ipynb`
- Constructs first-stage regression (price instruments)
- Performs second-stage log-linear regression
- Calculates price elasticity and interprets coefficients

### ✅ `CAR DEMAND ESTIMATION on 2005 data.ipynb`
- Consolidated notebook that includes all steps
- Great for running the project end-to-end in one place

---

## 📁 Data Sources

The dataset contains:
- Vehicle characteristics (horsepower, footprint, hybrid, fuel type, etc.)
- Sales volume (quantity)
- Manufacturer suggested retail prices (MSRP)
- Household demographic data for market sizing (optional in extended versions)

> Note: Some external sources like [FRED](https://fred.stlouisfed.org/) or EPA datasets may have been merged if noted in notebook code cells.

---

## ⚙️ Dependencies

Make sure you install the following Python libraries before running the notebooks:

```bash
pip install pandas numpy matplotlib seaborn statsmodels openpyxl
