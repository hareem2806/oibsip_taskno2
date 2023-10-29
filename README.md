# oibsip_taskno2

Unemployment Data Analysis

This repository contains a Python script for analyzing unemployment data from a CSV file using the Pandas, NumPy, Matplotlib, and Seaborn libraries. The script explores the dataset, checks for inconsistent data, and conducts exploratory data analysis (EDA) to gain insights into the unemployment rates, employed people, and labor participation rates. 


Exploring the Dataset:
The script begins by reading the CSV file and exploring the dataset using Pandas. It displays the first and last rows, shape, columns, data types, and basic statistics of the dataset.

Checking for Inconsistent Data:
The script checks for various types of inconsistent data, such as duplication, missing values, and wrong data types. It also renames certain column names and forms a new 'Month' column for better analysis.

Exploratory Data Analysis (EDA)
The EDA section includes various visualizations and data analysis steps to gain insights into the dataset. Here's a summary of the EDA performed in the script:

Visualizing Data:
* Countplot of Regions
* Countplot of States
* Countplot of Frequency
* Countplot of Months
* Histogram of Estimated Unemployment Rate (%)
* Histogram of Estimated Employed People
* Histogram of Estimated Labor Participation Rate (%)

Analyzing Data Through Visualization:
   - Visualizing Unemployment Rate:
         * Average Unemployment Rate by Month
         * Subsetting by Months and identifying the state with the highest unemployment rate.
  - Visualizing Estimation of Employed People:
         * Average Employed People by Month
         * Subsetting by Months and identifying the state with the highest employment.
  - Visualizing Estimated Labor Participation Rate:
         * Average Labor Participation Rate by Month
         * Subsetting by Months and identifying the state with the highest labor participation rate.

Identifying Outliers:
Boxplots showing outliers for Estimated Employed People, Estimated Unemployment Rate (%), and Estimated Labor Participation Rate (%), grouped by states.

Conclusion:
The visualizations and data analysis help identify states with high unemployment rates, high employment, and high labor participation rates during specific months. 
