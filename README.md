# Cardiotocography classification
Classification performed on the Cardiotocography dataset

This work consists of a data science workflow and the exploration of its main phases for a task of binary classification.

First, in Chapter 2 there is an in-depth analysis of the Cardiotocography dataset. Thedataset consists of measurements of fetal heart rate (FHR) and uterine contraction (UC) features on cardiotocograms classified by expert obstetricians.

In Chapter 3 the data preprocessing pipeline is analyzed: outlier removal by means of anomaly detectors such as Local Outlier Factor; scaling of the features in order to make it possible to use techniques of dimensionality reduction such as Principal Component Analysis so as to deal with the curse of dimensionality; resampling techniques to deal with an unbalanced dataset such as undersampling or oversampling. Moreover, it follows a detailed examination of K-Fold cross validation useful to split the dataset in order to tune the model and reduce the bias introduced by the data.

Chapter 4 focuses on the existing and most common metrics to evaluate a classification model. Hence, a description of the confusion metrics precedes the explanation of accuracy, precision, recall, F1-score, ROC curve and Precision-Recall curve, along with the AUC
and AP scores.

Chapter 5 describes many classifiers and the rationale behind them. The classifiers considered
are: Decision Tree along with its Random Forest ensemble version, Support Vector Machine and K-Nearest Neighbors. Finally, we evaluate what is the best preprocessing pipeline for each classifier, comparing then the performance of all the used classifiers.
