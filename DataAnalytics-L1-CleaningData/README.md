# Data Cleaning and Preprocessing

**Oasis Infobyte | Data Analytics track | Level 1 — Task 3**  
**Author:** Piyush Ramesh Bhor  
**Tools:** Python, pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Objective

Demonstrate a reproducible data-cleaning workflow: data-quality checks, missing-value treatment, duplicate removal, standardisation, outlier screening, type correction and before/after reporting.

## Notebook

Open `Data_Cleaning_and_Preprocessing.ipynb` in Google Colab or Jupyter Notebook and run the cells from top to bottom.

## Dataset and source

- Titanic passenger dataset: source URL is defined in the notebook. If automatic retrieval is unavailable, the notebook asks for a local CSV upload.

## Methodology

See the notebook for the complete workflow, code, figures, metrics and explanations. The notebook includes data inspection, preprocessing/analysis, charts and findings as appropriate to this task.

## Outputs

After running the notebook, place its generated output files in this folder’s `outputs/` directory. Expected outputs include:

- `titanic_cleaned.csv`
- `titanic_messy_practice.csv`
- `quality_report_before.csv`
- `quality_report_after.csv`
- `before_after_summary.csv`
- `dtype_verification.csv`
- `outlier_summary.csv`
- `missing_values_before.png`
- `before_after_distributions.png`

Create the `outputs/` folder if it does not already exist. Some notebooks write outputs to a path shown in their code; copy the resulting files into this folder before committing them to GitHub.

## Limitations and interpretation

The notebook creates a deliberately messy practice copy from a source Titanic dataset in order to demonstrate cleaning decisions. The original source data is kept separate from the modified practice copy. Outlier handling is documented; review the justification for capping high fares because extreme values can be valid observations.

## Reproducibility

- Run the notebook in Google Colab or a local Jupyter environment.
- Install dependencies using `pip install -r ../requirements.txt` when running locally.
- If a dataset cannot be downloaded automatically, follow the notebook's dataset-upload prompt.
- Keep the executed notebook outputs and generated files consistent with the version you demonstrate in your video.
