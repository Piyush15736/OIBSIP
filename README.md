# OIBSIP — Data Analytics Internship Projects

**Intern:** Piyush Ramesh Bhor  
**Track:** Data Analytics  
**Program:** Oasis Infobyte SIP  

This public repository contains three project notebooks prepared for the Data Analytics track. Each project folder contains its notebook, a project-specific README, and an `outputs/` directory for artifacts generated when the notebook is run.

## Projects

| Folder | Task | Project | Main topics |
|---|---|---|---|
| `DataAnalytics-L1-EDARetailSales/` | Level 1 — Task 1 | Exploratory Data Analysis on Retail Sales Data | Revenue trends, demographics, category performance, visualisation, recommendations |
| `DataAnalytics-L1-CleaningData/` | Level 1 — Task 3 | Data Cleaning and Preprocessing | Missing values, duplicates, standardisation, outliers, data types, quality reports |
| `DataAnalytics-L2-HousePricePrediction/` | Level 2 — Task 1 | Predicting House Prices with Linear Regression | EDA, preprocessing, one-hot encoding, regression metrics, residuals, coefficients |

## How to run

1. Open [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
2. Open the `.ipynb` file in the relevant project folder.
3. Run the notebook from top to bottom.
4. Follow any prompts to upload a dataset if an automatic public data-source download is unavailable.
5. The notebooks create their analysis outputs in the relevant `outputs/` folder (or the output folder specified inside the notebook).

## Requirements

The main libraries used across projects are listed in [`requirements.txt`](requirements.txt). Google Colab already includes most common data-science libraries.

## Important notes

- These notebooks are project work and should be explained accurately by the author.
- Data sources and limitations are documented in each project README and notebook.
- The retail project uses a separate supplemental dataset for product-level ranking because the primary retail dataset has categories but no individual product/SKU names.
- The cleaning project intentionally creates a messy practice copy of the Titanic data to demonstrate cleaning methods.
- The house-price model predicts values in the source dataset’s units; do not describe them as Indian rupees.
- Generated output files should be committed after running and reviewing the notebooks. Do not upload empty, fabricated, or unverified output files.

## Suggested citation / disclosure

The work uses publicly available datasets for educational analysis. Dataset ownership remains with the respective dataset publishers. This repository is an educational internship portfolio and is not a production analytics system.
