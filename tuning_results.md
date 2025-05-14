# Baseline Classifier Evaluation Results


> The following table shows the results of the baseline classifiers on the real and synthetic datasets.
> The results are based on 5-fold cross-validation with default parameters.
> The results are displayed in descending order of F1-Score.

## Initial_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| XGBoost | 0.746 (±0.014) | 0.815 | 0.810 | 15.18 | 0.05 |
| $k$NN | 0.679 (±0.013) | 0.761 | 0.743 | 0.14 | 5.45 |
| GradientBoosting | 0.323 (±0.006) | 0.645 | 0.621 | 5.02 | 0.12 |
| RandomForest | 0.206 (±0.003) | 0.379 | 0.272 | 3.99 | 0.07 |
| Decision Tree | 0.241 (±0.012) | 0.287 | 0.170 | 0.04 | 4.22 |

## Initial_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| XGBoost | 0.721 (±0.005) | 0.822 | 0.819 | 24.04 | 0.03 |
| $k$NN | 0.680 (±0.004) | 0.739 | 0.725 | 2.73 | 0.27 |
| GradientBoosting | 0.345 (±0.001) | 0.649 | 0.626 | 19.61 | 0.03 |
| Decision Tree | 0.256 (±0.001) | 0.291 | 0.170 | 0.17 | 1.03 |
| RandomForest | 0.217 (±0.000) | 0.308 | 0.160 | 5.14 | 0.03 |

## Extra_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| $k$NN | 0.577 (±0.494) | 0.573 | 0.105 | 1.95 | 0.05 |
| RandomForest | 0.570 (±0.495) | 0.573 | 0.104 | 161.98 | 0.00 |
| Decision Tree | 0.570 (±0.495) | 0.573 | 0.104 | 2.08 | 0.05 |
| XGBoost | 0.565 (±0.496) | 0.531 | 0.101 | 43.84 | 0.00 |
| GradientBoosting | 0.571 (±0.495) | 0.521 | 0.101 | 328.53 | 0.00 |

## Extra_real_pseudoreal_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| XGBoost | 0.778 (±0.021) | 0.510 | 0.381 | 7.32 | 0.05 |
| $k$NN | 0.709 (±0.027) | 0.365 | 0.324 | 0.12 | 2.73 |
| GradientBoosting | 0.333 (±0.010) | 0.312 | 0.239 | 6.36 | 0.04 |
| RandomForest | 0.206 (±0.004) | 0.062 | 0.078 | 3.27 | 0.02 |
| Decision Tree | 0.246 (±0.010) | 0.115 | 0.077 | 0.05 | 1.54 |

## Extra_real_pseudoreal_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| XGBoost | 0.738 (±0.006) | 0.417 | 0.310 | 22.61 | 0.01 |
| $k$NN | 0.696 (±0.004) | 0.333 | 0.289 | 3.37 | 0.09 |
| GradientBoosting | 0.360 (±0.001) | 0.281 | 0.207 | 24.55 | 0.01 |
| Decision Tree | 0.251 (±0.002) | 0.073 | 0.048 | 0.19 | 0.25 |
| RandomForest | 0.230 (±0.000) | 0.021 | 0.012 | 6.17 | 0.00 |

