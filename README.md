# Machine Learning Final Project: BBC Document full text Classification

## Project Description:

### Introduction: Question Formulation and Data Acquisition

This repository contains a dataset of BBC published documents, a README.md file, and a Python Notebook containing exploratoy data analysis, model selection, model prediction, and model interpretation. This repository is where I will be testing various models on the BBC data, in an attempt to discover which machine learning model works best for large text dataset classification. This dataset is legal to use, and can be found through Kaggle [here.](https://www.kaggle.com/datasets/alfathterry/bbc-full-text-document-classification/data)

This repository aims to explore the effectiveness of Google's pretrained language vectorization model when compared to regular data vectorization. First, I will explore the data, highlighting any anomalies or noteworthy features. Following, the data will be ran through a regular word vectorization model called Word2Vec, a similar model to TP-IDF. The transformed data will then be split and trained on two machine learning models - a linear model and a random forest. The process will then repeat but with the Google News vectorization model instead of the Word2Vec model. Finally, the results of each vectorization model will be compared to help better understand the strengths and weaknesses of each model.

