# Udacity_Blog_Project

Answers to Three Questions that will Keep You Optimistic in Your Journey of Becoming a Data Scientist.

![Intro Pic](blog_assets/title.png)

## Table of Contents
1. [Description](#project_overview)
2. [Getting Started](#getting_started)
	1. [Dependencies](#dependencies)
	2. [Installing](#installing)
	3. [Results](#executing)
3. [Authors](#authors)
4. [License](#license)
5. [Acknowledgement](#acknowledgement)
6. [Publication](#published)

<a name="project_overview"></a>
## Project Overview

The Sparkify churn prediction project is my final final capstone project for the Udacity Data Scientist Nanodegree. The main objective of this project is to manipulate large and realistic datasets with Spark to select and engineer relevant features for predicting churn rates for a music app, Sparkify. Millions of users stream their favorite songs everyday and this generates large datasets; Here, we choose to use Spark MLlib to build "simple" machine learning models with large datasets, far beyond what could be done with non-distributed technologies like scikit-learn.


Objective

Simply, demonstrate how to develop simple ML models with good feature selection/engineering to predict churn rates based on user activities in the Sparkify app. 
Three steps:

1) Exploratory Data Analysis (EDA): Clean, label data, and explore the data
2) Feature Engineering: Create features to improve model performance
3) Modeling: Transform feature engineered data, train-test split, and build machine learning models and compare.

<a name="getting_started"></a>
## Getting Started

<a name="dependencies"></a>
### Dependencies
* Python 3, NumPy, Pandas, PySpark, Matplotlib, Seaborn

<a name="installing"></a>
### Installing
Clone this GIT repository:
```
git clone https://github.com/geovani-montoya/Churn_Prediction_of_Sparkify
```
<a name="executing"></a>
### Results:
It turns out that we only needed 7 features to acquire a decent model that will predict churn rates; the logistic regression model was 91% accurate with an F1-Score of 0.87 and the random forest model had an accuracy score of 90% with an F1-score of 0.89. Not bad! Considering there was virtually no tuning to be done and the training was relatively fast (compared to other sophisticated models).

![results](sparkify_assets/page_distribution.png)

<a name="authors"></a>
## Authors

[Geovani Montoya](https://github.com/geovani-montoya)

<a name="license"></a>
## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<a name="acknowledgement"></a>
## Acknowledgements

* [Udacity](https://www.udacity.com/) extensive curriculum in Data Science Nanodegree Program

<a name="published"></a>
## Publication

https://medium.com/@geovani.m12/answers-to-three-questions-that-will-keep-you-optimistic-in-your-journey-of-becoming-a-data-824c6666d688?source=friends_link&sk=a5287af5d6cf158d0e3055214af646f0
