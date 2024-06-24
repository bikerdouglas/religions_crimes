


# Religion and Crime Rates Analysis

**Table of Contents**

Introduction
Data
Setup
Analysis
Results
Conclusion
Introduction

**Introduction**

This project aims to explore the relationship between the religious composition of various countries and their crime rates. The analysis is performed using data on different religions and crime rates from various countries over a specified period. I was curious of whether a countries relgious composition had any correlations with their crimes rates. Specifically asking, do non religious countries have higher crimes rates than religious countries?


The primary objective of this project is to understand how different religious compositions of a population correlate with various crime rates. This includes examining data for different religions such as Islam, Christianity, Hinduism, Buddhism, Judaism, and non-religious groups.

**Setup**

To run the analysis, ensure you have the following libraries installed:

 pandas
 numpy 
 matplotlib.pyplot 
 seaborn
 plotly.express

**Data**

The dataset used in this analysis contains information on:

Kidnappings per 100,000 people
Robberies per 100,000 people
Murders per 100,000 people
Assaults per 100,000 people
Burglaries per 100,000 people
Other relevant crime statistics
These data points are segmented by year and country, alongside the religious composition of the population.


The analysis involves several key steps:

Data Loading and Cleaning:

Load the data into a pandas DataFrame.
Check for and handle any missing values.
Data Filtering:

Filter the data for the range of 2005-2017 to ensure consistency.
Categorization by Religion:

Define thresholds for categorizing countries based on the percentage of the population adhering to different religions.
Plot the average crime rates for these categories to visualize potential correlations.
Plotting:

Generate bar plots to compare average crime rates across different religious compositions.
Results
![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/islam.png?raw=true)
![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/christians.png?raw=true)
![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/non-religious.png?raw=true)
![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/hinduism.png?raw=true)
![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/buddhism.png?raw=true)
![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/judaism.png?raw=true)

![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/all%20religions.png?raw=true)
The results section contains various plots and analyses showing the relationship between the religious composition of a country's population and its crime rates. Each religious group is analyzed separately, and the crime rates are compared across different categories.

**Conclusion**
![alt text](image.png)
The conclusion summarizes the findings and provides insights into the correlations between religious composition and crime rates. It also discusses potential implications and areas for further research.