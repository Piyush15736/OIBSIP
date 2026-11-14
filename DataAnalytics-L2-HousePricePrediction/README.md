# Predicting House Prices with Linear Regression

**Oasis Infobyte | Data Analytics track | Level 2 — Task 1**  
**Author:** Piyush Ramesh Bhor  
**Tools:** Python, pandas, NumPy, scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

## Objective

Build and evaluate a regression model to estimate residential sale prices from property attributes, from EDA and preprocessing through model interpretation.

## Notebook

Open `House_Price_Prediction_Linear_Regression.ipynb` in Google Colab or Jupyter Notebook and run the cells from top to bottom.

## Dataset and source

- Ames Housing / House Prices dataset: the notebook first attempts to retrieve it through scikit-learn OpenML (`fetch_openml`). It includes fallback CSV retrieval and a manual CSV-upload option.

## Methodology

See the notebook for the complete workflow, code, figures, metrics and explanations. The notebook includes data inspection, preprocessing/analysis, charts and findings as appropriate to this task.

## Outputs

After running the notebook, place its generated output files in this folder’s `outputs/` directory. Expected outputs include:

- `model_metrics.csv`
- `model_comparison.csv`
- `test_set_predictions.csv`
- `model_coefficients.csv`
- `run_summary.csv`
- `01_house_price_distribution.png`
- `02_correlation_heatmap.png`
- `03_actual_vs_predicted.png`
- `04_residual_plot.png`
- `05_residual_distribution.png`
- `06_top_model_coefficients.png`

Create the `outputs/` folder if it does not already exist. Some notebooks write outputs to a path shown in their code; copy the resulting files into this folder before committing them to GitHub.

## Limitations and interpretation

The target price is the dataset’s SalePrice and is expressed in the source dataset’s currency units; it must not be relabelled as INR. Linear Regression is the required model. Ridge Regression is an optional comparison and should be described as such.

## Reproducibility

- Run the notebook in Google Colab or a local Jupyter environment.
- Install dependencies using `pip install -r ../requirements.txt` when running locally.
- If a dataset cannot be downloaded automatically, follow the notebook's dataset-upload prompt.
- Keep the executed notebook outputs and generated files consistent with the version you demonstrate in your video.
