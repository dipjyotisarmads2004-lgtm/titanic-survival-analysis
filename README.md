# Titanic Survival Analysis

## Overview

This project analyzes the Titanic dataset and develops machine learning models to predict passenger survival using demographic, socioeconomic, and travel-related features.

The primary objective of the project is not only to build predictive models, but also to develop a reproducible and analytically rigorous machine learning workflow.

The project follows a structured end-to-end workflow:

* data validation
* preprocessing and cleaning
* exploratory data analysis
* feature engineering
* model development
* evaluation and optimization

---

## Problem Statement

The objective of this project is to predict whether a passenger survived the Titanic disaster using information such as:

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

https://www.kaggle.com/competitions/titanic/data

### Files Used

* `train.csv`
* `test.csv`

The dataset contains passenger demographic information, ticket details, socioeconomic characteristics, fare information, and embarkation details.

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
│   ├── 02_data_wrangling_cleaning.ipynb
│   └── 03_exploratory_data_analysis.ipynb
│
├── outputs/
│   └── figures/
│
├── src/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Notebooks

| Notebook                           | Description                                                         | Status    |
| ---------------------------------- | ------------------------------------------------------------------- | --------- |
| 01_data_understanding.ipynb        | Dataset inspection and structural analysis                          | Completed |
| 02_data_wrangling_cleaning.ipynb   | Missing value analysis and preprocessing                            | Completed |
| 03_exploratory_data_analysis.ipynb | Distribution analysis, survival patterns, and feature relationships | Completed |
| 04_feature_engineering.ipynb       | Feature construction and transformation                             | Planned   |

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
* preprocessing operations
* cleaned dataset export

Key preprocessing decisions:

* median imputation for `Age`
* mode imputation for `Embarked`
* removal of `Cabin`
* removal of `PassengerId`
* removal of `Ticket`
* retention of investigated outliers

---

### Exploratory Data Analysis

Completed tasks:

* target variable analysis
* univariate analysis
* bivariate analysis
* feature relationship analysis
* correlation analysis
* multivariate analysis
* survival pattern investigation
* identification of feature engineering opportunities

Key findings:

* female passengers experienced significantly higher survival rates
* first-class passengers exhibited better survival outcomes
* fare and passenger class captured important socioeconomic information
* age effects appeared nonlinear
* family structure influenced survival patterns

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
git clone https://github.com/dipjyotisarmads2004-lgtm/titanic-survival-analysis.git
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

### Completed

* project setup and environment configuration
* dataset organization
* data understanding
* data wrangling and preprocessing
* cleaned dataset generation
* exploratory data analysis

### Upcoming

* feature engineering
* model development
* model evaluation
* model optimization

---

## Future Improvements

Planned future improvements include:

* feature engineering pipelines
* model comparison and benchmarking
* hyperparameter optimization
* cross-validation workflows
* reusable training pipelines
* experiment reproducibility improvements

---

## Author

**Dipjyoti Sarma**
