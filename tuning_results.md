# Baseline Classifier Evaluation Results


> The following table shows the results of the baseline classifiers on the real and synthetic datasets.
> The results are based on 5-fold cross-validation with default parameters.
> The results are displayed in descending order of F1-Score.

## Initial_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| XGBoost | 0.750 (±0.013) | 0.825 | 0.815 | 7.13 | 0.11 |
| LGBM | 0.810 (±0.015) | 0.820 | 0.810 | 6.79 | 0.12 |
| $k$NN | 0.682 (±0.018) | 0.755 | 0.731 | 0.13 | 5.81 |
| GradientBoosting | 0.325 (±0.014) | 0.651 | 0.630 | 5.27 | 0.12 |
| RandomForest | 0.210 (±0.004) | 0.389 | 0.279 | 3.82 | 0.07 |
| Decision Tree | 0.238 (±0.010) | 0.276 | 0.163 | 0.04 | 4.14 |

## Initial_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.734 (±0.003) | 0.817 | 0.809 | 50.50 | 0.02 |
| XGBoost | 0.725 (±0.006) | 0.788 | 0.778 | 42.83 | 0.02 |
| $k$NN | 0.682 (±0.005) | 0.755 | 0.735 | 2.55 | 0.29 |
| GradientBoosting | 0.338 (±0.003) | 0.613 | 0.578 | 20.15 | 0.03 |
| Decision Tree | 0.256 (±0.002) | 0.276 | 0.163 | 0.16 | 0.99 |
| RandomForest | 0.209 (±0.001) | 0.310 | 0.154 | 5.24 | 0.03 |

## Extra_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.536 (±0.498) | 0.543 | 0.157 | 250.79 | 0.00 |
| $k$NN | 0.575 (±0.494) | 0.576 | 0.126 | 1.89 | 0.07 |
| RandomForest | 0.571 (±0.495) | 0.565 | 0.103 | 161.12 | 0.00 |
| GradientBoosting | 0.570 (±0.495) | 0.565 | 0.103 | 329.05 | 0.00 |
| XGBoost | 0.555 (±0.496) | 0.565 | 0.103 | 45.67 | 0.00 |
| Decision Tree | 0.571 (±0.495) | 0.565 | 0.103 | 1.92 | 0.05 |

## Extra_real_pseudoreal_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| XGBoost | 0.774 (±0.011) | 0.522 | 0.383 | 23.82 | 0.02 |
| LGBM | 0.835 (±0.019) | 0.543 | 0.343 | 12.90 | 0.03 |
| $k$NN | 0.715 (±0.015) | 0.391 | 0.293 | 0.12 | 2.45 |
| GradientBoosting | 0.332 (±0.010) | 0.304 | 0.203 | 6.30 | 0.03 |
| RandomForest | 0.208 (±0.003) | 0.076 | 0.070 | 3.34 | 0.02 |
| Decision Tree | 0.247 (±0.011) | 0.076 | 0.055 | 0.05 | 1.09 |

## Extra_real_pseudoreal_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.747 (±0.008) | 0.543 | 0.420 | 50.90 | 0.01 |
| XGBoost | 0.737 (±0.006) | 0.522 | 0.417 | 36.24 | 0.01 |
| $k$NN | 0.696 (±0.007) | 0.478 | 0.393 | 3.60 | 0.11 |
| GradientBoosting | 0.360 (±0.002) | 0.348 | 0.300 | 23.82 | 0.01 |
| Decision Tree | 0.256 (±0.010) | 0.076 | 0.055 | 0.17 | 0.33 |
| RandomForest | 0.229 (±0.000) | 0.033 | 0.018 | 6.25 | 0.00 |

