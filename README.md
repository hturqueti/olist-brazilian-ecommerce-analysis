[![Python](https://img.shields.io/badge/python-3.12.3-blue?style=flat&logo=python&logoColor=ffdd54&color=blue)](https://www.python.org/downloads/release/python-3121/)
[![Static Badge](https://img.shields.io/badge/pyenv-2.4.0-blue?style=flat&logo=pyenv)](https://github.com/pyenv/pyenv)
[![Static Badge](https://img.shields.io/badge/Poetry-1.8.2-blue?style=flat&logo=poetry)](https://python-poetry.org/)
[![Static Badge](https://img.shields.io/badge/DVC-3.50.1-blue?style=flat&logo=dvc)](https://dvc.org/)
[![Kaggle](https://img.shields.io/badge/Kaggle-dataset-blue?logo=kaggle)](https://www.kaggle.com/olistbr/brazilian-ecommerce)

[![Static Badge](https://img.shields.io/badge/Ubuntu-24.04-5E2750?style=flat&logo=ubuntu&logoColor=FFFFFF&labelColor=E95420)](https://ubuntu.com/desktop/wsl)


# Olist Brazilian E-Commerce Analysis
<p align="center">
  <img src="files/olist_logo.svg" alt="Olist Logo"/>

This project is an analysis of the Olist Brazilian E-Commerce Dataset, which contains information about 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil.

## Requirements
The analysis was made using **Python 3.12.3** and the following libraries:
- duckdb        0.10.1
- keras         3.2.0
- numpy         1.26.4
- pandas        2.2.1
- pendulum      3.0.0
- plotly        5.20.0
- safetensors   0.4.2
- spacy         3.7.4

## Data
The original datasets can be found on [Kaggle](https://www.kaggle.com/olistbr/brazilian-ecommerce) and their data schema is shown below:
<p align="center">
  <img src="files/olist_erd.svg" alt="Olist Data Schema"/>

## Exploratory Data Analysis (EDA)
All analyzes are in the file "01-orders-eda.ipynb".

The topics covered were:
- volume of purchases and payments by state and purchase status
- average ticket per purchase in each region
- what are the regions of origin and destination of the purchased goods
- density map of registered sellers and customers
- number of products purchased from the main categories over time
- some customer metrics, such as:
  - recency
  - churn rate
  - frequency
  - total revenue
- sentiment analysis of comments texts written by customers