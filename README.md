# Time series prediction of pm 2.5 levels
This notebook aims to predict the pollution levels over time. The models used are an ensemble of ML alternatives (Light GBM, Neural Net, K-neighbors, CatBoost...) and the Prophet model.
The Whole dataset is divided into three subsets. The first one is used to train the inidividual models, the second one is used to test their performances and to derive their best ensemble,
finally the third one is used to evaluate the performances of the ensemble.
