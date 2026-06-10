# Dataset Explorer Tool

## Overview

The Dataset Explorer Tool is a Python-based data analysis utility designed to automatically inspect and summarize CSV datasets. It helps users quickly understand the structure, quality, and statistical properties of a dataset without manually writing exploratory analysis code.

This project was developed as part of a Data Analytics learning program and demonstrates the use of Python and Pandas for data exploration.

---

## Features

### Dataset Loading
- Loads CSV files using Pandas
- Handles file loading errors gracefully

### Data Inspection
- Displays dataset shape (rows and columns)
- Lists column names and data types
- Shows the first five rows of the dataset

### Missing Value Analysis
- Identifies missing values in each column
- Calculates the percentage of missing data

### Statistical Summary
- Computes descriptive statistics for numeric columns
- Displays:
  - Mean
  - Median
  - Standard Deviation
  - Minimum Value
  - Maximum Value

### Outlier Detection
- Detects outliers using the Interquartile Range (IQR) method
- Reports the number of outliers in each numeric column

---

## Technologies Used

- Python 3.x
- Pandas Library

---

## Project Structure

```text
Task-2/
│
├── titanic.csv
├── explorer.py
└── README.md
```

---

## Dataset

This project uses the Titanic dataset, which contains passenger information such as:

- Passenger ID
- Survival Status
- Passenger Class
- Name
- Gender
- Age
- Fare
- Cabin
- Embarkation Port

The dataset is commonly used for introductory data analysis and machine learning projects.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/sangeethavijayan01-spec/dataset-explorer.git
```

Navigate to the project folder:

```bash
cd dataset-explorer
```

Install required packages:

```bash
pip install pandas
```

---

## How to Run

Execute the script using:

```bash
python explorer.py
```

---

## Sample Output

```text
File loaded: titanic.csv

Shape: (891, 12)

Missing Values:
Age         177
Cabin       687
Embarked      2

Summary Statistics:
Mean, Median, Standard Deviation,
Minimum and Maximum values

Outlier Detection:
Fare: 116 outlier(s)
Age: 11 outlier(s)
```

---

## Learning Outcomes

Through this project, the following concepts were practiced:

- Reading CSV files with Pandas
- Exploratory Data Analysis (EDA)
- Data Cleaning Concepts
- Missing Value Identification
- Descriptive Statistics
- Outlier Detection using IQR
- Git and GitHub Version Control

---

## Future Improvements

Possible enhancements include:

- Support for Excel files (.xlsx)
- Data visualization using Matplotlib
- Automatic report generation
- Interactive dashboard integration
- Export analysis results to a text file

---

## Author

**Sangeetha V**

GitHub: https://github.com/sangeethavijayan01-spec

---

## License

This project is created for educational and learning purposes.
