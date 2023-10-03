# Time Series Data Visualization and NBA Player Performance Analysis

This repository contains a Python script that demonstrates two distinct data analysis tasks: visualizing time series data and performing an NBA player performance analysis.

## Time Series Data Visualization

The first part of the script involves generating and visualizing a sample time series dataset. This dataset consists of randomly generated daily values cumulatively summed over time. Here's a brief overview of this section:

- A time series dataset is generated using pandas' date range function, starting from January 1, 2022, with daily frequency.
- The generated dataset is organized into a DataFrame.
- The 'Date' column is set as the index for the DataFrame.
- The time series data is plotted using matplotlib to visualize the data.

## NBA Player Performance Analysis

The second part of the script focuses on performing a basic analysis of NBA player performance. Jimmy Butler's performance data is used for this analysis. Here's an outline of this section:

- Jimmy Butler's performance dataset is loaded from a CSV file ('JimmyButler.csv'). You can replace this file with data for any other NBA player.
- The script calculates the mean performance metrics for Jimmy Butler over the historical data. Metrics calculated include Assists (AST), Total Rebounds (TRB), Three-Pointers Made (3P), Two-Pointers Made (2P), Field Goal Percentage (FG%), and Points Per Game (PTS).
- The script then makes simplified predictions for the upcoming season for AST, TRB, 3P, 2P, FG%, and PTS based on the historical mean values. These predictions are generated using random noise for demonstration purposes.
- Finally, the predicted performance metrics for the upcoming season are printed to the console.

## Usage

You can use this script as a starting point for your own time series data visualization or NBA player performance analysis tasks. Feel free to replace the time series data with your own data or modify the player performance analysis section to work with different player datasets.

Make sure to have the required libraries installed, including pandas and matplotlib, before running the script.

```shell
pip install pandas matplotlib
