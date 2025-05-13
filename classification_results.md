# Baseline Classifier Evaluation Results


> The following table shows the results of the baseline classifiers on the real and synthetic datasets.
> The results are based on 5-fold cross-validation with default parameters.
> The results are displayed in descending order of F1-Score.

## Initial_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| XGBoost | 0.734 (±0.013) | 0.799 | 0.793 | 2.26 | 0.35 |
| LGBM | 0.796 (±0.013) | 0.796 | 0.791 | 8.90 | 0.09 |
| $k$NN | 0.671 (±0.014) | 0.725 | 0.701 | 0.12 | 5.73 |
| GradientBoosting | 0.317 (±0.009) | 0.645 | 0.621 | 5.48 | 0.11 |
| Random Forest | 0.216 (±0.004) | 0.462 | 0.373 | 4.82 | 0.08 |

## Initial_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.714 (±0.006) | 0.801 | 0.795 | 50.88 | 0.02 |
| XGBoost | 0.707 (±0.005) | 0.775 | 0.767 | 12.29 | 0.06 |
| $k$NN | 0.664 (±0.005) | 0.725 | 0.706 | 2.53 | 0.28 |
| GradientBoosting | 0.336 (±0.002) | 0.635 | 0.603 | 22.16 | 0.03 |
| Random Forest | 0.236 (±0.002) | 0.422 | 0.333 | 5.63 | 0.06 |

## Extra_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.548 (±0.498) | 0.490 | 0.131 | 197.83 | 0.00 |
| $k$NN | 0.571 (±0.495) | 0.562 | 0.123 | 1.91 | 0.06 |
| Random Forest | 0.570 (±0.495) | 0.573 | 0.104 | 160.88 | 0.00 |
| XGBoost | 0.560 (±0.496) | 0.573 | 0.104 | 38.38 | 0.00 |
| GradientBoosting | 0.573 (±0.495) | 0.531 | 0.102 | 316.00 | 0.00 |

## Extra_real_pseudoreal_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| $k$NN | 0.698 (±0.019) | 0.344 | 0.341 | 0.12 | 2.96 |
| LGBM | 0.821 (±0.022) | 0.448 | 0.341 | 12.45 | 0.03 |
| XGBoost | 0.759 (±0.020) | 0.469 | 0.339 | 3.16 | 0.11 |
| GradientBoosting | 0.324 (±0.008) | 0.312 | 0.213 | 5.85 | 0.04 |
| Random Forest | 0.219 (±0.004) | 0.125 | 0.086 | 3.07 | 0.03 |

## Extra_real_pseudoreal_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.731 (±0.005) | 0.469 | 0.336 | 52.42 | 0.01 |
| XGBoost | 0.724 (±0.006) | 0.438 | 0.310 | 13.48 | 0.02 |
| $k$NN | 0.681 (±0.007) | 0.354 | 0.306 | 3.00 | 0.10 |
| GradientBoosting | 0.349 (±0.002) | 0.292 | 0.199 | 22.84 | 0.01 |
| Random Forest | 0.243 (±0.001) | 0.219 | 0.134 | 6.07 | 0.02 |

