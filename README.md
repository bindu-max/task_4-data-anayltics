# Data Analysis and Visualization using Python

## Project Overview

This project demonstrates how to perform basic data analysis, statistical testing, and data visualization using Python. The dataset is stored in an Excel file named **ApexPlanet_DataAnalytics_Dataset.xlsx**.

The project uses the **Pandas** library for data handling, **Matplotlib** for visualization, and **SciPy** for statistical analysis.

## Features

* Load data from an Excel file
* Display the first five rows of the dataset
* Show dataset information and data types
* Generate summary statistics
* Identify missing values
* Calculate the correlation matrix for numeric columns
* Perform an Independent T-Test (when applicable)
* Create different types of charts:

  * Bar Chart
  * Pie Chart
  * Line Chart
  * Histogram
  * Box Plot

## Technologies Used

* Python 3.x
* Pandas
* Matplotlib
* SciPy
* OpenPyXL (for reading Excel files)

## Required Libraries

Install the required libraries using pip:

```bash
pip install pandas matplotlib scipy openpyxl
```

## Dataset

File Name:

```
ApexPlanet_DataAnalytics_Dataset.xlsx
```

The dataset should be placed in the same folder as the Python script.

## Code Workflow

### 1. Data Loading

* Imports the required libraries.
* Reads the Excel dataset into a Pandas DataFrame.

### 2. Data Exploration

* Displays the first five records.
* Shows dataset information.
* Generates summary statistics.
* Checks for missing values.

### 3. Correlation Analysis

* Computes the correlation matrix for all numeric columns.
* Helps identify relationships between numerical variables.

### 4. Statistical Analysis

* Performs an Independent T-Test between two groups (if the specified columns exist).
* Displays:

  * T-Statistic
  * P-Value
* Determines whether to reject or fail to reject the null hypothesis based on a significance level of 0.05.

### 5. Data Visualization

The program creates the following charts:

* **Bar Chart** – Total Sales by Category
* **Pie Chart** – Sales Distribution by Category
* **Line Chart** – Total Sales Trend
* **Histogram** – Distribution of Total Sales
* **Box Plot** – Detects spread and outliers in Total Sales

## Expected Output

The program displays:

* Dataset preview
* Dataset information
* Summary statistics
* Missing value report
* Correlation matrix
* T-Test results (if applicable)
* Five different visualizations

## Project Structure

```
Project Folder/
│
├── ApexPlanet_DataAnalytics_Dataset.xlsx
├── data_analysis.py
└── README.md
```

## Conclusion

This project provides a simple introduction to data analysis using Python. It demonstrates how to explore a dataset, perform basic statistical analysis, and visualize data using commonly used Python libraries. The project serves as a foundation for more advanced data analytics and machine learning applications.
# task_4-data-anayltics
