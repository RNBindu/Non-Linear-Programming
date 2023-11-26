# Non-Linear-Programming
### Project Summary:
Problem Statement: Addressing variable selection for regression using mixed integer quadratic programming (MIQP) compared to the LASSO approach.

### Objective: Evaluate whether MIQP for variable selection in regression outperforms LASSO's shrinkage technique.

### Methodology:
- MIQP Approach:
Introduction of binary variables (Zj) to enforce 𝛽𝑗 values and control variable inclusion.
Flexibility in precise variable selection for impactful models.
Inclusion of an intercept term (𝛽0) and hyperparameter tuning (k) through cross-validation.
- LASSO Approach:
Sparse variable selection by shrinking 𝛽 coefficients.
Overfitting prevention and intercept term inclusion without penalty.


### Results and Comparison:
- Performance Metrics:
MIQP showed superior performance in certain error metrics, demonstrating lower SSE and MSE, but similar R-squared values to LASSO.
LASSO exhibited a comparative ability to explain data variability.

- Findings and Considerations:

1. MIQP Advantages:

Enhanced accuracy in test sets, although computationally demanding.
Robustness in predicting outcomes with the optimal hyperparameter k.

2. LASSO Advantages:

Efficiency in computational resources and quick model updates.
Ease of implementation, especially for individuals with limited coding experience.


### Comparison Analysis:
Number of Non-Zero Coefficients:

LASSO identified 17 significant features compared to MIQP's 10, influencing model interpretability and performance.


### Conclusion and Recommendations:
Method Selection Criteria:
Suggested considerations for method selection based on computational resources, model performance, and ease of implementation.
Future Directions:
Highlighted the need for a balanced discussion and thoughtful consideration of specific business objectives in method selection.
