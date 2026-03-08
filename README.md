# HAR Activation Functions Exploration

This repository contains dissertation experiments on Human Activity Recognition (HAR), focused on comparing activation-function variants in deep learning models.

## Project Scope
- Dataset pipelines for UCI-HAPT and WISDM
- CNN, LSTM, and CNN-LSTM architectures
- Custom and standard activation functions (ReLU, Tanh, ELU, PReLU, CReLU, and custom nonlinear variants)
- Evaluation outputs including confusion-matrix-based metrics and Pareto-style trade-off analysis

## Main Notebook
- `HAR_Activation_Functions_Dissertation.ipynb`

The notebook is kept clean in version control:
- outputs cleared
- execution counts reset
- analysis logic preserved

## Data and Artifacts
Repository includes raw and processed files used during experimentation (datasets, cached CSV/PKL outputs, and result folders).

## Reproducibility Notes
Some sections load cached CSV results to avoid re-running long training jobs. Re-run full training only when needed and when compute resources are available.
