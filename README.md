# ICU Mortality Prediction
A risk assessment tool to improve outcomes in the ICU

In this project I use ensemble learning to predict mortality with open source ICU data. The model I have selected is XGBoost, 
hyperparameter tuning was performed through gridsearch and feature selected was performed through iterative random search.
The evaluation metric I have chosen is area under the curve (AUC) for the receiving operator characteristic curve.

Training Data AUC: 0.9077

See  for details [icu_risk_assessment.ipynb](https://github.com/Gabriel-Aspen/icu/blob/main/icu_risk_assessment.ipynb)
