# Feature Selection

- selecting the most useful features and moving the rest.

## why this is important ?
- reduces noice and overfitting
- speeds up training
-  improves model accuracy
-  makes model interpretation easier



1. Filter methods ( pure statistics)
- Correlation matrix ->  remove highly correlated features.
- Chi-square test (categorical vs categorical).
- ANOVA F-test (numrical vs categorical target).

2. Embedded Methods (selection built into the model)
- Lasso Regression -> shrinks coefficients to  0
- Tree-based models ( Random forest, XGBoost)
   -> Feature importance scores