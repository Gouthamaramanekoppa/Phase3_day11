# Phase3_day11

Evaluation Metrics Generated

1. Confusion Matrix
The confusion matrix helps visualize prediction results across all classes.
It shows:
Correct predictions
Misclassifications
Model bias toward any class

This is essential for understanding where the model fails.

2. Precision, Recall, F1-Score
Instead of relying only on accuracy, more reliable metrics were computed:
Precision → How many predicted positives were correct
Recall → How many actual positives were detected
F1 Score → Balance between precision & recall

These metrics are especially important for imbalanced datasets.

3. Classification Report
A full classification report was generated including:
Class-wise precision
Class-wise recall
F1 score
Support values

This gives a complete performance overview.

Final Evaluation Results
Metric	          Score
Test Accuracy	     95%
Precision	         94%
Recall	           93%
F1 Score	         93%

The optimized model shows strong generalization performance.

Error Analysis (Initial)
Misclassified samples were inspected manually.

Common failure cases:
Low-quality or noisy images
Visually similar classes
Poor lighting or unusual angles

This insight is important for future improvements.

Day 11 — Model Evaluation Completed

Completed Tasks

Generated predictions on test dataset
Computed confusion matrix
Generated classification report
Performed initial error analysis

Key Result
Optimized model achieved strong performance and is ready for final reporting.
