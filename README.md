# Stroke Prediction

This project uses a dataset from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset) to predict whether a person is likely to have a stroke or not. You can execute the notebook files in the ``notebooks`` folder to see the data cleaning and model building process. You can also view the Power BI file in the ``visualisation`` folder to see the visualizations that were created using the raw data.

## Table of Contents

- [Content](#content)
- [Usage](#usage)

## Content

In the notebook files, you will find the following:

In ``data_cleaning.ipynb``, you will find the following:

- Data Exploration
- Data Cleaning
- Data Visualization

In ``stroke_prediction.ipynb``, you will find the following:

- Data Preprocessing
- Model Building
- Model Evaluation
- Saving of Model

In the ``data`` folder, you will find the following:

- stroke-data-cleaned.csv
- stroke-data-raw.csv

In the ``models`` folder, you will find the following:

- gbm_model.pkl

In the ``notebooks`` folder, you will find the following:

- data_cleaning.html
- stroke_prediction.html

In the ``visualisation`` folder, you will find the following:

- stroke-visuals.pbix (Power BI file)

## Usage

To run this project, you will need to install the packages that are provided inside the pipfile. You will also need to activate the pipfile after installing. You can do this by running the following command:

```bash
pipenv install
pipenv shell
```

There are also html notebooks that can be viewed in the browser. These notebooks are located in the notebooks folder.
