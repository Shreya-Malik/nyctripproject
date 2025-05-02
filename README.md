# NYC Taxi Fare Project

This project analyzes taxi trip data using NYC Trip Fare repository.It focuses on data cleaning, transformation, and insightful exploration through 17 structured tasks.

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

The notebook performs the following:

-> Data cleaning: handle nulls, invalid and possibly canceled trips
-> Aggregation: compute statistics by pickup/dropoff location and time intervals
-> Grouped analysis: identify high-revenue locations and intervals
-> Clustering of pickup times into 30-minute intervals
-> Pattern discovery: compare common vs. full trip routes
-> Chaining logic: detect trip sequences based on time and location continuity

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

## Final Analysis Summary

Data Cleanup
-> Memory-efficient loading with dtype
-> Removal of invalid trips (nulls, negatives, outliers)
-> Final cleaned dataset used consistently in all tasks

## Key Analytical Tasks
| Task Range | Description                                         |
|------------|-----------------------------------------------------|
| 1–5        | Filtering, missing values, duration calculation     |
| 6–9        | Time-based grouping and passenger/fare trends       |
| 10–12      | Peak interval detection and top-fare locations      |
| 13–16      | Fare comparison for common vs. full trips           |
| 17         | Chain detection using vectorized time/location logic |

## Deliverables
-> Jupyter Notebook (nyc_trip_analysis_cleaned.ipynb)
-> Clean and modular code with clear outputs
-> Final df_sorted containing all chained trips
-> Intermediate CSVs saved for inspection (invalid_duration, chained_trips_full, etc.)





