# Diabetes-prediction-using-linear-learner-and-XGBoost

# Introduction

TO build, deploy, and evaluate two different models to distinguish between people who will and will not get diabetes in the next 5 years.

# Data

The data is a set of medical measurements made on the Pima Indians (who live near Phoenix, AZ), and a target “will_get_diabietes” that indicates the true outcome.

you can find the data at  'https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.csv'

# Models

Used Amazon's sagemaker to build models, used amazon specific linear learner and XGBoost models. Used metrics AUC and logloss to compare both models and to choose which models suits better for this data.

# Conclusion

Both models performed well although XGBoost predicted well with AUC of 0.80 where as linear learner AUC is 0.65
