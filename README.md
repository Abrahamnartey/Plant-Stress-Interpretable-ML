# Plant Stress Interpretable Machine Learning

## Problem
Predict plant stress conditions from transcriptomic data using interpretable machine learning models.

## Data
Publicly available gene expression data from GEO:
- GSE5686 (Arabidopsis stress responses)

## Methods
- Logistic Regression (L1 regularization)
- Random Forest
- SHAP for model interpretability

## Analysis Workflow

1. Data acquisition and preprocessing from GEO
2. Exploratory data analysis and quality control
3. Feature selection and normalization
4. Model training and evaluation
5. Model interpretation using SHAP
6. Biological interpretation of key genes

## Results
Interpretable models achieve competitive classification performance and identify biologically relevant stress-associated genes.

## Reproducibility
Create the analysis environment using:

## Repository Structure
- data/: raw and processed data references
- notebooks/: exploratory and modeling notebooks
- src/: reusable Python scripts
- results/: figures and tables
- paper/: manuscript files
