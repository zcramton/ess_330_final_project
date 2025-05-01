Changes

5/1/25 04:00
- 10cv_fold -> bootstraps for resamples, better for small (n = 25) data stability
- cut nn_model from data, unlikely to be effective with small (n = 25) data
- cut lasso_model, replaced with lm_model for better interpretability and no step_normalize()