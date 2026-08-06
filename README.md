# Predicting Hotel Success Using Online Reviews

This repository contains the implementation of my MSc Data Analytics thesis at the University of Galway.

## Project Overview

This project predicts **hotel success** using Booking.com customer reviews by combining Natural Language Processing (NLP), Machine Learning, and Deep Learning techniques.The framework includes an inconsistency review filter to improve data quality, hotel-level prediction through review aggregation, and SHAP explainability to interpret model predictions.

## Models

* Logistic Regression
* Random Forest
* XGBoost
* CNN
* BiLSTM

## Features

* Review text preprocessing
* Inconsistent review detection
* Hotel-level prediction
* SHAP explainability
* Performance evaluation using Accuracy, Precision, Recall, F1-score, ROC-AUC, and AUPRC

## Files

* `hotel_prediction_kaynat_25246046.ipynb` - Complete implementation of the proposed framework.

## Requirements

Install the required packages using:

```bash
pip install -r requirements.txt
```

## Dataset

This project uses the Booking.com Hotel Reviews dataset.

The dataset is not included in this repository because of its large file size.

It can be downloaded from:

https://www.kaggle.com/datasets/jiashenliu/515k-hotel-reviews-data-in-europe

After downloading the dataset, update the dataset path in the notebook before running the code.

## Author

**Kaynat Ahmed**
MSc Data Analytics
University of Galway

