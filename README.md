# INSAID2022-DL-NLP-Classify-Whether-Real-or-Fake-News
INSAID 2022 Deep Learning NLP Term Project
# Project Description
## Introduction
- Your client for this project is a media company.
    - The company offers content to users via news, article, pamphlets etc.
    - They are always working hard to provide users with the best content as possible.
    - Their editing team are always unsure of the sanity of the content so every time when they are publishing new content they always have to track back to the source of the content.

## Current Scenario
- The current process of identifying legit content requires a lot of manually checking and going through the content again and again which is quite tiresome and tedious.
- Their tech department is utilizing the content which was previously classified as fake to build a dataset for developing a machine learning model to solve the problem of identifying legit and fake contents.
## Problem Statement
The current process suffers from the following problems:
- Their editing team have to go through each and every article line by line to check the legitimacy of the content
- This process is very time-consuming and labour-intensive

## Project Task
* Dataset contains text document with real and fake articles.
* Project task is to build a classification model using the dataset.
## Project Deliverables
- Deliverable: **Fake or Real News Prediction.**
- Machine Learning Task: **Text Classification**
- Target Variable: **Label**
## Evaluation Metric
* The model evaluation will be based on the Accuracy score.
# Data Description
* The dataset contains text data of different articles.
  There are 2 distinct labels in the data.
* This is what we have to predict for future text data.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 35918 rows and 6 columns.
* The column Label is the target variable.

## Test Set:
* The test set contains 8980 rows and 5 columns.
* The test set doesn’t contain the Label column.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **Id**   | Unique identifier          |
|02| **title** | The title of the article       |
|03| **Text**   | The text of the article                  |
|04| **subject** | The subject of the article        |
|05| **Date**   | The date at which the article was posted             |
|06| **Label** | Whether the article is true or fake             |
