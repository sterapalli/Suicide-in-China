Arrests Data Analysis

This repository contains Python code for analyzing arrests data using pandas and seaborn libraries. The dataset used for analysis is Arrests.csv.

Dataset Information

The dataset contains information about arrests, including attributes such as released status, race, year, age, sex, employment status, citizenship, and number of checks.

Data Cleaning and Preprocessing

Removed the Unnamed: 0 column.
Replaced categorical variables with numerical equivalents:
'released': 'Yes' with 1, 'No' with 0
'colour': 'White' with 1, 'Black' with 0
'sex': 'Male' with 1, 'Female' with 0
'employed': 'Yes' with 1, 'No' with 0
'citizen': 'Yes' with 1, 'No' with 0

Data Analysis

Analyzed the distribution of arrests over the years using histograms.
Plotted distributions of different attributes such as race, sex, employment status, citizenship, and number of checks using seaborn's displot.
Visualized the distribution of arrests over the years using seaborn's boxplot and barplot.
Insights

In 2000, there was a significant increase in the number of arrests compared to other years, with a lower release rate.
1997 and 1999 had similar arrest rates, but 1997 had a slightly higher release rate than 1999.
Usage

To run the code:

Install Python (if not already installed).
Install the required libraries using pip:
