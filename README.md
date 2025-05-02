# NYC Taxi Fare Project

This project analyzes taxi trip data using NYC Trip Fare repository.

## Folder Structure

```
nyc-taxi-project/
├── data/                  # Contains the raw dataset 
├── notebooks/             # Contains the Jupyter notebook
│   └── nyc_taxi_analysis.ipynb
├── README.md              # Project overview
├── requirements.txt       # Python dependencies
└── .git/                  # Git version control 
```

## Objectives

The goal is to perform a series of data wrangling and analysis tasks on the NYC Trip Fare, including:
- Filtering invalid trips
- Aggregating fare data
- Clustering pickup intervals
- Building chains of trips
- Generating insights from fare patterns

## Getting Started

To run this project:

1. Create a virtual environment:

```bash
python -m venv nycenv
source nycenv/bin/activate     
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start JupyterLab:

```bash
jupyter lab
```

## Dataset

Download the dataset from Kaggle:  
https://www.kaggle.com/datasets/diishasiing/revenue-for-cab-drivers

Unzip it and place `revenue.csv` in the `data/` folder.
