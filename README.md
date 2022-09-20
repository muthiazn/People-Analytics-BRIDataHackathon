# People-Analytics-BRIDataHackathon
This is Python code for BRI Data Hackathon 2021 Submission on People Analytics. This code use Pandas, Numpy, Sklearn, and JcopML package.
The objective of this competition is to predict employees performance for the next one year, whether they will give best performance or not from categorical and numeric data.
What I did to increase the ROC-AUC Mean Score is binning employees Age and creating new feature (isAlone) based on employees Number of Dependencies.
For training, I used bayesian search cross validation to find best hyperparameter and using XGBoost Classifier algorithm for training the model.
The dataset can be found on https://www.kaggle.com/competitions/bri-data-hackathon-pa/data
