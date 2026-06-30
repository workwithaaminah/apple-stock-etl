# Apple Stock ETL Pipeline

## Overview

This project is a beginner data engineering ETL pipeline built with Python and pandas.

The pipeline loads Apple stock market data from a CSV file, performs validation checks to ensure data quality, creates derived metrics, and explores the data using common data engineering techniques.

This project was built as part of my journey into data engineering.

## Dataset

The project uses historical Apple stock price data containing:

* Date
* Open
* High
* Low
* Close
* Volume

## Features

### Validation

* Check for missing values
* Check for duplicate rows

### Transformations

* Daily Range
* Price Change
* Daily Return Percentage

### Analysis

* Summary statistics
* Largest daily gains
* Largest daily losses
* Filtering and sorting using pandas
* Selecting relevant columns for reporting

## Technologies

* Python
* pandas
* Jupyter Notebook

## Skills Demonstrated

* ETL pipelines
* Data validation
* Data transformation
* Derived columns
* Boolean masking
* DataFrame filtering
* Sorting and analysing datasets

## Future Improvements

* Automate the pipeline
* Create visualisations
* Generate summary reports
* Connect to live financial data APIs
* Schedule automated pipeline runs
