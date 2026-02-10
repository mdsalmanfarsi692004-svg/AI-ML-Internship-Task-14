# Task 14: Model Comparison & Selection

This repository contains a comparative analysis of ML models (Logistic Regression, Decision Tree, Random Forest, SVM) on the Breast Cancer dataset.

## Steps Taken:
1. **Preprocessing**: Scaled features using Standard Scaler.
2. **Training**: Trained 4 different classifiers.
3. **Evaluation**: Compared models using Accuracy, Precision, Recall, and F1-Score.
4. **Selection**: Identified **SVM/Random Forest** as the best performer based on Recall and Accuracy.

## Results Table:
| Model | Accuracy | F1 Score |
| :--- | :--- | :--- |
| **SVM** | ~98% | ~0.97 |
| **Random Forest** | ~96% | ~0.95 |
| **Logistic Regression**| ~95% | ~0.94 |
| **Decision Tree** | ~93% | ~0.92 |

## Files:
* **Task_14_Model_Comparison.ipynb**: Code for training and plotting.
* **best_model.pkl**: The saved best-performing model.
* **Task_14_Report.pdf**: Final analysis report.
