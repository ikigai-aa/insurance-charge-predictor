# Insurance Charge Predictor

## Table of contents
* [About project](#about-project)
* [Technologies](#technologies)
* [Software and account requirement](#software-and-account-requirement)
* [Setup](#setup)
* [Project Architecture](#project-architecture)
* [Project Pipeline](#project-pipeline)
<!-- * [License](#license) -->

<br>

## About project
he purposes of this exercise to look into different features to observe their relationship, and plot a multiple linear regression based on several features of individual such as age, physical/family condition and location against their existing medical expense to be used for predicting future medical expenses of individuals that help medical insurance to make decision on charging the premium.
<br>

## Technologies
This project is created with below resources:
* Python: 3.7
* Machine Learning
* Jupyter Notebook
* Docker
* Git
* CI/CD Pipeline
* Azure

<br>

## Software and account Requirement
1. [Github Account](https://github.com/)
2. [Azure Account](https://portal.azure.com/)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT CLI](https://git-scm.com/downloads)

<br>

## Setup 

To install requirement file
```
pip install -r requirements.txt
```

* Add files to git  `git add .` or  `git add <file_name>`    
* To check the git status  `git status`    
* To check all version maintained by git  `git log`    
* To create version/commit all changes by git  `git commit -m "message"`    
* To send version/changes to github  `git push -u origin main`    

<br>

## Project Pipeline
1. [Data Ingestion](#1-data-ingestion)
2. [Data Validation](#2-data-validation)
3. [Data Transformation](#3-data-transformation)
4. [Model Training](#4-model-training)
5. [Model Evaluation](#5-model-evaluation)
6. [Model Deployement](#6-model-deployement)

<br>

### 1. Data Ingestion: 
* Data ingestion is the process in which unstructured data is extracted from one or multiple sources and then prepared for training machine learning models.

<br>

### 2. Data Validation:
* Data validation is an integral part of ML pipeline. It is checking the quality of source data before training a new mode
* It focuses on checking that the statistics of the new data are as expected (e.g. feature distribution, number of categories, etc). 

<br>

### 3. Data Transformation 
* Data transformation is the process of converting raw data into a format or structure that would be more suitable for model building.
* It is an imperative step in feature engineering that facilitates discovering insights.

<br>

### 4. Model Training
* Model training in machine learning is the process in which a machine learning (ML) algorithm is fed with sufficient training data to learn from.

<br>

### 5. Model Evaluation
* Model evaluation is the process of using different evaluation metrics to understand a machine learning model’s performance, as well as its strengths and weaknesses.
* Model evaluation is important to assess the efficacy of a model during initial research phases, and it also plays a role in model monitoring.

<br>

### 6. Model Deployement
* Deployment is the method by which we integrate a machine learning model into production environment to make practical business decisions based on data. 

<br>
