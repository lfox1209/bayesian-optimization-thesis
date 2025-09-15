# Bayesian Optimization in Quantitative Finance

This repository contains the code and results accompanying the MSc thesis  
*"Advancing Bayesian Optimization in Quantitative Finance"* (University College London, 2025).

## Contents
- `01_framework_comparison.ipynb` — Comparison of Hyperopt and Optuna on a synthetic benchmark function  
- `02_batch_bo.ipynb` — Sequential vs. Batch Bayesian Optimization in the DRACUS backtesting environment  
- `03_results_oos_robustness.ipynb` — Out-of-sample validation, robustness and sensitivity analysis  
- `MSc_Thesis_Bayesian_Optimization_Fuchs.pdf` — Full thesis text  

**Note:** The DRACUS backtesting system referenced in the thesis is proprietary and not included in this repository.  
The notebooks illustrate its usage conceptually, but the implementation itself is not publicly available.

## Usage
The notebooks can be opened and run with Jupyter.  
A standard Python 3.10+ environment with the following packages is required:  
`numpy`, `pandas`, `matplotlib`, `optuna`, `hyperopt`.  

## License
This project is released under the MIT License.
