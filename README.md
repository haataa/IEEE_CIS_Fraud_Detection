#### Table of Contents

1. [Installation](#Installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

# Installation<a name="Installation"></a>
libraries needed by this project are provided by the Anaconda distribution of Python. The code should run with no 
issues using Python versions 3.*.


# Project Motivation<a name="motivation"></a>
Build machine learning models to improve the efficacy of fraudulent transaction alerts. The data comes from Vesta's real-world e-commerce transactions and contains a wide range of features from device type to product features.

In this project, I build three tree models: lightgbm,xgboost and catboost.

I tried several feature selection method: forward search, backward search, permutation importance and so on.

I used fold cross validation as the validation strategy.

Model results are blended as the final result.


# File Descriptions<a name="files"></a>
Data file can be found at [Kaggle](https://www.kaggle.com/c/ieee-fraud-detection/data)

EDA notebook contain all steps of data EDA and background knowledge of fraud detection.

Features_Engineer notebook contain all engineered features.

feature_selection notebook contain all steps of feature selection method.

model_lgb notebook contain works related to build lightgbm models.

model_xgb notebook contain works related to build xgb models.

model_cat notebook contain works related to build catboost models.

Baseline notebook contain all works of baseline model.

model_blend contain workds related to blend model results.

model_easyensemble contain works that use easyensemble idea to train lgb models.

# Result<a name="results"></a>
Best result achieve LB AUC 0.952039 and PB AUC 0.927302.

# Licensing, Authors, Acknowledgements<a name="licensing"></a>
Data Source can be acquired from [Kaggle](https://www.kaggle.com/c/home-credit-default-risk/data)