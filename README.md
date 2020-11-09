# WeatherPrediction

Project name is a Data Mining project that allows users to predict whether the weather tomorrow is rainy or not based on input weather conditions.

The model was developed using [Weather Dataset From Kaggle](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package).

## Prerequisites

Before you begin, ensure you have met the following requirements:
* You have installed `Anaconda Navigator` and `Jupyter Notebook`.
* Python packages: `numpy`, `pandas`, `sklearn`, `functools`, `seaborn`, `pandas_profiling`, `itertools`.
* You have reviewed `weatherAUS` dataset file.
* You have basic understanding of Macine Learning models: `SVM`, `Decision Tree`, `kNN`, `Logistic Regression`, `Neural Network`.

## Installing

To install WeatherPrediction, follow git command:
```
git clone https://github.com/KhanhDNg/WeatherPrediction
```
## Using WeatherPrediction

### DataPreparation.ipynb
This notebook is created for data pre-processing:
* Data descriptions: stats, missing values, outliers
* Data cleaning: missing values, outliers
* Data experiements: hypothesis tests, z-score, feature correlation, visualizations
* Data transformation: dummy, normalization

### DataModelling.ipynb
This notebook is used to apply Machine Learning models on processed dataset:
* Feature selection: top 10 features
* Modelling reports: `Accuracy`, `F-score`, `Precision`, `Recall`.
* Machine Learning models: `SVM classifier`, `Decision Tree classifier`, `kNN classifier`, `Logistic Regression classifier`, `Neural Network classifier`.
* Experiments: Comparision between models
* Cohen's Kappa Score, Voting Classifier
