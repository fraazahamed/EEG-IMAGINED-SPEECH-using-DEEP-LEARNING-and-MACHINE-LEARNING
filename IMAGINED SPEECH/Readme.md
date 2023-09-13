EEG signals are collected and stored as datasets with help of appropriate headsets containing channels.
The datasets and the epochs used by me are included.
Preprocessing like epoching, resampliing, windowing and splitting of data as test data and train data.
Features are extracted in time domain and passed to different machine learning classifiers like k-nearest neighbour, SVM, Naive Bayes and Random Forest in machine learning approach.
Also LTSM, GRU, CNN, GIN methods are extracted in temporal features.

Accuracies obtained from the code processed by me in this repositary

Without windowing and time domain feature:

rf -0.11711711711711711
nb -0.0990990990990991
knn -0.08108108108108109
svc -0.09009009009009009

Windowing before splitting data in time domain feature:

rf -0.9905405405405405
nb -0.18153153153153154
knn -0.5495495495495496
svc -0.2072072072072072

Windowing after splittinga data in time domain feature:

rf -0.12207207207207207
nb -0.0918918918918919
knn -0.11891891891891893
svc -0.08468468468468468

Windowing after splitting data and cross validation in time domain feature:

rf -

Validation Accuracy: 1.0
Validation Accuracy: 0.9984984984984985
Validation Accuracy: 0.996996996996997
Validation Accuracy: 0.996996996996997
Validation Accuracy: 0.9984984984984985
Validation Accuracy: 1.0
Validation Accuracy: 0.993993993993994
Validation Accuracy: 1.0
Validation Accuracy: 0.996996996996997
Validation Accuracy: 1.0
Test Accuracy: 0.12207207207207207

nb -

Validation Accuracy: 0.1966966966966967
Validation Accuracy: 0.22522522522522523
Validation Accuracy: 0.2132132132132132
Validation Accuracy: 0.2087087087087087
Validation Accuracy: 0.19369369369369369
Validation Accuracy: 0.20270270270270271
Validation Accuracy: 0.2087087087087087
Validation Accuracy: 0.22522522522522523
Validation Accuracy: 0.17417417417417416
Validation Accuracy: 0.2057057057057057
Test Accuracy: 0.0918918918918919

knn -

Validation Accuracy: 0.521021021021021
Validation Accuracy: 0.5420420420420421
Validation Accuracy: 0.5420420420420421
Validation Accuracy: 0.515015015015015
Validation Accuracy: 0.5225225225225225
Validation Accuracy: 0.5330330330330331
Validation Accuracy: 0.5375375375375375
Validation Accuracy: 0.53003003003003
Validation Accuracy: 0.5420420420420421
Validation Accuracy: 0.527027027027027
Test Accuracy: 0.09594594594594595

svc -

Validation Accuracy: 0.21921921921921922
Validation Accuracy: 0.23573573573573572
Validation Accuracy: 0.25975975975975973
Validation Accuracy: 0.24324324324324326
Validation Accuracy: 0.23873873873873874
Validation Accuracy: 0.24174174174174173
Validation Accuracy: 0.23723723723723725
Validation Accuracy: 0.25675675675675674
Validation Accuracy: 0.23123123123123124
Validation Accuracy: 0.23873873873873874
Test Accuracy: 0.08468468468468468