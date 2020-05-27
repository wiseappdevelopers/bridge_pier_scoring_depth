# 🌉 Predicting the Bridge Pier Scouring Depth Using Machine Learning

This jupyter notebook shows an example dataset preparation and machine learning algorithms used for prediction of the bridge pier scouring depth from the public dataset of a survey in USA.

## 1. Problem Definition

> It is tried to depict the steps for a practical data science application to predict the bridge pier scouring depth based on the different inputs such as 'Measurement', 'Site', 'State', 'Date', 'Time', 'Pier',
       'Upstream/Downstream', 'Pier type', 'Pier shape', 'Pier width (m)', 'Pier length (m)', 'Skew (deg)', 'Velocity (m/s)', 'Depth (m)', 'Debris Effect', 'Bed Material', 'd16 (mm)', 'd50(mm)', 'd84 (mm)', 'd95 (mm)', 'Gradation', 'Scour depth (m)', 'Accuracy (m)'.

## 2. Data

The dataset is downloaded from the webpage of "Geospatial Data for Bridge Scour Countermeasure Assessments at Select Bridges in the United States, 2014".
https://catalog.data.gov/dataset/geospatial-data-for-bridge-scour-countermeasure-assessments-at-select-bridges-in-the-united-sta

The data for this modeling purpose is split into three parts:

- Train.csv - is the training set, which contains data through the end of 2014.
- Valid.csv - is the validation set.
- Test.csv - is the test set, which is reserved for evaluation of the proposed models.

## 3. Evaluation

Different metrics of sklearn package of Python are used to get the accuracy and predictability of the proposed models.

**Note:** The goal for most regression evaluation metrics is to minimize the error and enhance its ability to be predictable.
## 4. Features

The data.gov site at the following address has explanation about the dataset.
https://catalog.data.gov/dataset/geospatial-data-for-bridge-scour-countermeasure-assessments-at-select-bridges-in-the-united-sta
