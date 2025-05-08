# Supervised Learning 
## Introduction
While working as an analyst for Beta Bank, use data on clients’ past behavior and termination of contracts to predict whether a customer will leave the bank soon. Build a model with the maximum possible F1 score. Accomplsh with an F1 score of at least 0.59. Check the F1 for the test set. Additionally, measure the AUC-ROC metric and compare it with the F1.
## Project
- Data was loaded in and initially analyzed
- The data was preprocessed to deal with duplicates and null values
- Data was prepared for model training
  - One-Hot encoding was performed
  - target and features were declared
  - data was split for training, validation, and testing
  - data was standardized
- Three models were trained:
  - Logistic Regression
  - Decision tree classifier 
  - Random forest classifier
- Models were trained for parameter optimization and upscaled or downscaled to provide best f1 score
## Conclusion
The random forest classifier came to be the best model for prediction. The parameters used to get an f1 score of 0.61 and AUC-ROC score of 0.83 were number of estimators at 21, and a depth of 17, while also using an upscaled dataset. The model predicted that of the 2000 people using beta bank in the test set, 368 of them would leave the bank.
