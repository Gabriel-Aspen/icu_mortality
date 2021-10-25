# ICU Mortality Prediction
A risk assessment tool to improve outcomes in the ICU

In this project I use ensemble learning to predict mortality with open source ICU data. Features include basic demographic information,
lab values, vital signs and health comorbidities, as well as risk assessment scores from other severtiy-of-disease systems such as APACHE

The model I have selected is XGBoost, 
hyperparameter tuning was performed through gridsearch and feature selected was performed through iterative random search.
The evaluation metric I have chosen is area under the curve (AUC) for the receiving operator characteristic curve.

**Training Data AUC: 0.9077**

See notebook for details [icu_risk_assessment.ipynb](https://github.com/Gabriel-Aspen/icu/blob/main/icu_risk_assessment.ipynb)

Data can be found [here](https://www.kaggle.com/c/widsdatathon2020/data)
