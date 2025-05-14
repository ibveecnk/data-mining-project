# Baseline Classifier Evaluation Results


> The following table shows the results of the baseline classifiers on the real and synthetic datasets.
> The results are based on 5-fold cross-validation with default parameters.
> The results are displayed in descending order of F1-Score.

## Initial_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.816 (±0.016) | 0.839 | 0.831 | 28.46 | 0.03 |
| XGBoost | 0.747 (±0.013) | 0.825 | 0.815 | 30.41 | 0.03 |
| $k$NN | 0.720 (±0.015) | 0.788 | 0.771 | 0.17 | 4.43 |
| GradientBoosting | 0.429 (±0.020) | 0.762 | 0.755 | 12.24 | 0.06 |
| RandomForest | 0.262 (±0.007) | 0.454 | 0.352 | 6.59 | 0.05 |
| Decision Tree | nan (±nan) | 0.349 | 0.249 | 0.05 | 4.61 |

## Initial_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.732 (±0.003) | 0.815 | 0.807 | 88.19 | 0.01 |
| XGBoost | 0.727 (±0.006) | 0.788 | 0.778 | 30.93 | 0.03 |
| $k$NN | 0.674 (±0.005) | 0.755 | 0.735 | 4.58 | 0.16 |
| GradientBoosting | 0.433 (±0.004) | 0.728 | 0.714 | 55.79 | 0.01 |
| RandomForest | 0.261 (±0.001) | 0.418 | 0.320 | 9.09 | 0.04 |
| Decision Tree | nan (±nan) | 0.329 | 0.236 | 0.17 | 1.39 |

## Extra_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.537 (±0.498) | 0.543 | 0.157 | 741.12 | 0.00 |
| XGBoost | 0.562 (±0.496) | 0.565 | 0.144 | 78.96 | 0.00 |
| $k$NN | 0.557 (±0.494) | 0.543 | 0.123 | 3.86 | 0.03 |
| RandomForest | 0.571 (±0.495) | 0.565 | 0.103 | 258.43 | 0.00 |
| GradientBoosting | 0.558 (±0.496) | 0.565 | 0.103 | 744.36 | 0.00 |
| Decision Tree | nan (±nan) | 0.565 | 0.103 | 1.74 | 0.06 |

## Extra_real_pseudoreal_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| $k$NN | 0.748 (±0.015) | 0.576 | 0.458 | 0.15 | 3.08 |
| XGBoost | 0.769 (±0.009) | 0.522 | 0.383 | 2.70 | 0.14 |
| LGBM | 0.838 (±0.018) | 0.565 | 0.360 | 33.90 | 0.01 |
| GradientBoosting | 0.437 (±0.013) | 0.511 | 0.318 | 12.89 | 0.02 |
| RandomForest | 0.260 (±0.005) | 0.065 | 0.062 | 4.29 | 0.01 |
| Decision Tree | nan (±nan) | 0.043 | 0.041 | 0.05 | 0.79 |

## Extra_real_pseudoreal_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| XGBoost | 0.738 (±0.006) | 0.543 | 0.442 | 16.88 | 0.03 |
| LGBM | 0.746 (±0.008) | 0.500 | 0.408 | 88.54 | 0.00 |
| $k$NN | 0.690 (±0.007) | 0.478 | 0.393 | 4.87 | 0.08 |
| GradientBoosting | 0.453 (±0.003) | 0.489 | 0.362 | 62.80 | 0.01 |
| RandomForest | 0.278 (±0.001) | 0.130 | 0.092 | 9.68 | 0.01 |
| Decision Tree | nan (±nan) | 0.054 | 0.055 | 0.17 | 0.33 |

