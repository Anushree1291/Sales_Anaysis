Sales Analysis
This repository contains Python code for performing sales analysis on a dataset.

Overview
The provided Python script performs various operations on sales data to derive insights. Here's a breakdown of what each section of the script does:

Importing Necessary Libraries
Imports required libraries like os and pandas.

Merging Data
Merges data from each month into one CSV file and reads the updated dataframe using Pandas.

Cleaning Data
Drops rows with NaN values.
Removes text in the 'Order Date' column.
Converts columns to the correct data types.
Data Augmentation
Adds a 'Month' column derived from the 'Order Date'.
Extracts city information from the 'Purchase Address' to create a 'City' column.
Data Exploration
Analyzes sales data to determine:
Best month for sales and the corresponding revenue.
Cities that sold the most products and their sales figures.
Optimal times for displaying advertisements based on order times.
Products frequently sold together and their occurrences.
Most sold products and their quantities.
Usage
To use this script:

Ensure you have Python installed.
Clone the repository.
Run the Python script in your preferred environment.
Contributing
Contributions to enhance this sales analysis script are welcome! Feel free to submit pull requests or report issues.
