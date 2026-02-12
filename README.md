# ibm-de-spark
Replica of the ETL PySpark project for the course "Machine Learning and Date Engineering" of the IBM Data Engineering Certification

# dataset
https://www.kaggle.com/datasets/yasserh/titanic-dataset

# ibm-de-etl-python
Replica of the ETL PySpark project for the course "Machine Learning and Date Engineering" of the IBM Data Engineering Certification

## What it does
End-to-end **ETL pipeline with PySpark** + **Linear Regression** to predict Titanic passenger **fare** prices. 
- **Extract**: Load Titanic CSV dataset
- **Transform**: Basic Transform operations + feature engineering (StringIndexing, OneHotEncoding, Scaling)
- **Load**: Model training + evaluation (RMSE, MAE, R²)
- **Results**: R²=0.31, RMSE=57£, MAE=24£ (realistic for LinearRegression)

## Data source
[Titanic Dataset (CC0 Public Domain)](https://www.kaggle.com/datasets/yasserh/titanic-dataset) - 891 passengers

## Project structure
- `/src/etl_spark.ipynb` — main notebook.
- `data/` — Sample input data.
- `requirements.txt` — Python dependencies.
- `README.md` — Project documentation.

## Setup (venv)
```bashclear
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt

