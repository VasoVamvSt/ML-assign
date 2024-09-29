##MSc Business Analytics -  	Machine Learning and Content Analytics

This repository contains the materials and code for the project Sentiment Analysis On Social Media Comments conducted by team Delta as part of the machine learning course. Below is a detailed explanation of the structure and contents of the repository.

Repository Structure
/dataset/
This folder contains the datasets used for training and testing our models. The data has been split into indexed and preprocessed versions for different stages of the pipeline.

/index/

df_test_indexed.csv: The test dataset with added indexes.
df_training_indexed.csv: The training dataset with added indexes.
/preprocessed/

df_test_preprocessed.csv: The test dataset after preprocessing.
df_training_preprocessed.csv: The training dataset after preprocessing.
test.csv: The raw test dataset.
train.csv: The raw training dataset.
/notebooks/
This folder contains Jupyter notebooks used during the different phases of the project:

indexing.ipynb: This notebook includes the code for indexing the datasets.
preprocessing.ipynb: Contains code for preprocessing the datasets (e.g., cleaning, tokenization, etc.).
training_with_tuning.ipynb: This notebook covers the model training process and hyperparameter tuning.
readme.md
This file provides an overview of the repository and the project structure.

Report
The full report for the project is included in this repository as a PDF document. The report details the following:

Introduction and problem statement
Data preprocessing steps
Model selection and training process
Hyperparameter tuning
Results and evaluation metrics
Conclusion and future work
Presentation
A presentation summarizing the project's key points and findings is also included in PDF format. It covers:

The project overview
The machine learning approach taken
Key results and insights
Final conclusions
