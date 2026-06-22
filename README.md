# Eye-Cancer-Patient-Outcome-Prediction
This project develops a predictive modeling pipeline combining multi-class machine learning classification and Cox Proportional Hazards survival analysis. 


## Methods
- Data preprocessing using Scikit-learn pipelines
- Model comparison using Stratified 5-Fold Cross-Validation
- Evaluation metric: Macro F1-score
- Models: Logistic Regression, Random Forest, LightGBM, XGBoost
- Model explainability using SHAP
- Survival modeling using Cox Proportional Hazards

## Results
XGBoost achieved the strongest generalization performance on the test set
(Macro F1 = 0.36), balancing bias and variance more effectively than alternative models.

## Explainability
SHAP values were used to identify globally important predictors and understand
directional risk contributions.

## Survival Analysis
A Cox Proportional Hazards model was fitted to estimate time-dependent risk
and hazard ratios for key covariates.

## Tools
Python, Scikit-learn, XGBoost, LightGBM, SHAP, Lifelines

## Author
Steve Musyoka
