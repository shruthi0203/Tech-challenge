Stock Price Outlier Detection
This program identifies potential outliers in stock price data, ensuring high-quality data for financial analysis. It processes CSV files of stock price data and detects anomalies based on statistical outliers.

Features:
Downloads and extracts stock price data from a provided ZIP file.
Selects 30 consecutive random data points from each file.
Calculates the mean and standard deviation for the selected data points.
Detects outliers that are beyond 2 standard deviations from the mean.
Outputs the identified outliers in a new CSV file.
Requirements:
Python 3.x
Libraries: os, random, csv, urllib, zipfile, statistics
Setup & Usage:
Clone the repository.
Ensure Python 3.x is installed.
Run python main.py to:
Download and extract the ZIP file.
Process CSV files and identify outliers.
The results will be saved as CSV files named with a _outliers suffix.

Example:
For each processed file, the output CSV will contain:

Stock-ID
Timestamp
Stock Price
Mean Price of the selected 30 points
Price Deviation
Percentage Deviation
