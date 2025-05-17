# Hyperparameter-Tuned Classifier Evaluation Results


> The following table shows the results of the baseline classifiers on the real and synthetic datasets.
> The results are based on 5-fold cross-validation with default parameters.
> The results are displayed in descending order of F1-Score.

## Initial_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.816 (±0.012) | 0.846 | 0.838 | 30.66 | 0.03 |
| GradientBoosting | 0.799 (±0.018) | 0.844 | 0.834 | 30.89 | 0.03 |
| RandomForest | 0.684 (±0.016) | 0.839 | 0.831 | 2.97 | 0.28 |
| XGBoost | 0.808 (±0.018) | 0.827 | 0.818 | 20.95 | 0.04 |
| MLPClassifier | 0.777 (±0.015) | 0.805 | 0.796 | 27.54 | 0.03 |
| $k$NN | 0.737 (±0.013) | 0.796 | 0.776 | 0.12 | 6.40 |
| Decision Tree | 0.686 (±0.015) | 0.767 | 0.754 | 0.08 | 8.99 |
| Baseline | 0.166 (±0.001) | 0.168 | 0.041 | 0.05 | 0.80 |

## Initial_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| RandomForest | 0.637 (±0.007) | 0.822 | 0.811 | 8.91 | 0.09 |
| LGBM | 0.741 (±0.004) | 0.798 | 0.790 | 77.57 | 0.01 |
| GradientBoosting | 0.720 (±0.004) | 0.793 | 0.787 | 223.06 | 0.00 |
| XGBoost | 0.735 (±0.005) | 0.791 | 0.784 | 12.68 | 0.06 |
| MLPClassifier | 0.712 (±0.006) | 0.762 | 0.752 | 234.65 | 0.00 |
| $k$NN | 0.670 (±0.006) | 0.760 | 0.741 | 1.49 | 0.50 |
| Decision Tree | 0.641 (±0.007) | 0.731 | 0.715 | 0.34 | 2.12 |
| Baseline | 0.173 (±0.000) | 0.156 | 0.039 | 0.15 | 0.25 |

## Extra_real_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| LGBM | 0.547 (±0.498) | 0.609 | 0.243 | 875.97 | 0.00 |
| Decision Tree | 0.463 (±0.496) | 0.565 | 0.211 | 3.65 | 0.06 |
| XGBoost | 0.517 (±0.500) | 0.576 | 0.184 | 77.40 | 0.00 |
| MLPClassifier | 0.491 (±0.499) | 0.543 | 0.161 | 604.07 | 0.00 |
| GradientBoosting | 0.526 (±0.499) | 0.587 | 0.146 | 1299.02 | 0.00 |
| $k$NN | 0.546 (±0.496) | 0.576 | 0.127 | 2.79 | 0.05 |
| RandomForest | 0.582 (±0.493) | 0.565 | 0.104 | 98.08 | 0.00 |
| Baseline | 0.571 (±0.495) | 0.565 | 0.103 | 0.55 | 0.19 |

## Extra_real_pseudoreal_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| GradientBoosting | 0.820 (±0.014) | 0.609 | 0.621 | 49.34 | 0.01 |
| XGBoost | 0.831 (±0.017) | 0.543 | 0.542 | 6.44 | 0.08 |
| $k$NN | 0.764 (±0.014) | 0.489 | 0.462 | 0.10 | 4.58 |
| RandomForest | 0.700 (±0.015) | 0.543 | 0.408 | 2.22 | 0.18 |
| LGBM | 0.841 (±0.017) | 0.598 | 0.384 | 37.00 | 0.01 |
| Decision Tree | 0.706 (±0.020) | 0.467 | 0.354 | 0.10 | 3.65 |
| MLPClassifier | 0.792 (±0.016) | 0.435 | 0.251 | 32.84 | 0.01 |
| Baseline | 0.169 (±0.001) | 0.098 | 0.025 | 0.04 | 0.63 |

## Extra_real_pseudoreal_synth_data Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| XGBoost | 0.746 (±0.006) | 0.587 | 0.444 | 18.85 | 0.02 |
| GradientBoosting | 0.734 (±0.007) | 0.565 | 0.418 | 244.37 | 0.00 |
| LGBM | 0.753 (±0.008) | 0.533 | 0.414 | 82.12 | 0.01 |
| MLPClassifier | 0.722 (±0.007) | 0.511 | 0.381 | 273.07 | 0.00 |
| $k$NN | 0.687 (±0.006) | 0.457 | 0.337 | 1.89 | 0.18 |
| RandomForest | 0.648 (±0.005) | 0.435 | 0.320 | 8.27 | 0.04 |
| Decision Tree | 0.656 (±0.006) | 0.337 | 0.241 | 0.35 | 0.69 |
| Baseline | 0.196 (±0.000) | 0.011 | 0.003 | 0.14 | 0.02 |

