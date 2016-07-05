# iPLS
Source code for 'An Adaptive Partial Least Squares Method for Integrating Independent Cohorts'

iPLS base: main functions for iPLS, tuning selection, data generation, evaluation

iPLS analysis (breast cancer): code for breast cancer analysis

iPLS simulation: code for simulation study

# Data
clin_IVS/STR/WNG_ERp/ERn: (.npy) post-processed datasets for clinical variables (IVS/STR/WNG: cohorts, ERp/ERn: ER-positive/negative), columns are [relapse-free survival months, event of relapse, ER status (+)]

data_IVS/STR/WNG_ERp/ERn: (text file) post-processed datasets for gene expression (IVS/STR/WNG: cohorts, ERp/ERn: ER-positive/negative)

var_full: (.npy) post-processed (filtered) variables

obs_IVS/STR/WNG: (.npy) observations (IVS/STR/WNG: cohorts)
