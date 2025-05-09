# Baseline Classifier Evaluation Results


> The following table shows the results of the baseline classifiers on the real and synthetic datasets.
> The results are based on 5-fold cross-validation with default parameters.
> The results are displayed in descending order of F1-Score.

## Real Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| RidgeClassifier | 0.485 (±0.035) | 0.583 | 0.197 | 0.62 | 0.32 |
| LGBM | 0.528 (±0.067) | 0.469 | 0.188 | 28.86 | 0.01 |
| XGBoost | 0.565 (±0.018) | 0.469 | 0.186 | 1.49 | 0.12 |
| KNN | 0.547 (±0.025) | 0.427 | 0.186 | 0.11 | 1.65 |
| SVC | 0.559 (±0.016) | 0.406 | 0.176 | 2.23 | 0.08 |

## Pseudoreal Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| SVC | 0.503 (±0.040) | 0.510 | 0.328 | 0.73 | 0.45 |
| KNN | 0.753 (±0.030) | 0.365 | 0.304 | 0.15 | 2.04 |
| XGBoost | 0.765 (±0.085) | 0.385 | 0.264 | 2.82 | 0.09 |
| LGBM | 0.834 (±0.098) | 0.323 | 0.253 | 97.33 | 0.00 |
| RidgeClassifier | 0.536 (±0.038) | 0.292 | 0.197 | 0.32 | 0.62 |

## Real+synthetic Dataset

| Classifier | CV Accuracy | Test Accuracy | Test F1-Score | Training Time (s) | Efficiency (F1/s) |
|------------|-------------|---------------|---------------|------------------| ------------------ |
| KNN | 0.685 (±0.013) | 0.479 | 0.366 | 5.14 | 0.07 |
| SVC | 0.592 (±0.005) | 0.500 | 0.352 | 88.51 | 0.00 |
| LGBM | 0.770 (±0.015) | 0.260 | 0.278 | 423.68 | 0.00 |
| XGBoost | 0.752 (±0.013) | 0.271 | 0.232 | 15.76 | 0.01 |
| RidgeClassifier | 0.553 (±0.002) | 0.229 | 0.184 | 2.70 | 0.07 |

