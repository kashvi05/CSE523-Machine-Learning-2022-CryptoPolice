* This is a classic regression combined with time series problem to be solved using Machine Learning.

# Prerequisite (Installation required)
* Python
* pip

# Installation Guide

#### Download the dataset
* Download the dataset from the [link here](https://www.kaggle.com/c/g-research-crypto-forecasting/data)
* Extract the folder
* Rename the folder to Dataset and place it in the root directory of this repo.

#### Install Jupyter Notebook
```bash
pip install jupyter notebook
jupyter notebook
```

#### Clone the repo
```bash
git clone https://github.com/kashvi05/CryptoPolice.git
```

#### Run the notebooks
* First run Installation.ipnyb to ensure that you have the necessary packages required for this project to run.
* Then, run Preprocessing.ipnyb so as to handle null values and reduce the size of dataset by combining the values for one day.
* Then, run Exploratory Data Analysis.ipnyb to get insigts about the dataset.
* Then, run Feature Engineering.ipnyb which takes care of outliers, lag features and feature selection.
* After that, run Model Fitting.ipnyb which fits basic machine learning and time series models
* Finally, run Optimization.ipnyb which find the best set of hyperparameters with lowest error rate.