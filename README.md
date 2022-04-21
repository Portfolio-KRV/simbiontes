# Simbiontes
Developed in the "course" course by: Diego Quezada and Kevin Reyes.
## Objectives
- Predict diseases given a set of data associated with the human microbiome.
- Compare performance of machine learning classifiers.
- Infer the importance of microbiomic profiles to detect different diseases.
- Identify biases present in the data through exploratory data analysis.

## Description
Predictive model to predict diseases based on data from a patient's microbiota, using machine learning methods in conjunction with data exploration and pre-processing tools.

## Conclusions
- Predictive categorical characteristics where one or more of its classes are present exclusively in a subset of the classes to be predicted could introduce biases to the predictive model.
- Applying dimensionality reduction in data sets where the sample size is limited and the dimensionality of the feature space could improve the generalizability of the model.
- For each disease there is a species of microorganism of great importance to predict the disease, accompanied by a set of specific strains.
- In small data sets, you should avoid deleting complete records, instead you should find the appropriate way to replace these values ​​and thus have a greater amount of data available.


## Technology stack
- Numpy.
- Pandas.
- Matplotlib.
- Plotly.
- Scikit-learn.
- XGBoost.