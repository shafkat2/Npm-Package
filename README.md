# Npm-Package-Lifeline

Problem Statement - To detect depricated packages in the NPM repository


Solution - Collect data from npm package repository
           Use the data to do a binary classification using machine learning the tags are Depri/Non- Depri

Approach -
-> The datast was collected by scraping the NPM package repository
-> The dataset was cleaned on the important columns which had any meaning of relation with the tag was selected
-> We did cluster analysis to detect the validity of the features whether the features could be separated or not
-> used SVM classifier to train the data
-> Prediction was close to 98%
