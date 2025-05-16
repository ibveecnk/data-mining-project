# Hyperparameter-Tuned Classifier Evaluation Results


> The following table shows the results of the baseline classifiers on the real and synthetic datasets.
> The results are based on 5-fold cross-validation with default parameters.
> The results are displayed in descending order of F1-Score.

## Initial_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.816 (±0.016) | 0.839 | 0.831 | 33.42 | 0.02 |
| XGBoost | 0.747 (±0.013) | 0.825 | 0.815 | 20.62 | 0.04 |
| $k$NN | 0.719 (±0.015) | 0.788 | 0.771 | 0.19 | 4.01 |
| GradientBoosting | 0.429 (±0.020) | 0.762 | 0.755 | 14.97 | 0.05 |
| RandomForest | 0.262 (±0.007) | 0.454 | 0.352 | 6.54 | 0.05 |
| Decision Tree | nan (±nan) | 0.349 | 0.249 | 0.04 | 5.85 |
| Baseline | 0.166 (±0.001) | 0.168 | 0.041 | 0.02 | 1.71 |

## Initial_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.732 (±0.003) | 0.815 | 0.807 | 103.25 | 0.01 |
| XGBoost | 0.727 (±0.006) | 0.788 | 0.778 | 17.86 | 0.04 |
| $k$NN | 0.674 (±0.005) | 0.755 | 0.735 | 4.38 | 0.17 |
| GradientBoosting | 0.433 (±0.004) | 0.728 | 0.714 | 57.50 | 0.01 |
| RandomForest | 0.261 (±0.001) | 0.418 | 0.320 | 9.57 | 0.03 |
| Decision Tree | nan (±nan) | 0.329 | 0.236 | 0.17 | 1.43 |
| Baseline | 0.173 (±0.000) | 0.156 | 0.039 | 0.13 | 0.31 |

## Extra_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.537 (±0.498) | 0.543 | 0.157 | 843.45 | 0.00 |
| XGBoost | 0.562 (±0.496) | 0.565 | 0.144 | 115.65 | 0.00 |
| $k$NN | 0.557 (±0.494) | 0.543 | 0.123 | 4.79 | 0.03 |
| RandomForest | 0.571 (±0.495) | 0.565 | 0.103 | 277.33 | 0.00 |
| GradientBoosting | 0.558 (±0.496) | 0.565 | 0.103 | 757.10 | 0.00 |
| Decision Tree | nan (±nan) | 0.565 | 0.103 | 1.50 | 0.07 |
| Baseline | 0.571 (±0.495) | 0.565 | 0.103 | 0.37 | 0.28 |

## Extra_real_pseudoreal_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| $k$NN | 0.748 (±0.015) | 0.576 | 0.458 | 0.20 | 2.28 |
| XGBoost | 0.769 (±0.009) | 0.522 | 0.383 | 38.68 | 0.01 |
| LGBM | 0.838 (±0.018) | 0.565 | 0.360 | 38.17 | 0.01 |
| GradientBoosting | 0.437 (±0.013) | 0.511 | 0.318 | 16.93 | 0.02 |
| RandomForest | 0.260 (±0.005) | 0.065 | 0.062 | 5.34 | 0.01 |
| Decision Tree | nan (±nan) | 0.043 | 0.041 | 0.05 | 0.88 |
| Baseline | 0.169 (±0.001) | 0.098 | 0.025 | 0.03 | 0.97 |

## Extra_real_pseudoreal_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| XGBoost | 0.738 (±0.006) | 0.543 | 0.442 | 37.13 | 0.01 |
| LGBM | 0.745 (±0.009) | 0.500 | 0.408 | 114.46 | 0.00 |
| $k$NN | 0.690 (±0.007) | 0.478 | 0.393 | 5.48 | 0.07 |
| GradientBoosting | 0.453 (±0.003) | 0.489 | 0.362 | 71.13 | 0.01 |
| RandomForest | 0.278 (±0.001) | 0.130 | 0.092 | 11.35 | 0.01 |
| Decision Tree | nan (±nan) | 0.054 | 0.055 | 0.18 | 0.30 |
| Baseline | 0.196 (±0.000) | 0.011 | 0.003 | 0.13 | 0.02 |

