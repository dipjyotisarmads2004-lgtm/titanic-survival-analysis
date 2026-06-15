# Titanic Survival Analysis

## Overview

This project analyzes the Titanic dataset and develops machine learning models to predict passenger survival using demographic, socioeconomic, and travel-related features.

The project follows a structured end-to-end machine learning workflow including:

* data validation
* preprocessing and cleaning
* exploratory data analysis
* feature engineering
* model development
* evaluation and optimization

The primary objective is not only predictive modeling, but also the development of a reproducible and analytically rigorous machine learning workflow.

---

## Problem Statement

The objective of this project is to predict whether a passenger survived the Titanic disaster using features such as:

* passenger class
* age
* sex
* fare
* family relationships
* embarkation details

This is a supervised machine learning classification problem.

### Target Variable

`Survived`

* `0` → Did Not Survive
* `1` → Survived

---

## Dataset

### Dataset Source

Kaggle Titanic Machine Learning Competition

### Dataset Link

[Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

### Files Used

* `train.csv`
* `test.csv`

The dataset contains passenger demographic information, ticket details, travel class, fare information, and embarkation details.

---

## Project Structure

```text
titanic-survival-analysis/
│
├── data/
│   ├── raw/
│   │   ├── train.csv
│   │   └── test.csv
│   │
│   └── processed/
│       └── titanic_cleaned.csv
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   └── 02_data_wrangling_cleaning.ipynb
│
├── models/
├── outputs/
├── src/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Project Workflow

### Data Understanding

Completed tasks:

* dataset inspection
* feature analysis
* datatype validation
* structural assessment

---

### Data Wrangling & Cleaning

Completed tasks:

* missing value analysis
* missing data visualization
* duplicate inspection
* distribution analysis
* skewness assessment
* outlier investigation
* preprocessing and cleaning operations
* cleaned dataset export

Key preprocessing decisions:

* median imputation for `Age`
* mode imputation for `Embarked`
* exclusion of `Cabin`
* removal of low-utility identifier-based features

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Setup Instructions

### Clone Repository

```bash
git clone <repository-url>
```

### Navigate to Project Directory

```bash
cd titanic-survival-analysis
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Current Progress

Completed:

* project setup and environment configuration
* dataset organization
* dataset validation and inspection
* data wrangling and preprocessing workflow
* cleaned dataset generation

Upcoming:

* exploratory data analysis
* feature engineering
* model development
* model evaluation
* model optimization

---

## Future Improvements

Planned future improvements include:

* advanced feature engineering
* reusable preprocessing pipelines
* cross-validation workflows
* hyperparameter tuning
* model comparison and benchmarking
* modular training pipelines
* experiment tracking and reproducibility improvements

---

## Author

Dipjyoti Sarma
