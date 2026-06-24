# Titanic Survival Analysis

## Overview

Titanic Survival Analysis is an end-to-end machine learning project that investigates the factors influencing passenger survival aboard the RMS Titanic and develops predictive models using demographic, socioeconomic, and travel-related information.

The project follows a structured data science workflow covering data preparation, exploratory analysis, feature engineering, and predictive modeling.

---

## Problem Statement

The objective is to predict whether a passenger survived the Titanic disaster using passenger characteristics such as:

* Passenger Class
* Age
* Sex
* Fare
* Family Relationships
* Embarkation Port

**Target Variable**

| Value | Meaning         |
| ----- | --------------- |
| 0     | Did Not Survive |
| 1     | Survived        |

---

## Dataset

**Source:** Kaggle Titanic Machine Learning Competition

Dataset: https://www.kaggle.com/competitions/titanic/data

The dataset contains passenger-level demographic, socioeconomic, and travel information used for survival prediction.

---

## Project Workflow

### Data Understanding

* Dataset inspection
* Feature assessment
* Data type validation
* Structural analysis

### Data Wrangling & Cleaning

Key preprocessing operations:

* Median imputation for `Age`
* Mode imputation for `Embarked`
* Removal of `Cabin`
* Removal of `PassengerId`
* Removal of `Ticket`

### Exploratory Data Analysis

Key findings:

* Survival was strongly influenced by passenger sex.
* Passenger class exhibited significant predictive power.
* Fare captured important socioeconomic information.
* Age effects appeared nonlinear.
* Family structure influenced survival outcomes.

### Feature Engineering

Engineered features:

* `FamilySize`
* `IsAlone`
* `Title`
* `LogFare`
* `AgeGroup`

Additional processing:

* Feature validation
* Categorical encoding
* Modeling dataset generation

### Model Development

* Planned

---

## Repository Structure

```text
titanic-survival-analysis/
│
├── data/
│   ├── raw/
│   ├── interim/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_wrangling_cleaning.ipynb
│   ├── 03_exploratory_data_analysis.ipynb
│   ├── 04_feature_engineering.ipynb
│   └── 05_model_development.ipynb
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

## Project Status

| Stage                     | Status      |
| ------------------------- | ----------- |
| Data Understanding        | Completed   |
| Data Wrangling & Cleaning | Completed   |
| Exploratory Data Analysis | Completed   |
| Feature Engineering       | Completed   |
| Model Development         | In Progress |
| Model Evaluation          | Pending     |

---

## Technologies

* Python
* Pandas
* NumPy
* SciPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Setup

```bash
git clone https://github.com/dipjyotisarma-dev/titanic-survival-analysis.git

cd titanic-survival-analysis

pip install -r requirements.txt

jupyter notebook
```

---

## Author

**Dipjyoti Sarma**
