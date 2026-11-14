# Exploratory Data Analysis on Retail Sales Data

**Oasis Infobyte | Data Analytics track | Level 1 — Task 1**  
**Author:** Piyush Ramesh Bhor  
**Tools:** Python, pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Objective

Explore retail transactions to understand revenue trends, customer demographics, product-category performance and actionable business recommendations.

## Notebook

Open `Retail_Sales_EDA.ipynb` in Google Colab or Jupyter Notebook and run the cells from top to bottom.

## Dataset and source

- Primary Retail Sales Dataset: downloaded by the notebook from the dataset URL defined in its first data-loading section.
- Supplemental Sample Superstore dataset: used only for a separate product-level ranking because the primary dataset contains product categories rather than individual product/SKU names.

## Methodology

See the notebook for the complete workflow, code, figures, metrics and explanations. The notebook includes data inspection, preprocessing/analysis, charts and findings as appropriate to this task.

## Outputs

After running the notebook, place its generated output files in this folder’s `outputs/` directory. Expected outputs include:

- `monthly_revenue.png`
- `quarterly_revenue.png`
- `quarterly_revenue_trend.png`
- `customer_demographics.png`
- `category_performance.png`
- `top10_products_superstore.png`
- `correlation_heatmap.png`
- `monthly_revenue_by_category.png`
- `retail_sales_cleaned.csv`
- `revenue_by_category.csv`
- `monthly_revenue.csv`

Create the `outputs/` folder if it does not already exist. Some notebooks write outputs to a path shown in their code; copy the resulting files into this folder before committing them to GitHub.

## Limitations and interpretation

**Important dataset limitation:** the primary retail dataset does not include individual product names/SKUs, so the top-10 product ranking uses a separate Sample Superstore dataset and is clearly treated as supplemental analysis. Do not combine its figures with the primary dataset’s sales totals.

## Reproducibility

- Run the notebook in Google Colab or a local Jupyter environment.
- Install dependencies using `pip install -r ../requirements.txt` when running locally.
- If a dataset cannot be downloaded automatically, follow the notebook's dataset-upload prompt.
- Keep the executed notebook outputs and generated files consistent with the version you demonstrate in your video.
