# Data Science Article Classifier

This project is designed to classify data science articles into five classes: Big Data (BD), Machine Learning (ML), Artificial Intelligence (AI), Data Analysis (DA), and Data Visualization (DV).

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
    - [Data Scraping](#1-data-scraping)
    - [Setting Up Environment](#2-setting-up-environment)
    - [Running the Scraping Script](#3-running-the-scraping-script)
    - [Data Preprocessing](#4-data-preprocessing)
    - [Training the Model](#5-training-the-model)
    - [Evaluating the Model](#6-evaluating-the-model)
    - [Interpretation and Improvements](#7-interpretation-and-improvements)
- [Note](#note)

## Introduction

The project leverages both traditional machine learning (Logistic Regression and Naive Bayes) and deep learning (RNN) models to classify data science articles. The dataset consists of 2500 articles scraped from DataScienceCentral.com, with 500 articles for each of the five classes.

**Note:** Manually handle pop-ups during the scraping process as described in the note to ensure accurate data collection.

## Usage

### 1. Data Scraping

The data was scraped from DataScienceCentral.com. If you wish to reproduce the dataset, you can manually scrape articles for each class (BD, ML, AI, DA, DV) or use the provided dataset.

### 2. Setting Up Environment

Install the required dependencies:

```bash
pip install -r requirements.txt
```

### 3. Running the Scraping Script

Execute the Jupyter notebook (scraping_script.ipynb). Make sure to click on pop-ups manually as instructed in the note.

```bash
scrape.ipynb
```

### 4. Data Preprocessing

If necessary, preprocess the scraped data to prepare it for training. This may include lowering the text cases, handling missing values or duplicates.

### 5. Training the Model

Use the provided Jupyter notebook to train your machine learning or deep learning model.

```bash
ML_&_DL.ipynb
```

### 6. Evaluating the Model

Evaluate the trained model on the test set and analyze the results from classification report.

### 7. Interpretation and Improvements

Interpret the results, explore misclassifications, and consider making improvements to the model or data collection process.
