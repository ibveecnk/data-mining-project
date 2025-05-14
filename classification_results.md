# Baseline Classifier Evaluation Results


> The following table shows the results of the baseline classifiers on the real and synthetic datasets.
> The results are based on 5-fold cross-validation with default parameters.
> The results are displayed in descending order of F1-Score.

## Initial_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.810 (±0.013) | 0.827 | 0.823 | 14.82 | 0.06 |
| XGBoost | 0.746 (±0.014) | 0.815 | 0.810 | 7.20 | 0.11 |
| $k$NN | 0.672 (±0.016) | 0.756 | 0.738 | 0.85 | 0.87 |
| GradientBoosting | 0.323 (±0.010) | 0.649 | 0.626 | 15.30 | 0.04 |
| Random Forest | 0.206 (±0.003) | 0.379 | 0.272 | 15.82 | 0.02 |

## Initial_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| XGBoost | 0.721 (±0.005) | 0.822 | 0.819 | 35.19 | 0.02 |
| LGBM | 0.732 (±0.007) | 0.818 | 0.815 | 58.51 | 0.01 |
| $k$NN | 0.679 (±0.003) | 0.737 | 0.721 | 7.80 | 0.09 |
| GradientBoosting | 0.345 (±0.001) | 0.633 | 0.607 | 63.58 | 0.01 |
| Random Forest | 0.217 (±0.000) | 0.308 | 0.160 | 20.73 | 0.01 |

## Extra_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.536 (±0.498) | 0.500 | 0.131 | 257.06 | 0.00 |
| $k$NN | 0.577 (±0.494) | 0.573 | 0.105 | 4.39 | 0.02 |
| Random Forest | 0.570 (±0.495) | 0.573 | 0.104 | 444.22 | 0.00 |
| XGBoost | 0.565 (±0.496) | 0.531 | 0.101 | 130.00 | 0.00 |
| GradientBoosting | 0.572 (±0.495) | 0.510 | 0.099 | 736.99 | 0.00 |

## Extra_real_pseudoreal_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| XGBoost | 0.779 (±0.021) | 0.510 | 0.381 | 7.60 | 0.05 |
| $k$NN | 0.701 (±0.026) | 0.344 | 0.301 | 0.43 | 0.71 |
| LGBM | 0.838 (±0.020) | 0.479 | 0.292 | 10.93 | 0.03 |
| GradientBoosting | 0.332 (±0.009) | 0.333 | 0.247 | 17.46 | 0.01 |
| Random Forest | 0.206 (±0.004) | 0.062 | 0.078 | 9.73 | 0.01 |

## Extra_real_pseudoreal_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.747 (±0.004) | 0.490 | 0.372 | 49.65 | 0.01 |
| XGBoost | 0.738 (±0.006) | 0.417 | 0.310 | 38.68 | 0.01 |
| $k$NN | 0.695 (±0.005) | 0.312 | 0.274 | 9.52 | 0.03 |
| GradientBoosting | 0.360 (±0.001) | 0.281 | 0.207 | 73.85 | 0.00 |
| Random Forest | 0.230 (±0.000) | 0.021 | 0.012 | 29.80 | 0.00 |

