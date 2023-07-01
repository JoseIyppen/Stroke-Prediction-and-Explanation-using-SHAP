# Stroke-Prediction-and-Explanation-using-SHAP
In this notebook, I will attempt the task of predicting an individual's likelihood of experiencing a stroke.

To begin, I will use EDA, aiming to identify the key features that could potentially indicate the chance of a stroke. Chi-square test will be used in feature engineering.
Moving forward, I will train multiple models and carefully evaluate their performance, taking F1 score or positive class specific recall as metric. 
I will be employing SMOTE for addressing the imbalanceness of the data. I will select the best performing model using cross validation and grid search.

Additionally, I will utilize SHAP (SHapley Additive exPlanations) to explain important features of the model and how they influence the classification.
