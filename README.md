# Dataset Explorer Tool

## Description
This project is a Python-based Dataset Explorer Tool that automatically analyzes CSV datasets. It loads a dataset, inspects its structure, checks for missing values, generates summary statistics, and detects outliers using the IQR (Interquartile Range) method.

## Features
- Load CSV datasets using Pandas
- Display dataset shape and column data types
- Show the first 5 rows of the dataset
- Identify missing values and their percentages
- Generate summary statistics for numeric columns
- Detect outliers using the IQR method

## Requirements
- Python 3.x
- Pandas

## Installation

Install Pandas using:

```bash
pip install pandas
```

## Dataset Used
Titanic Dataset (`titanic.csv`)

## How to Run

Open a terminal in the project folder and run:

```bash
python explorer.py
```

## Sample Output

```text
File loaded: titanic.csv

Shape: (891, 12)

Columns & Data Types:
PassengerId      int64
Survived         int64
Pclass           int64
...

Missing Values:
          Count  Percent (%)
Age         177       19.87
Cabin       687       77.10
Embarked      2        0.22

Outlier Detection (IQR Method):
PassengerId: 0 outlier(s)
Age: 11 outlier(s)
Fare: 116 outlier(s)
...
```

## Project Structure

```text
Task-2/
│
├── titanic.csv
├── explorer.py
└── README.md
```

## Author
Sangeetha V